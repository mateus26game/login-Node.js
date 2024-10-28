# Projeto de Sistema de Login com Node.js e MongoDB

Este projeto é um sistema de autenticação simples desenvolvido com Node.js e Express, utilizando MongoDB como banco de dados. O objetivo é fornecer uma interface para usuários se registrarem e efetuarem login.

Funcionalidades
---
  
* Cadastro de Usuário: Permite que novos usuários se registrem informando um nome e uma senha. O sistema verifica se o usuário já existe antes de criar um novo registro.
  
* Login de Usuário: Permite que usuários existentes façam login usando seu nome e senha. O sistema valida as credenciais e direciona o usuário para uma página de boas-vindas.

* Rotas: O aplicativo possui rotas para as páginas de login e cadastro, além de um redirecionamento para a página inicial após o login bem-sucedido.

Tecnologias Utilizadas
---

* Node.js: Ambiente de execução para JavaScript no servidor.
  
* Express: Framework web para facilitar o desenvolvimento de aplicações Node.js.
  
* MongoDB: Banco de dados NoSQL para armazenamento dos dados de usuários.
  
* HBS: Mecanismo de template utilizado para renderizar as páginas HTML.
  
Estrutura do Projeto
---

* app.js: Arquivo principal que configura o servidor e as rotas.

* mongo.js: Configuração do Mongoose e definição do esquema de login.

* views/: Contém os arquivos de template (HBS) para as páginas do aplicativo.

* public/: Diretório para arquivos estáticos, como CSS.
