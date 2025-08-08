# Comunidade Impressionadora

## Visão Geral do Projeto

Este projeto é uma plataforma de comunidade online desenvolvida como parte do curso de Python da Hashtag Treinamentos. O objetivo principal é criar um ambiente onde usuários possam se registrar, criar posts e interagir em um fórum simples. A aplicação é construída com o framework web **Flask** em Python e utiliza um banco de dados **SQLite** para persistência de dados.

## Funcionalidades Principais

-   **Autenticação de Usuário**: Registro de novos usuários e login seguro com criptografia de senhas (bcrypt).
-   **Gerenciamento de Perfil**: Os usuários podem visualizar e editar seus próprios perfis, incluindo foto de perfil e cursos que estão fazendo.
-   **Posts**: Usuários autenticados podem criar, editar e excluir seus próprios posts.
-   **Fórum de Discussão**: Uma página inicial que exibe todos os posts da comunidade em ordem cronológica.

## Tecnologias Utilizadas

-   **Backend**: Python, Flask
-   **Banco de Dados**: SQLite (configurado via SQLAlchemy)
-   **Frontend**: HTML, CSS, Bootstrap 5
-   **Autenticação**: Flask-Login, Bcrypt
