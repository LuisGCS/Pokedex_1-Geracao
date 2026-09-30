# 🔴 Pokédex

Pokédex feita com JavaScript que busca os dados de cada Pokémon na [PokéAPI](https://pokeapi.co/). Você pesquisa por **nome ou número** e navega entre os Pokémon com os botões **Prev** e **Next**.

<!-- Coloque aqui um print da tela: ![Pokédex](img/print.png) -->

## Tecnologias

- HTML5
- CSS3
- JavaScript (`fetch`, `async/await`)
- [PokéAPI](https://pokeapi.co/)

## Como funciona

- O formulário envia o nome ou número digitado para a PokéAPI.
- Se o Pokémon existe, a tela mostra o número, o nome e a imagem animada.
- Se não existe, aparece "Not Found".
- Os botões Prev e Next andam para o Pokémon anterior e o próximo.

## Estrutura

```
Pokedex_1-Geracao/
└── POKEMON/
    ├── favicons/
    ├── img/          # imagem da Pokédex
    ├── index.html
    ├── script.js     # busca na API e controle da tela
    └── style.css
```

## Como rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/LuisGCS/Pokedex_1-Geracao.git
   ```
2. Abra `POKEMON/index.html` no navegador. É preciso estar conectado à internet, porque os dados vêm da API.

## Próximos passos

- [ ] Publicar online com GitHub Pages
- [ ] Mostrar tipo e habilidades de cada Pokémon

## Autor

Feito por [Luis Guilherme](https://github.com/LuisGCS).
