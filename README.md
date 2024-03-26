# Biblioteca de Jogos

Um projeto prático guiado pelo instrutor Isaac Pontes da OneBitCode para uma biblioteca de jogos utilizando React.

## Visão Geral

Este projeto é uma aplicação web para gerenciar uma biblioteca de jogos. Os usuários podem adicionar novos jogos à biblioteca, visualizar os jogos existentes e remover jogos conforme necessário.

## Componentes

O projeto é composto pelos seguintes componentes:

- `App.jsx`: Componente principal que renderiza a interface do usuário e gerencia o estado da biblioteca de jogos.
- `components/Game.jsx`: Componente responsável por exibir informações sobre um jogo, como título e capa, e permite que os usuários removam o jogo da biblioteca.
- `components/NewGameForm.jsx`: Componente que fornece um formulário para os usuários adicionarem novos jogos à biblioteca.
- `components/TextInput.jsx`: Componente reutilizável para campos de entrada de texto.
- `index.css`: Estilos CSS globais aplicados à aplicação.
- `main.jsx`: Arquivo responsável por renderizar o componente `App` na página HTML.
- `hooks/useGameCollection.js`: Um hook customizado para gerenciar a coleção de jogos na aplicação.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

src/
|__ components/
|   |__ Game.jsx
|   |__ NewGameForm.jsx
|   |__ TextInput.jsx
|
|__ hooks/
|   |__ useGameCollection.js
|
|__ App.jsx
|__ index.css
|__ main.jsx

## Como Executar

Para executar o projeto localmente, siga estas etapas:

1. Clone este repositório.
2. Instale as dependências do projeto usando `npm install`.
3. Execute o projeto usando `npm run dev`.
4. Abra o navegador e acesse o endereço local fornecido pelo seu ambiente de desenvolvimento para visualizar o aplicativo.

## Autor

Este projeto foi desenvolvido como parte do curso de Desenvolvedor Fullstack JavaScript da OneBitCode.
