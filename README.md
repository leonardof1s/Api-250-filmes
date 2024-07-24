# Api-250-filmes

Este projeto tem como objetivo buscar os 250 melhores filmes com as melhores notas da internet utilizando a API do IMDb. Faz parte de uma imersão na Alura, focada em APIs e Orientação a Objetos.

## Funcionalidades

- Consultar a API do IMDb para obter uma lista dos 250 melhores filmes.
- Exibir os filmes com suas respectivas notas.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **API do IMDb**: Fonte dos dados dos filmes.
- **IDE Visual Studio Code**: Ambiente de desenvolvimento utilizado.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `src/`: Diretório contendo o código-fonte do projeto.
  - `Main.java`: Classe principal que executa o programa.
  - `Filme.java`: Classe que representa um filme.
  - `ImdbApi.java`: Classe que realiza a conexão com a API do IMDb e busca os dados dos filmes.
  - `FilmeService.java`: Classe que gerencia a lógica de negócio relacionada aos filmes.

## Como Executar

1. Clone o repositório para sua máquina local:
    ```sh
    git clone https://github.com/seu-usuario/api-250-filmes.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd api-250-filmes
    ```

3. Compile o projeto:
    ```sh
    javac -d bin src/*.java
    ```

4. Execute o projeto:
    ```sh
    java -cp bin Main
    ```

## Exemplo de Uso

Quando o programa for executado, ele irá buscar e exibir a lista dos 250 melhores filmes do IMDb:

```sh
Buscando os 250 melhores filmes...
1. Um Sonho de Liberdade - Nota: 9.3
2. O Poderoso Chefão - Nota: 9.2
...
250. Guerra nas Estrelas - Nota: 8.0

