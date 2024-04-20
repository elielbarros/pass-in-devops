Execute na pasta principal do projeto o comando
- ```docker build -t passin:v1 -f <dockerfile-path>```

Execute a aplicação com o seguinte comando
- ```docker run -p 3001:3333 -d passin:v1```