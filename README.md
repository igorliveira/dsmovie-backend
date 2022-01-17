# ![DevSuperior logo](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/devsuperior-logo-small.png) Semana Spring
Projeto de app full-stack responsivo de avaliação de filmes, realizado em monorepo e com armazenamento em banco de dados relacional dividido em 4 episódios, onde cada episódio o professor [Nelio Alves](https://github.com/acenelio) explica passo-a-passo para realizá-lo, mas como só tenho interesse no momento no backend só goi desenvolvido o backend e realizado o deploy da API no Heroku.

## Tecnologias
O sistema utiliza Spring no back-end.

## Objetivos
O projeto tem como objetivo desenvolver uma API que retorna uma lista de filmes que estão no banco de dados, retornar um filme específico buscando pelo seu ID e também adicionar uma avaliação, sendo inserido o email e a nota designada ao filme.

### Objetivos pessoais 
O objetivo deste treinamento é aprofundar meus conhecimentos em Spring, framework do Java e o treinamento tem contribuído para agregar conhecimentos. 

## Testar a API
URL: https://dsmovie-backend.herokuapp.com/

- /movies: Ao utilizar a URL acima com o /movies em uma requisição GET, iremos chamar todos os filmes armazenados no banco de dados, mas podemos tambem manipular essa requisição inserindo na url os parametros: https://dsmovie-backend.herokuapp.com/movies?size=5&page=4 onde o size definira quantos filmes será retornado na requisição e o page o número da página onde se pensando que essa API seria consumida pra um catalogo de filmes a pagina 4 buscaria o 5 filmes que seriam mostrados na página 4.

- /movies/${id}: Ao utilizar a URL acima com o /movies/id em uma requisição GET, onde o id seria o id do filme e retornaria apenas o filme com o id correspondente (lembrando que temos 20 filmes no nosso banco de dados atualmente).

- /scores: Ao utilizar a URL acima com o /scores em uma requisição PUT, com um body como mostrado abaixo, seria inserido ao filme com id uma nova nota dessa pessoa que também seria armazenada no banco de dados.

        {
	    "movieId": 3,
	    "email": "rodrigo@gmail.com",
	    "score": 4
        }

    
#
## Realização
[DevSuperior - Escola de programação](https://devsuperior.com.br)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig)
[![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)](https://youtube.com/devsuperior)

