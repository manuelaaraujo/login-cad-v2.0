 # LOGIN - CAD V2.0

* [Atualizações](#atualizações)
* [Introdução](#introdução)
* [Descrição](#descrição)
* [Funcionalidades](#funcionalidades)
* [Referências](#referências)
* [Autores](#autores)

## Atualizações
Este projeto é uma versão aprimorada do [LOGIN CAD v2](https://github.com/manuelaaraujo/login-cad-v2) .
Corrigimos problemas encontrados na versão anterior e introduzimos melhorias significativas na tela de cadastro. Agora, os usuários podem adicionar um novo e-mail, além de salvar, editar ou excluir registros. Também implementamos uma validação para o campo de CPF.

## Introdução
O projeto é um sistema básico de login e cadastro de usuários, criado com JavaScript, HTML e CSS.
 Seu objetivo é oferecer uma interface intuitiva onde os usuários podem se registrar com seus nomes e, posteriormente, visualizar, modificar ou remover suas informações.

## Descrição
Este sistema é uma aplicação web simples desenvolvida com HTML, CSS e JavaScript. Ele permite que os usuários façam login e cadastrem seus nomes, oferecendo uma interface amigável e eficiente para a manipulação dos dados.

## Funcionalidades

``Tela de Login:`` Os usuários acessam uma tela de login onde devem fornecer e-mail e senha. O sistema verifica se ambos os campos estão preenchidos e, se estiverem, redireciona o usuário para a tela de cadastro.

``Cadastro de Usuários:`` Na tela de cadastro, os usuários podem inserir seus nomes, que serão salvos em uma lista. Caso o campo esteja vazio, uma mensagem de alerta solicitará o preenchimento do nome.

``Gerenciamento da Lista de Nomes:`` Os usuários podem visualizar uma tabela com os nomes cadastrados. Cada nome na tabela possui botões para edição e exclusão:

``Editar:`` Ao clicar no botão de editar, o nome selecionado é carregado no campo de entrada, permitindo ao usuário fazer alterações.

``Excluir:`` O botão de excluir remove o nome correspondente da lista.

``Tela de Login:``
O sistema começa com uma tela de login onde o usuário deve inserir e-mail e senha.
Ao clicar no botão de login, o sistema valida se ambos os campos estão preenchidos. Se não estiverem, uma mensagem de alerta solicita o preenchimento dos campos.
Se os campos estiverem preenchidos, o usuário é redirecionado para a tela de cadastro.

``Cadastro de Usuários:``
Na tela de cadastro, o usuário pode inserir seu nome em um campo de texto.
O sistema verifica se o campo está vazio. Se estiver, um alerta pede que o nome seja fornecido.
Se o nome for preenchido, ele é armazenado em um array denominado ´´dadosLista´´, que mantém todos os nomes cadastrados.
Alterações
Os campos para inserir nome e e-mail foram adicionados, juntamente com um botão "SALVAR". Após preencher esses campos e clicar no botão, o nome e e-mail são adicionados à tabela exibida abaixo. Na tabela, existem botões para editar ou excluir os registros existentes.

## Referências
[CHAT GPT](https://chatgpt.com/)

[MDN WEB DOCS](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Indexed_collections)

## Autores
https://github.com/LeonardoRochaMarista

https://github.com/manuelaaraujo