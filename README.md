# Trabalho Final de Complexidade de Algoritmos

Alunos: Kalyl Henings e Matheus Roberto da Silva Correa

## Descrição

No presente trabalho, utilizou-se o [OSMnx](https://osmnx.readthedocs.io/en/stable/index.html) para explorar um grafo de ruas providas pelo [OpenStreetMap](https://www.openstreetmap.org/). O objetivo deste trabalho é calcular uma rota entre dois endereços utilizando o algoritmo de busca de caminho A*, utilizando a [Formula de haversine](https://en.wikipedia.org/wiki/Haversine_formula) como heurística para o algoritmo. Os endereços são traduzidos em coordenadas pelo [Nominatim](https://nominatim.org/release-docs/develop/api/Overview/), um *geocoder* para dados do OpenStreetMap provido pela biblioteca [geopy](https://geopy.readthedocs.io/en/stable/).

## Dependências

Para executar este notebook, são necessárias as bibliotecas [OSMnx](https://osmnx.readthedocs.io/en/stable/index.html), [Geopandas](https://geopandas.org/en/stable/) [Matplotlib](https://matplotlib.org/) [GeoPy](https://geopy.readthedocs.io/en/stable/) e [Scikit-Learn](https://scikit-learn.org/stable/). Todas essas dependências são instaladas automaticamente ao executar o notebook do jupyter.

## Uso

Para utlilizar, basta executar o notebook do Jupyter em sua IDE de preferência.

## Observação

Este notebook necessita de uma quantidade razoável de memório para execução, sendo 16GB o mínimo recomendável para obter figuras bonitinhas para visualização em uma cidade. É possível trocar as dimensões e DPI das figuras para execução em ambientes com menos memória. Um teste utilizando a cidade de Joinville, com figuras de dimensão (128,128) e dpi=2000, consumiu 14GB de memória. Para uma visualização de todo o estado de SC, foram necessário 40GB+ de memória. Se você tiver memória o suficiente, vá em frente e divirta-se com diferentes regiões!

As regiões já consultadas são armazendas num arquivo de cache. O cache cresce conforme uso, para evitar requisições desnecessárias.

## Algumas Imagens Bonitas de Exemplo

### 1 - Joinville, SC

![data/mapa_sc_sem_caminho](data/Joinville,%20Santa%20Catarina,%20Brasil.svg)

### 2 - Rota entre o CCT-UDESC até o Mirante de Joinville, Joinville, SC

![data/mapa_sc_sem_caminho](data/Joinville,%20Santa%20Catarina,%20Brasil%20UDESC,%20Joinville,%20Santa%20Catarina,%20Brasil%20Mirante,%20Joinville,%20Santa%20Catarina,%20Brasil%20.svg)

### 3 - Santa Catarina, Brasil

![data/mapa_sc_sem_caminho](data/mapa_sc_sem_caminho.png)
