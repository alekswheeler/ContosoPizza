# ContosoPizza 🇧🇷

## Descrição do Projeto

Este projeto, chamado ContosoPizza, consiste na implementação de uma RESTful Web API usando a linguagem C# e o ASP.NET Core. A aplicação segue a arquitetura Modelo-Visão-Controlador (MVC) para organizar e estruturar o código de forma eficiente e escalável.

## Estrutura e Organização do Projeto

O projeto ContosoPizza está organizado conforme a arquitetura Modelo-Visão-Controlador (MVC), que consiste nas seguintes camadas:

- **Models**: Contém as classes que representam os modelos de dados da aplicação, definindo a estrutura e comportamento dos objetos manipulados pela API.
- **Views**: Representa a camada de apresentação, que normalmente inclui a interface do usuário, mas, no contexto de uma API, pode incluir a estrutura dos dados de saída.
- **Controllers**: Responsável por receber as requisições dos clientes, processar as informações e interagir com a camada de modelo para executar as operações necessárias.
- **Services**: Agrupa a lógica de negócios e a lógica de acesso a dados que não estão diretamente relacionadas a um modelo específico.

## Endpoints do CRUD

A API ContosoPizza oferece os seguintes endpoints para realizar operações CRUD (Criar, Ler, Atualizar, Deletar) relacionadas aos recursos disponíveis:

- **Criar**:
  - `POST /api/pizza`: Cria uma nova pizza.

- **Ler**:
  - `GET /api/pizza`: Obtém a lista de todas as pizzas.
  - `GET /api/pizza/{id}`: Obtém os detalhes de uma pizza específica com base no ID.

- **Atualizar**:
  - `PUT /api/pizza/{id}`: Atualiza os detalhes de uma pizza existente com base no ID.

- **Deletar**:
  - `DELETE /api/pizza/{id}`: Deleta uma pizza com base no ID.
 
## Experiência com o Template .NET Core

Este projeto, apesar de ser meu primeiro, foi enriquecedor devido às facilidades oferecidas pelo template .NET Core. A abordagem focada na criação eficiente das rotas CRUD e na automação das mensagens HTTP nativas foi um diferencial. Isso permitiu que eu me concentrasse na implementação das regras de negócio e do CRUD sem perder tempo com aspectos mais triviais.

Uma funcionalidade que me impressionou foi a presença do Swagger já integrado no template. Após a implementação dos endpoints, a documentação e a interface de implementação foram geradas automaticamente, economizando um tempo valioso durante o desenvolvimento.

Irei implementar os repositórios de persistência de dados no próximo tutorial em breve.

Estou ansioso para continuar explorando e aprimorando este projeto, aproveitando ao máximo as vantagens oferecidas pelo ecossistema .NET Core.

## Próximos Passos:

- Implementar a persistência de dados utilizando o [Entity Framework Core](https://learn.microsoft.com/pt-br/training/modules/persist-data-ef-core/) no próximo tutorial.
- Estudar algumas das classes base de controladores do ASP.NET Core.

---

# ContosoPizza 🇺🇸

## Project Description
 
This project, named ContosoPizza, involves the implementation of a RESTful Web API using C# language and ASP.NET Core. The application follows the Model-View-Controller (MVC) architecture to efficiently organize and structure the code.

## Project Structure and Organization

The ContosoPizza project is organized following the Model-View-Controller (MVC) architecture, which consists of the following layers:

- **Models**: Contains classes representing the data models of the application, defining the structure and behavior of the objects manipulated by the API.
- **Views**: Represents the presentation layer, which typically includes the user interface but in the context of an API, it may involve the structure of the output data.
- **Controllers**: Responsible for receiving client requests, processing the information, and interacting with the model layer to perform the necessary operations.
- **Services**: Groups business logic and data access logic that is not directly related to a specific model.

## CRUD Endpoints

The ContosoPizza API offers the following CRUD (Create, Read, Update, Delete) endpoints related to the available resources:

- **Create**:
  - `POST /api/pizza`: Creates a new pizza.

- **Read**:
  - `GET /api/pizza`: Retrieves the list of all pizzas.
  - `GET /api/pizza/{id}`: Retrieves details of a specific pizza based on ID.

- **Update**:
  - `PUT /api/pizza/{id}`: Updates details of an existing pizza based on ID.

- **Delete**:
  - `DELETE /api/pizza/{id}`: Deletes a pizza based on ID.

## Experience with the .NET Core Template

This project, despite being my first, was enriching due to the facilities provided by the .NET Core template. The approach focused on efficiently creating CRUD routes and automating native HTTP messages was a differential. It allowed me to focus on implementing business rules and CRUD without wasting time on more trivial aspects.

One feature that impressed me was the presence of Swagger already integrated into the template. After implementing the endpoints, the documentation and implementation interface were generated automatically, saving valuable time during development.

I will implement the data persistence repositories in the upcoming tutorial soon.

I look forward to continuing to explore and enhance this project, making the most of the advantages offered by the .NET Core ecosystem.

## Next Steps:

- Implement data persistence using [Entity Framework Core](https://learn.microsoft.com/pt-br/training/modules/persist-data-ef-core/) in the upcoming tutorial.
- Study some of the base controller classes in ASP.NET Core.
