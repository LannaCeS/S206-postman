# S206-postman
Codes developed for Postman studying.

# Arquivos
Postman-Pokemon.postman_collection.json: arquivo JSON com as informações das requisições testadas em aula.  
newman/ : contém o arquivo html com o relatório da execução dos scripts de teste para cada requisição testada.  
Lista2/: pasta que contém os exercícios referentes à segunda lista, sobre a API [Dog API](https://dog.ceo/dog-api/).

# Execução da lista 2

## 1) Clonar repositório  

    git clone https://github.com/LannaCeS/S206-postman.git  
    cd S206-postman/Lista2

## 2) Usando Newman (CLI)  

Instalar as dependências  

    npm install  

Instalar Newman  

    npm install -g newman  
    npm install -g newman-reporter-html  

Rodar a collection gerando o relatório HTML 

    newman run "Dog-API.postman_collection.json" -r htmlextra  

Acesso ao relatório HTML  
O relatório de teste se encontra na pasta "newman" dentro da [Lista2](https://github.com/LannaCeS/S206-postman/tree/main/Lista2).