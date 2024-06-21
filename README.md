# Trabalho Final de Complexidade de Algoritmos

Alunos: Kalyl Henings e Matheus Roberto da Silva Correa


## Descrição

No presente trabalho, utilizou-se o [OSMnx](https://osmnx.readthedocs.io/en/stable/index.html) para explorar um grafo de ruas providas pelo [OpenStreetMap](https://www.openstreetmap.org/). O objetivo deste trabalho é calcular uma rota entre dois endereços utilizando o algoritmo de busca de caminho A*, utilizando a [Formula de haversine](https://en.wikipedia.org/wiki/Haversine_formula) como heurística para o algoritmo. Os endereços são traduzidos em coordenadas pelo [Nominatim](https://nominatim.org/release-docs/develop/api/Overview/), um *geocoder* para dados do OpenStreetMap provido pela biblioteca [geopy](https://geopy.readthedocs.io/en/stable/).

## Dependências

Para executar este notebook, são necessárias as bibliotecas [OSMnx](https://osmnx.readthedocs.io/en/stable/index.html), [Geopandas](https://geopandas.org/en/stable/) [Matplotlib](https://matplotlib.org/) [GeoPy](https://geopy.readthedocs.io/en/stable/) e [Scikit-Learn](https://scikit-learn.org/stable/). Todas essas dependências são instaladas automaticamente ao executar o notebook do jupyter.

## Uso

Para utlilizar, 