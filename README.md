<div align="center" id="top">
  <img src="./.github/app.gif" alt="Dissertacao" />

  &#xa0;

  <!-- <a href="https://dissertacao.netlify.app">Demo</a> -->
</div>

<h1 align="center">Dissertação</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/dissertacao?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Dissertacao 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0;
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

cluster semente

## Escopo do projeto ##

Desenvolver um método não-supervisionado para **detecção de posicionamentos** a partir de postagens coletadas no Twitter.

## Entendimento do negócio - Detecção de Posicionamentos ##

Detecção de Posiocionamento, é uma tarefa que visa determinar automaticamente a partir de um trecho de texto se o **autor é a favor, contra ou neutro** em relação a uma **proposição ou alvo**. O alvo pode ser uma pessoa, uma organização, uma política de governo, um movimento, um produto, etc.

- Autor :woman:
  - usuário do Twitter
- Alvo :dart:
  - legalização do aborto
- Tweet :bookmark_tabs:
  - grávidas são mais do que incubadoras ambulantes e tem direitos!

Podemos deduzir a partir do exemplo acima, que o autor do tweet é a favor da legalização do aborto.

## Entendimento dos dados

- Dados rotulados do SEM-EVAL 2016 para criação de baselines.
- Dados do domínio da vacinação para validar a técnica e comparar com os resultados obtidos nos estudos anteriores.

## Desafios ##

:no_entry: Falta de dados rotulados para treinar o modelo \
:no_entry: Problemas inerentes a dados de redes sociais

- Falso-positivos
- Robôs

## Contribuições esperadas / o que está encaminhado ##

:heavy_check_mark: Método não-supervisionado para detecçao de poscionamentos: MLP\
:heavy_check_mark: Método semi-supervisionado para rotulagem de dados: Tranformers - UMAP - HDBSCAN\
:heavy_check_mark: Métrica para avaliar a qualidade da rotulagem: Função de custo que minimiza o atributo ```probabilities_``` do HSBSCAN

[^note]:
  ```probabilities_```: A força com que cada amostra de texto é atrbuída a um determinado cluster.

## Técnoligias empregadas ##

The following tools were used in this project:

- [MPNET](https://huggingface.co/docs/transformers/model_doc/mpnet)
- [Python](https://python.org.br/)
- [Tranformers](https://huggingface.co/docs/transformers/main/en/index)
- [UMAP](https://umap-learn.readthedocs.io/en/latest/)
- [HDBSCAN](https://hdbscan.readthedocs.io/en/latest/how_hdbscan_works.html)
- [MLFlow](https://www.mlflow.org/)

## Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## Starting ##

```bash
# Clone this project
$ git clone https://github.com/{{YOUR_GITHUB_USERNAME}}/dissertacao

# Access
$ cd dissertacao

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

Made with :heart: by <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">{{YOUR_NAME}}</a>

&#xa0;

<a href="#top">Back to top</a>
