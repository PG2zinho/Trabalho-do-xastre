Abra o cmd e coloque o comando : 
1- cd(direcionado para a pasta do docker) docker build -t nginx: 1.0 . 

Depois coloque o seguinte comando:
1- cd(direcionado para pasta files) docker run -d -p 9090:80 --name TrabalhoX-docker nginx:1.0
Agora acesse o site 'http://localhost:9090'
