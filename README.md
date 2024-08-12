# Aluno: Bruno Felipe Santana de Melo

Para a atividade, criei um banco de dados com H2 Database, possuindo as tabelas ALUNO, EMPRESTIMO e PUBLICACAO, representando um sistema de biblioteca. Adcionei as relações entre tabelas com as “foreign keys”.
A conexão com o H2 Database foi feita usando o driver e o caminho local do banco de dados. As classes foram geradas automaticamente pelo NetBeans, que mapeou as tabelas escolhidas e as ligou aos atributos das classes que serão usadas em Java.

# Atividade DAO

Essa é a classe principal do projeto, responsável por executar os testes da classe Empréstimo DAO.

# Classe DAO

A classe padrão DAO tem a responsabilidade de aplicar essa arquitetura a qualquer classe-entidade do sistema. Ela gerencia as entidades por meio das classes da biblioteca "javax.persistence" e implementa os métodos de CRUD (findAll, insert, update e delete) para manipulação do banco de dados.

# Empréstimo DAO

A classe Empréstimo herda o padrão DAO, sobrescrevendo os métodos de CRUD definidos na classe DAO padrão. Ela utiliza a API Criteria para consultar os dados presentes no banco de dados e a classe Transaction para realizar operações de inserção, atualização e exclusão.
