# ProjetoLoja_Csharp
GitHub Destinado ao projeto loja de C#


https://github.com/Fiap-DEV/ProjetoLoja.git


1. Camada de Dados & Modelagem

Banco de Dados: Criar a tabela Clientes com os campos: Nome, Telefone e Email.
Model: Mapear a entidade Cliente no projeto, garantindo as anotações de validação ([Required], [EmailAddress]).

2. Camada de Persistência (Repositorio Pattern)

Interface: Definir IClienteRepositoio para garantir a abstração dos métodos de persistência.
Repositório: Implementar a classe ClienteRepository com a lógica de acesso ao banco.
Injeção de Dependência: Registrar o serviço no container Program.cs.

3. Camada de Controle e Visão

Controller: Criar a ClientesController, aplicando os atributos de autorização [Authorize] para proteger as rotas.
Views: Desenvolver as telas de Listagem e Cadastro utilizando componentes do Bootstrap.
Layout: Atualizar o menu de navegação principal (_Layout.cshtml) para incluir o link de acesso ao novo módulo
