Este repositório contém o projeto LojaEsportes_WebApp, um e-commerce desenvolvido com ASP.NET Core 8.0, oferecendo funcionalidades como catálogo de produtos, carrinho de compras, checkout e painel administrativo. Ele utiliza o Entity Framework Core para acesso a dados e o SQL Server como banco de dados.

Este projeto é uma implementação baseada no material do livro Pro ASP.NET Core 6 (Cap08), com fins educacionais e de demonstração, incorporando melhorias e atualizações para a versão mais recente do framework.

## Atualizações do Projeto:

Este projeto foi atualizado para .NET 8.0, garantindo compatibilidade com a versão mais recente do framework, além de aprimoramentos de desempenho e estabilidade.

### Melhorias implementadas:
- Migração completa de .NET 6 para .NET 8.0
- Atualização de pacotes NuGet para versões compatíveis
- Aproveitamento das otimizações de desempenho do .NET 8
- Expansão do conjunto de funcionalidades para melhor experiência do usuário
- Implementação de navegação por categorias
- Sistema completo de carrinho de compras
- Testes unitários com MOQ e xUnit

### Tecnologias Utilizadas
- ASP.NET 8.0+ – Framework web principal
- Entity Framework Core – ORM para acesso a dados
- SQL Server LocalDB – Banco de dados local
- Bootstrap – Estilização da interface
- MOQ – Framework para mocking em testes
- xUnit – Framework para testes unitários

### Funcionalidades Implementadas
- Infraestrutura central do aplicativo
- Modelo de domínio com repositório de produtos
- Acesso ao SQL Server via Entity Framework Core
- Listagem paginada de produtos no controlador Home
- Esquema de URL limpo e amigável
- Navegação por categorias com filtragem de produtos
- Carrinho de compras com adição/remoção de itens
- Resumo do pedido com cálculo do total
- Fluxo de compra (Continuar comprando/Finalizar compra)
