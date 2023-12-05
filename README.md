# chess-system

Projeto Sistema: Jogo de Xadrez

Descrição do Projeto
Este projeto é um sistema de jogo de xadrez desenvolvido em Java, utilizando o framework Spring para criar uma API REST. O objetivo é proporcionar uma plataforma para que os jogadores possam desfrutar de partidas de xadrez online. O projeto abrange conceitos importantes, como API REST, entidades e ORM, seeding de banco de dados, padrão de camadas, controllers, serviços, repositórios e padrão DTO.

Tecnologias Utilizadas
Java
Spring Framework (Spring Boot, Spring Web, Spring Data JPA)
Entidades ORM (Banco de Dados H2)
Maven (para gerenciamento de dependências)
DTO (Data Transfer Object)

Estrutura do Projeto
O projeto segue um padrão de camadas para garantir uma arquitetura organizada e modular. A estrutura inclui:

Service: Camada que contém a lógica de negócios do sistema, manipulando dados e interagindo com o banco de dados.

Repository: Camada responsável por interagir diretamente com o banco de dados, realizando operações CRUD (Create, Read, Update, Delete).

DTO (Data Transfer Object): Objetos utilizados para transferir dados entre as camadas, ajudando a reduzir o acoplamento e melhorar a modularidade.

Execução do Projeto
Para executar o projeto, siga os passos abaixo:

Certifique-se de ter o Java e o Maven instalados na sua máquina.
Clone o repositório para sua máquina local.
Configure as propriedades do banco de dados no arquivo src/main/resources/application.properties ou src/main/resources/application.yml.
Execute o comando mvn spring-boot:run no diretório do projeto.
O servidor será iniciado, e você poderá acessar a API REST através do endpoint padrão (por exemplo, http://localhost:8080).

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, propor melhorias ou enviar pull requests.

Agradecimento
Espero que este projeto de jogo de xadrez seja útil e educativo. Divirta-se jogando xadrez online!
