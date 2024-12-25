# Projeto-pokedex

## Descrição

 A Pokédex Interativa é um projeto que exibe informações de Pokémon utilizando a PokéAPI. Ela foi desenvolvida com HTML, CSS/SASS e JavaScript, proporcionando uma interface intuitiva e responsiva, com funcionalidades como busca de Pokémon pelo nome ou número e navegação pelos Pokémon disponíveis.

## Processo de Desenvolvimento:
O desenvolvimento começou com a definição da estrutura HTML e a estilização básica usando SASS. Em seguida, implementei a lógica em JavaScript para consumir a PokéAPI e exibir os dados dos Pokémon. O principal foco foi garantir que a aplicação fosse rápida e responsiva, proporcionando uma experiência de usuário agradável em dispositivos móveis e desktops.

## Problemas Encontrados e Soluções:
### Consumo da API e Latência:

  - Problema: As requisições à PokéAPI estavam lentas, especialmente em conexões mais fracas.

  - Solução: Implementei caching local para armazenar os dados dos Pokémon já carregados, reduzindo o número de chamadas à API e melhorando o desempenho.

### Responsividade do Layout:

  - Problema: A interface não estava se adaptando corretamente em todos os tamanhos de tela.

  - Solução: Utilizei media queries no SASS para ajustar o layout de acordo com diferentes resoluções, garantindo uma boa aparência em todos os dispositivos.

### Busca por Pokémon:

  - Problema: A função de busca não estava retornando os resultados esperados devido a inconsistências na entrada do usuário.

  - Solução: Implementei uma normalização das entradas do usuário, convertendo tudo para minúsculas e removendo espaços extras, melhorando a precisão da busca.

### Estilização Complexa com SASS:

  - Problema: Manter a organização e a eficiência do código CSS com SASS estava desafiador à medida que o projeto crescia.

  - Solução: Adotei a metodologia BEM (Block, Element, Modifier) para nomear classes, mantendo o código modular e fácil de manter.

## Tecnologias utilizadas

[![My Skills](https://skillicons.dev/icons?i=html,css,sass,javascript)](https://skillicons.dev)

## Funcionalidades

- Exibição de uma lista de Pokémon com nome e imagem.
- Busca interativa por nome ou número do Pokémon.
- Layout responsivo adaptável para dispositivos móveis e desktops.

## Pré Requisitos

- Node.js (opcional, caso deseje compilar o SASS manualmente)
- Navegador de sua preferência.
  
## Como rodar localmente

- clone o repositório:

``` sh
  git clone https://github.com/Davi504/projeto-pokedex
  cd projeto-pokedex
```

- Instale as dependências do SASS (opcional):
 
``` sh
  npm install -g sass 
```

- Abra o projeto no vscode:
``` sh
  code .
```

### Instale a extensão live server

- Abra o VS Code.
- Vá para a aba de Extensões
- Pesquise por Live Server.
- Instale a extensão desenvolvida por Ritwick Dey.

### Inicie o Live Server

- Clique com o botão direito no arquivo `index.html` no explorador de arquivos do VS Code.
- Escolha a opção Open with Live Server.
- O projeto será iniciado no navegador, geralmente no endereço `http://127.0.0.1:5500` ou similar.





## Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
