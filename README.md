<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/lucianfiocello/devfreela?color=%2304D361">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/lucianfiocello/devfreela">  
  <a href="https://github.com/lucianfiocello/devfreela/tree/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/lucianfiocello/devfreela">
  </a>    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">   
</p>

<h1 align="center">
    Cartório de Registros
</h1>

<h4 align="center"> 
	Em desenvolvimento
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#%EF%B8%8F-funcionalidades">Funcionalidades</a> •
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>

## 💻 Sobre o projeto

Cartório de Registros foi um projeto desenvolvido para testar os conhecimentos em C# e Windows Forms.

---

## ⚙️ Funcionalidades

- [x] Tela de login.
- [x] Cadastro, edição de registros de casamentos.
- [x] Cadastro, edição de registros de nascimentos.
- [x] Cadastro, edição de registros de óbitos.
- [x] Relatórios em TXT e XML de registros de casamentos.
- [x] Relatórios em TXT e XML de registros de nascimentos.
- [ ] Relatórios em TXT e XML de registros de óbitos.

---

## 🚀 Como executar o projeto

1. Windows Forms

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [.NET Framework 4.8](https://go.microsoft.com/fwlink/?linkid=2088631),
[PostgreSQL](https://www.postgresql.org/download/).
Além disto é necessário ter o Visual Studio instalado [Visual Studio](https://visualstudio.microsoft.com/pt-br/downloads/).

### 🎲 Rodando o Cartório de Registros

Instale o banco de dados PostgreSQL e configure o usuário "postgres" com a senha "pzub2kDAYT" (sem as ").

```bash

# Clone este repositório
$ git clone https://github.com/lucianfiocello/cartorio-de-registros.git

```

Na pasta CartorioFacil abra o arquivo CartorioFacil.sln com o Visual Studio.
Agora será necessário criar o banco de dados, para isso clique no menu Tools > NuGet Package Manager > Package Manager Console e digite o comando abaixo:

```bash

# Cria ou atualiza o banco de dados
update-database

```

Agora clique em Start para iniciar a aplicação.

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Server**

- **[.NET Framework](https://dotnet.microsoft.com/en-us/)**

#### **Utilitários**

- IDE: **[Visual Studio](https://visualstudio.microsoft.com/)**

---

### Autor

 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/60575473?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Lucian Rezende</b></sub>

[![Linkedin Badge](https://img.shields.io/badge/-Lucian-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucianrezende/)](https://www.linkedin.com/in/lucianrezende/)
[![Gmail Badge](https://img.shields.io/badge/-lucianfiocello@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:lucianfiocello@gmail.com)](mailto:lucianfiocello@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).
