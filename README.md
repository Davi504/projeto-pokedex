# Projeto Pokédex

## Descrição
A Pokédex Interativa é um projeto que exibe informações de Pokémon utilizando a PokéAPI. Ela foi desenvolvida com HTML, CSS/SASS e JavaScript, proporcionando uma interface intuitiva e responsiva, com funcionalidades como busca de Pokémon pelo nome ou número e navegação pelos Pokémon disponíveis.

## Objetivo
O principal objetivo deste projeto é criar uma plataforma interativa onde os fãs de Pokémon possam explorar e descobrir informações sobre seus personagens favoritos de forma rápida e intuitiva.

## Público-alvo
O projeto é destinado a fãs da série Pokémon de todas as idades, desenvolvedores interessados em aprender sobre consumo de APIs públicas e qualquer pessoa que queira explorar informações sobre Pokémon de uma maneira prática e divertida.

## Processo de Desenvolvimento
O desenvolvimento começou com a definição da estrutura HTML e a estilização básica usando SASS. Em seguida, implementei a lógica em JavaScript para consumir a PokéAPI e exibir os dados dos Pokémon. O principal foco foi garantir que a aplicação fosse rápida e responsiva, proporcionando uma experiência de usuário agradável em dispositivos móveis e desktops.

## Problemas Encontrados e Soluções

### Consumo da API e Latência
- **Problema**: As requisições à PokéAPI estavam lentas, especialmente em conexões mais fracas.
- **Solução**: Implementei caching local para armazenar os dados dos Pokémon já carregados, reduzindo o número de chamadas à API e melhorando o desempenho.

### Responsividade do Layout
- **Problema**: A interface não estava se adaptando corretamente em todos os tamanhos de tela.
- **Solução**: Utilizei media queries no SASS para ajustar o layout de acordo com diferentes resoluções, garantindo uma boa aparência em todos os dispositivos.

### Busca por Pokémon
- **Problema**: A função de busca não estava retornando os resultados esperados devido a inconsistências na entrada do usuário.
- **Solução**: Implementei uma normalização das entradas do usuário, convertendo tudo para minúsculas e removendo espaços extras, melhorando a precisão da busca.

### Estilização Complexa com SASS
- **Problema**: Manter a organização e a eficiência do código CSS com SASS estava desafiador à medida que o projeto crescia.
- **Solução**: Adotei a metodologia BEM (Block, Element, Modifier) para nomear classes, mantendo o código modular e fácil de manter.

## Tecnologias Utilizadas
[![My Skills](https://skillicons.dev/icons?i=html,css,sass,javascript)](https://skillicons.dev)

## Funcionalidades
- **Exibição de uma lista de Pokémon** com nome e imagem.
- **Busca interativa** por nome ou número do Pokémon.
- **Layout responsivo** adaptável para dispositivos móveis e desktops.

## Pré-requisitos
- Node.js (opcional, caso deseje compilar o SASS manualmente)
- Navegador de sua preferência

## Como Rodar Localmente

1. **Clonar o Repositório**:
    ```sh
    git clone https://github.com/Davi504/projeto-pokedex
    cd projeto-pokedex
    ```

2. **Instalar as Dependências do SASS (opcional)**:
    ```sh
    npm install -g sass 
    ```

3. **Abrir o Projeto no VS Code**:
    ```sh
    code .
    ```

### Instale a Extensão Live Server

1. Abra o VS Code.
2. Vá para a aba de Extensões.
3. Pesquise por Live Server.
4. Instale a extensão desenvolvida por Ritwick Dey.

### Inicie o Live Server

1. Clique com o botão direito no arquivo `index.html` no explorador de arquivos do VS Code.
2. Escolha a opção Open with Live Server.
3. O projeto será iniciado no navegador, geralmente no endereço `http://127.0.0.1:5500` ou similar.

## Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
