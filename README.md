# Zuber — análise do mercado de táxis em Chicago

Projeto de análise exploratória sobre corridas de táxi em Chicago, combinando comparação de empresas, análise geográfica de destinos e teste de hipótese sobre condições climáticas.

## Objetivo

Entender a concentração do mercado, identificar os principais bairros de destino e verificar se a duração média das viagens entre Loop e O'Hare difere conforme as condições climáticas aos sábados.

## Ferramentas

- Python
- pandas
- scipy
- Jupyter Notebook

## Principais análises

- validação dos conjuntos de dados;
- ranking das empresas de táxi por número de corridas;
- identificação dos dez principais bairros de destino;
- visualizações comparativas;
- teste t de Welch para duração das corridas em condições climáticas distintas.

## Principais achados

- Flash Cab lidera com ampla vantagem no período analisado;
- Loop, River North, Streeterville e West Loop concentram a maior média de corridas com destino nesses bairros;
- o teste estatístico encontrou diferença significativa na duração média das viagens entre condições `Good` e `Bad` aos sábados no trajeto Loop–O'Hare.

## Dados

O notebook carrega os conjuntos de dados diretamente de URLs públicas usadas no estudo de caso. Os outputs foram mantidos para facilitar a visualização da análise no GitHub.
