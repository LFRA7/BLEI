# 📚 BLEI - Biblioteca Universitária

**BLEI** é uma aplicação desenvolvida em **ASP.NET Core** com o objetivo de gerir o sistema de uma biblioteca universitária. O sistema permite gerir livros, utilizadores, empréstimos, devoluções e outras funcionalidades essenciais para o bom funcionamento de uma biblioteca acadêmica.

Além disso, conta com **autenticação segura** baseada em **Entity Framework**, garantindo o controlo de acesso de usuários.

---

## 🛠️ Tecnologias Utilizadas

- [ASP.NET Core](https://learn.microsoft.com/aspnet/core) — Framework web moderno da Microsoft;
- C# — Linguagem de programação;
- [Entity Framework Core](https://learn.microsoft.com/ef/core) — ORM para acesso a banco de dados;
- SQL Server — Banco de dados utilizado;
- MVC — Model-View-Controller;
- Autenticação com Identity (via Entity Framework).

---

## ✅ Funcionalidades

- 📘 Cadastro de livros: inclusão, edição, listagem e remoção de livros;
- 👤 Gerir usuários: registro de Leitores, Bibliotecários e Administradores;
- 🔄 Controlo de empréstimos: sistema de requisição e devolução de livros;
- 🕓 Histórico de empréstimos: registro completo de movimentações de cada usuário;
- 📊 Controlo de disponibilidade: mostra livros disponíveis ou emprestados;
- ⏰ Alertas: Emissão de alerta caso o utilizador tenha livros que já passou a data de devolução;
- 🔍 Busca e filtros: permite encontrar livros por nome, autor, categoria, etc;
- 🔐 Autenticação segura com ASP.NET Identity: controlo de acesso seguro.
