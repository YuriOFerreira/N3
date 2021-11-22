# Passo a passo para executar o código:

## Instruções de inicialização

Primeiro deve clonar o código do repósitorio
se houver dúvidas ou dificuldade seque link para ajudar
https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository.
Com o código baixado vá até a pasta do arquivo pelo Terminal ou CMD de sua maquina, em seguida de o seguinte comando:

```
npm start
```

Recomendo para testes o Postman segue link para download:
https://www.postman.com/downloads/


## Persistencia de Dados

Os dados são salvos no banco de dados MongoDB.
registrados dessa forma:

•	Pessoas: Nome, sobrenome
•	Salas: Nome, lotacao

## Endpoints para teste

• Realizar o cadastro de pessoas, com nome e sobrenome: http://localhost:4000/pessoa = POST
• Realizar a consulta de uma pessoa pelo nome: http://localhost:4000/pessoa/Yuri = GET
• Realizar a remoção de uma pessoa pelo id: http://localhost:4000/pessoa/619a9525ebf4ab284904deec = DEL
• Realizar a listagem de todas as pessoas: http://localhost:4000/pessoa = GET
• Realizar o cadastro das salas do evento, com nome e lotação: http://localhost:4000/sala = POST
• Realizar a consulta de uma sala específica pelo id: http://localhost:4000/sala/619ad11901cffc4820b558c6 = GET  
• Realizar a alteração do nome e da lotação de uma sala específica: http://localhost:4000/sala/619ad11901cffc4820b558c6 = PUT
