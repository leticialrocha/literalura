##  LiterAlura - Catálogo de Livros  ♡₊˚ 

O **LiterAlura** é um desafio de programação que consiste em desenvolver um catálogo de livros integrando uma API externa (**Gutendex API**) com persistência em banco de dados relacional. O sistema permite realizar buscas, salvar informações e filtrar dados diretamente pelo terminal.

##  Funcionalidades

* **Busca por Título:** Consulta livros na Web via API e registra automaticamente no banco de dados.
* **Listagem de Livros:** Exibe todos os livros salvos com detalhes de título, autor e idioma.
* **Listagem de Autores:** Exibe os autores registrados no sistema.
* **Filtro por Época:** Lista autores que estavam vivos em um determinado ano informado.
* **Filtro por Idioma:** Busca livros registrados de acordo com a sigla do idioma (ex: `pt`, `en`, `fr`).

##  Tecnologias e Lógica

* **Java 17 & Spring Boot:** Base do desenvolvimento da aplicação.
* **Spring Data JPA:** Para comunicação simplificada com o banco de dados.
* **PostgreSQL:** Banco de dados relacional para persistência dos livros e autores.
* **Jackson:** Biblioteca utilizada para desserializar os dados JSON recebidos da API Gutendex.
* **API Gutendex:** Fonte de dados externa para consulta de obras literárias.

##  Estrutura do Projeto

* **Model:** Classes que representam as entidades (Livro, Autor) e DTOs para mapeamento JSON.
* **Repository:** Interfaces para manipulação dos dados no banco.
* **Service:** Classes responsáveis pelo consumo da API e conversão de dados.
* **Principal:** Classe que gerencia o menu interativo e a lógica de exibição no terminal.

##  Como Executar

1. Clone o repositório.
2. Configure as credenciais do seu banco de dados PostgreSQL no arquivo `application.properties`.
3. Execute a aplicação através da classe `LiteraluraApplication`.
4. Utilize o menu interativo no console para navegar pelas opções.

---
Desenvolvido com ♡ por Leticia Almeida 
