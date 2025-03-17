# MinhaAppFuncional / AppMvcFuncional

MinhaAppFuncional é um projeto de exemplo desenvolvido seguindo o curso **Fundamentos do ASP.NET MVC** da [Desenvolvedor.io](https://desenvolvedor.io). Este projeto utiliza ASP.NET Core Razor Pages e demonstra a criação, edição, visualização e exclusão de registros de alunos.

## Funcionalidades

- Listar alunos
- Visualizar detalhes de um aluno
- Criar um novo aluno
- Editar um aluno existente
- Excluir um aluno

## Tecnologias Utilizadas

- .NET 8
- ASP.NET Core MVC
- Entity Framework Core
- Microsoft SQL Server

## Requisitos

- .NET 8 SDK
- SQL Server

## Configuração do Projeto

1. Clone o repositório:
   

2. Navegue até o diretório do projeto:

3. Configure a string de conexão com o banco de dados no arquivo `appsettings.json`:

4. Execute as migrações para criar o banco de dados:

5. Execute o projeto:

## Uso

- Acesse a aplicação em `https://localhost:5001`
- Utilize as rotas para gerenciar os alunos:
  - `/meus-alunos` - Listar alunos
  - `/meus-alunos/detalhes/{id}` - Visualizar detalhes de um aluno
  - `/meus-alunos/novo` - Criar um novo aluno
  - `/meus-alunos/editar/{id}` - Editar um aluno existente
  - `/meus-alunos/excluir/{id}` - Excluir um aluno

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
