# Estudo sobre doenças cardíacas

Esse repositório se refere a uma análise exploratória da seguinte base de dados.
(> Estudo Usado)[https://archive.ics.uci.edu/dataset/45/heart+disease]

O estudo se refere a uma prediçâo sobre doenças cardíacas com base em 4 datasets diferentes (Cleveland, Hungary, Switzerland, VA Long Beach - Cleveland é o mais promissor), contendo 76 atributos (14 usaveis)

O modelo deve prever um número de 0 a 4, usando como base: idade, Sexo,  Dor no Peito, Pressão sanguinea, taxa de colesterol, etc.

O estudo compara a performance entre 5 modelos:
- XGBoost
- Support Vector
- Random Forest
- NN
- Regressão Logística

Atributos usados:

| Variável | Tipo       | Descrição                                                             | Unidade |
| -------- | ---------- | --------------------------------------------------------------------- | ------- |
| age      | Inteiro    | Idade                                                                 | anos    |
| sex      | Categórico | Sexo                                                                  |         |
| cp       | Categórico | Tipo de dor no peito                                                  |         |
| trestbps | Inteiro    | Pressão arterial em repouso (na admissão hospitalar)                  | mm Hg   |
| chol     | Inteiro    | Colesterol sérico                                                     | mg/dl   |
| fbs      | Categórico | Glicemia em jejum > 120 mg/dl                                         |         |
| restecg  | Categórico | Resultado do eletrocardiograma em repouso                             |         |
| thalach  | Inteiro    | Frequência cardíaca máxima atingida                                   |         |
| exang    | Categórico | Angina induzida por exercício                                         |         |
| oldpeak  | Inteiro    | Depressão do segmento ST induzida por exercício em relação ao repouso |         |

Nossos patrocinadores são:
- Desenvolvedores de Wearables de Saúde
- Clínicas

[TODO: descrever processo de limpeza, transformação]
[TODO: elaborar gráficos usando algumas dimensões]
[TODO: ...]