# Pokédex Interativa - Fetch API

Projeto desenvolvido para praticar o consumo de APIs RESTful reais e públicas utilizando JavaScript moderno (`Fetch API`, `async/await` e manipulação do DOM) sem recarregar a página.

## Funcionalidades

- **Busca Dinâmica:** Pesquisa qualquer Pokémon pelo nome (ex: `pikachu`, `charizard`) ou pelo número da Pokédex (ex: `25`, `6`).
- **Tratamento de Entrada:** Converte automaticamente o texto digitado para letras minúsculas e remove espaços extras.
- **Feedback Visual:** Exibe mensagem de carregamento durante a requisição e mensagens de erro claras caso o Pokémon não seja encontrado (erro 404).
- **Exibição de Dados:** Renderiza o número de identificação (`#ID`), a arte oficial em alta resolução, o nome e o tipo principal do Pokémon.

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página e formulário de busca.
- **CSS3:** Estilização responsiva, layout com Flexbox e controle de visibilidade do card.
- **JavaScript (ES6+):** Requisições assíncronas com `fetch`, `async/await`, tratamento de exceções com `try...catch` e manipulação do DOM.
- **PokéAPI:** API RESTful pública utilizada como fonte de dados (`https://pokeapi.co/api/v2/pokemon/`).

## Estrutura de Arquivos

```text
aula8-pokedex-fetch/
├── index.html   # Estrutura da interface e elementos do card
├── style.css    # Estilos visuais e classes de estado (.oculto)
├── script.js    # Lógica de requisição à API e atualização do DOM
└── README.md    # Documentação do projeto
