# Literalura

<div align ="center">

[![Java Version](https://img.shields.io/badge/Java-8%2B-blue)](https://www.java.com/)
![GitHub repo size](https://img.shields.io/github/repo-size/rodrigoborge/Literalura)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rodrigoborge/Literalura)

</div><br>

 # Configure o banco de dados no arquivo 
`application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

## Estrutura do Projeto

- `br.com.alura.literalura`: Pacote principal do projeto.
  - `principal`: Contém a classe `Principal`, que gerencia a execução da aplicação.
  - `model`: Contém as classes de modelo (`Livro`, `Autor`, `LivroDTO`, `AutorDTO`).
  - `repository`: Contém as interfaces de repositório Spring Data JPA.
  - `service`: Contém as classes de serviço (`ConsumoAPI`, `ConverteDados`).

