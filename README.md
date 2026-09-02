# ConstruLar_Atividade

# Sistema de Locação de Equipamentos

Trabalho da disciplina de DS, proposto pelo professor Arnaldo Hidalgo, sobre a criação de um layout digital para uma empresa de locação de equipamentos leves, médios e pesados.

**Alunos:** Nathan Gabriel Affonso Cortello (RM 25068) e Lucas Henrique Rodrigues Caldas (RM 25301)

## Sobre o projeto

A ideia é criar o layout de um sistema para uma empresa que aluga equipamentos, com uma parte voltada para os usuários (que podem se cadastrar e solicitar equipamentos) e outra voltada para os administradores (que gerenciam os equipamentos, acompanham empréstimos, geram relatórios, etc).

Antes de começar a desenhar as telas, levantamos os requisitos funcionais e não funcionais do sistema, que estão detalhados no arquivo [`requisitos.md`](./requisitos.md). Esse levantamento serviu de base pra pensar quais telas eram necessárias e o que cada uma delas precisava ter.

## Status atual

Até o momento o projeto está na etapa de **prototipação no Figma**. Ainda não iniciamos a codificação das páginas — o repositório, por enquanto, serve para reunir a documentação e o levantamento de requisitos do projeto.

## Telas desenvolvidas

Já temos protótipos navegáveis para duas partes do sistema:

**Cadastro e login (Flow 2)**
Telas de formulário para o usuário se cadastrar (com campos como e-mail, senha, telefone e CPF) e fazer login no sistema, atendendo aos requisitos RF01 e RF02.

**Painel do administrador**
Conjunto de telas do lado administrativo, com menu lateral de navegação, tabelas de equipamentos e um dashboard com gráficos (visão geral, distribuição por categoria e evolução ao longo do tempo). Essa parte cobre principalmente os requisitos ligados ao cadastro de equipamentos, controle de empréstimos/agendamentos e geração de relatórios (RF09, RF11, RF14 e RF20). O acesso a essa área é restrito, só entra quem tem cadastro de administrador — como já pedia o RF06.

Vale reforçar que nem todos os requisitos levantados foram cobertos nos protótipos até agora, já que o trabalho ainda está em desenvolvimento.

## Links do projeto

📌 Figma: [inserir link aqui]
📌 GitHub: [inserir link aqui]

## Entregáveis

- [x] Levantamento de requisitos
- [x] Protótipo navegável no Figma
- [ ] Codificação das páginas
- [x] Documentação do projeto
