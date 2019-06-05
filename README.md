# Resumo

Implementar uma Web Service RESTful capaz de se comunicar com aplicações mobile e web.

O Web Service deverá ter as operações de um C.R.U.D.:

- Listar itens
- Exibir item
- Adicionar item
- Editar item
- Apagar item

Deverão existir três ou mais entidades relacionadas com a entidade principal. Porém, só é necessário listar, exibir, adicionar, editar e apagar itens da entidade principal.

Você é livre para escolher quais os atributos de cada entidade.


# Instruções

- Criar três ou mais Models
- Ter uma associação entre Models do tipo 1..n
- Ter uma associação entre Models do tipo 1..1
- A aplicação deve ser Rails API-only
- Elaborar documento de especificação das chamadas ao WebService
- Seguir os padrões e convenções do Ruby on Rails
- Seguir o padrão RESTful
- Seguir Normalização do Banco de Dados
- Utilizar RSpec para escrita de testes (pode escrever o teste antes ou depois, mas é importante testar)
- Utilizar Ruby on Rails 5 ou superior
- Utilizar Ruby 2.5.0 ou superior
- Utilizar o RVM ou outra ferramenta para gerenciamento de versões Ruby
- Enviar o código para o github
- Hospedar a aplicação no Heroku

Plus (não obrigatório)

- Utilizar Swagger ou Apiary para documentação da API
- Criar uma aplicação web separada em Ruby on Rails que consuma o Web Service - criado, utilizando VueJS ou React
- Utilizar FactoryBot
