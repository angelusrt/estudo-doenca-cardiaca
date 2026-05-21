# Estudo sobre doenças cardíacas

Esse repositório se refere a uma análise exploratória da seguinte base de dados.

[> Estudo Usado](https://archive.ics.uci.edu/dataset/45/heart+disease)

## Sobre o estudo

O estudo se refere a uma prediçâo sobre doenças cardíacas com base em 4 datasets diferentes (Cleveland, Hungary, Switzerland, VA Long Beach - Cleveland é o mais promissor), contendo 76 atributos (14 usaveis)

O modelo deve prever um número de 0 a 4, usando como base: idade, Sexo,  Dor no Peito, Pressão sanguinea, taxa de colesterol, etc.

O estudo compara a performance entre 5 modelos:
- XGBoost
- Support Vector
- Random Forest
- NN
- Regressão Logística

### Atributos usados

| Variável | Tipo       | Descrição                                                             | Unidade |
| -------- | ---------- | --------------------------------------------------------------------- | ------- |
| age      | Numérico   | Idade                                                                 | anos    |
| sex      | Categórico | Sexo                                                                  |         |
| cp       | Categórico | Tipo de dor no peito                                                  |         |
| trestbps | Numérico   | Pressão arterial em repouso (na admissão hospitalar)                  | mm Hg   |
| chol     | Numérico   | Colesterol sérico                                                     | mg/dl   |
| fbs      | Categórico | Glicemia em jejum > 120 mg/dl                                         |         |
| restecg  | Categórico | Resultado do eletrocardiograma em repouso                             |         |
| thalach  | Numérico   | Frequência cardíaca máxima atingida                                   |         |
| exang    | Categórico | Angina induzida por exercício                                         |         |
| oldpeak  | Numérico   | Depressão do segmento ST induzida por exercício em relação ao repouso |         |

### Contexto

Doenças cardiovasculares se tornaram a principal fonte de 
mortalidade do século passado e isso impulsionou que a medicina 
se tornasse preditiva, gerenciando risco.

Em 1948, surgiu o estudo de coração de Framingham - com o uso de estatistica.

E então se percebeu correlação com:
- Fumo
- Hipertensão
- Colesterol alto
- Risco por obesidade
- Diabetes
- Falta de exercício físico

## Nosso objetivo

Fazer uma análise exploratória do estudo para conduzir um algoritmo ML 
e enteder melhor o _storytelling_ que conta o dado.

Esse estudo universitário deve conter:
- Descrição do problema
- Lista de Stakeholders
- Descobertas anteriores relacionadas ao dataset
- Dicionário de dados
- Descrição dos atributos utilizados
- Pré-processamento do dado (redução, limpeza, transformação) e relatório
- Elaborar gráficos (histograma, dispersão e boxplot) de um atributo do projeto
- Uso de ML: Árvore de decisão e K-means
- Contar um bom story-tellings com o dado

## Setup

```bash
git clone https://github.com/angelusrt/estudo-doenca-cardiaca.git
cd estudo-doenca-cardiaca

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
```
