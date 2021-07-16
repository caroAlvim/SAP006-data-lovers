# Studio Ghibli - Data Lovers

Projeto criado para organizar, filtrar e selecionar dados e apresentar em uma página web de acordo com a necessidade de usuários.

Para visualizar, acesse [aqui.](https://caroalvim.github.io/SAP006-data-lovers/)


![totoro](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/totoro.gif)

## Índice

- [1. Resumo do projeto](#1-resumo-do-projeto)
- [2. Introdução](#2-introducao)
- [3. Pesquisa](#3-pesquisa)
- [4. Histórias de usuários](#3-historias-de-usuarios)
- [5. Desenvolvimento do protótipo](#5-desenvolvimento-do-prototipo)
- [6. Testes de usabilidade ](#6-testes-de-usabilidade)
- [7. Objetivos de aprendizagem](#7-objetivos-de-aprendizagem)


---
## 1. Resumo do projeto

Studio ghibli - Data Lovers é uma aplicação web desenvolvida a partir de um data set contendo informações sobre lançamentos, personagens, diretores e avaliações de cada um dos filmes. 

Neste projeto foi desenvolvido um protótipo para a interface gráfica para visualizar os dados de maneira adequada aos usuários, pesquisa de usuários e testes de usabilidade.

Estes são os dados utilizados:

* [Studio Ghibli](src/data/ghibli/ghibli.json).
  Lista de animações e personagens do [Studio Ghibli](https://ghiblicollection.com/).
  - [Pesquisa com seguidores de Studio Ghibli](src/data/ghibli/README.md)


✨ Projeto desenvolvido por [Lediane Machado](https://github.com/ledi-mach) e [Carolina Alvim.](https://github.com/caroAlvim)

## 2. Introdução

Segundo a [Forbes](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read) 90% dos dados que existem hoje foram gerados durante os últimos dois anos. A cada dia geramos 2.5 milhões de terabytes de dados, uma cifra sem precedentes.

Apesar disso, os dados por si só são de pouca utilidade. Para que essas grandes quantidades de dados se convertam em **informação** compreensível para os usuários, precisamos entender e processar estes dados. Uma forma simples de fazer isso é criando _interfaces_ e _visualizações_.


## 3. Pesquisa

Utilizando o Google Forms, realizamos uma pesquisa visando descobrir qual é a idade dos nossos usuários e quais seriam os seus interesses na aplicação web que seria desenvolvida.

Obtivemos os seguintes resultados:

![print-idade](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/idade.png)

* 40,7% dos usuários tem entre 16-21 anos e mais de 30% tem entre 22-33 anos.

![print-fa](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/relacao.png)
* 53,7% já conhecem as animações e se declaram fãs das animações.

![interesse-site](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/topicos.png)
* Parte significativa dos entrevistados afirmaram ter interesse em pesquisar filmes por diretor, ano de lançamento e por ordem alfabética dos personagens.



## 4. História dos usuários

Após a análise das respostas do formulário, identificamos três usuários:

### Hitória 1

![historia-um](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/1.png)

Definição de pronto: Local para selecionar e filtrar os filmes por avaliação. 

Critérios de aceitação: Os filmes serão exibidos na forma de flipcards, com o título e poster na frente e demais informações no verso. A ordem de exibição será dos filmes de maior para menor ratting score.

### História 2

![historia-dois](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/2.png)

Definição de pronto: Local para organizar e apresentar os personagens com filtros de espécie, gênero, ordem alfabética e filme ao qual pertencem. 

Critérios de aceitação: As informações associadas aos personagens serão exibidas na forma de flipcard com a imagem do personagem na frente e informações no verso.


### História 3

![historia-tres](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/3.png)

Definição de pronto: Seletores para selecionar os filmes por diretor e ordem crescente/decrescente de lançamento.

Critérios de aceitação: As informações selecionadas serão exibidas no verso de flipcards, podendo o usuário transitar entre tais informações e o poster do filme ao passar o mouse nas cartas.


## 5. Protótipo

![prototipo]()

A Paleta de cores escolhida baseia-se no filme "O Castelo Animado (Howl's Moving Castle)".
![paleta-ghibli](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/paleta_ghibli.png)

### Projeto final

Home
![pagina-home](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/pg-inicial.png)

Header e navegaçao
![header](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/pg-header.png)

Página de filmes
![pagina-films](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/pg-films.png)

Página de personagens
![pagina-chars](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/pg-chars.png)

Página com calculo agregado
![pagina-calc](https://github.com/caroAlvim/SAP006-data-lovers/blob/main/src/imgs/pg-chars-calc.png)


## 6. Teste de usabilidade

Os usuários que participaram dos testes de usabilidade relataram a necessidade de um campo de pesquisa nas páginas 2 e 3, principalmente devido ao grande volume de personagens. Outro ponto para melhoria foi a padronização dos cards de filmes e personagens. Assim, incluímos um campo de pesquisa ligado às funções de filtro e padronizamos todos os flipcards quanto à cores e formatação das informações.


## 7. Objetivos de aprendizagem

Neste projeto, o objetivo principal é aprender a desenhar e construir uma interface web onde se possa visualizar e manipular dados, entendendo o que o usuário necessita.

Para isso, foi utilizado:

### HTML e CSS

* [Uso de HTML semântico.](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
* Uso de seletores de CSS.
* Construir sua aplicação respeitando o desenho realizado (protótipo).
* [Uso de flexbox em CSS.](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### DOM e Web APIs

* Uso de seletores de DOM.
* Gerenciamento de eventos de DOM.
* [Manipulação dinâmica de DOM.](https://developer.mozilla.org/pt-BR/docs/DOM/Referencia_do_DOM/Introdu%C3%A7%C3%A3o) (appendChild |createElement | createTextNode| innerHTML | textContent | etc.)

### JavaScript

* Uso de condicionais (if-else | switch | operador ternário)
* Uso de laços (for | for..in | for..of | while)
* Uso de funções (parâmetros | argumentos | valor de retorno)
* Manipular arrays (filter | map | sort | reduce)
* Manipular objects (key | value)
* Uso ES modules ([`import`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import) | [`export`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export))
* Diferenciar entre expression e statements.
* Diferenciar entre tipos de dados atômicos e estruturados.

### Testing

* [Teste unitário.](https://jestjs.io/docs/pt-BR/getting-started)

### Estrutura do código e guia de estilo

* Organizar e dividir o código em módulos (Modularização)
* Uso de identificadores descritivos (Nomenclatura | Semântica)
* Uso de linter (ESLINT)

### Git e GitHub

* Uso de comandos de git (add | commit | pull | status | push)
* Gerenciar repositórios de GitHub (clone | fork | gh-pages)
* Colaboração no Github (branches | pull requests | |tags)




