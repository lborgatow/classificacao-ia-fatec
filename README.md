# :bookmark: Classificação - IA (ADS Fatec) :bookmark:

## :bulb: Referências e Requerimentos

- Obtive o dataset através do [Kaggle](https://www.kaggle.com/datasets/muratkokludataset/acoustic-extinguisher-fire-dataset);
- Utilizei a linguagem [Python](https://docs.python.org/3/) (>=3.10 e <3.11) e o [Jupyter Notebook](https://docs.jupyter.org/en/latest/);
- Utilizei o [Poetry](https://python-poetry.org/) para gerenciar o ambiente (dependências).

## :pushpin: Introdução

Essa base de dados é o resultado de experimentos conduzidos para determinar o estado de extinção de chamas de combustível usando um sistema de extinção de incêndio por ondas sonoras. O objetivo é prever se uma chama será extinta ou não com base em várias características relacionadas à configuração dos dispositivos emissores das ondas e às condições experimentais.

- O sistema inclui quatro subwoofers (alto-falante que reproduz frequências baixas) com uma potência total de 4.000 watts, colocados em um gabinete colimador (estrutura que direciona/concentra fluxos de energia);

- O sistema de ondas sonoras é alimentado por dois amplificadores e uma fonte de alimentação, com um circuito de filtro para transmitir as frequências sonoras adequadas;

- Um anemômetro mede o fluxo de ar resultante das ondas sonoras, um medidor de decibéis mede a intensidade do som e um termômetro infravermelho mede a temperatura da chama e do combustível;

- Uma câmera é usada para detectar o tempo de extinção da chama;

- Um total de 17.442 testes foram conduzidos usando essa configuração.


## ⚙️ Como executar

### 1º No terminal/cmd, deve-se clonar o repositório:
```
git clone https://github.com/lborgatow/classificacao-ia-fatec.git
```
ou baixar o projeto diretamente do [GitHub](https://github.com/lborgatow/classificacao-ia-fatec);

### 2º Configurar o Poetry para gerar o ".venv" na pasta do projeto:
```
poetry config virtualenvs.in-project true
```

### 3º Instalar as dependências usando o Poetry:
```
poetry install --no-root
```

### 4º Adicionar o ".venv" como kernel do notebook "classificacao.ipynb".

### 5º Executar o notebook "classificacao.ipynb".
