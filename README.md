# Visualização - Limite de Crédito

Este projeto é um exercício do curso **Profissão Cientista de Dados** da Escola Britânica de Artes Criativas e Tecnologia (EBAC). No módulo 12, a tarefa era realizar uma análise com 3 gráficos para identificar quais fatores são os principais impulsionadores do limite de crédito.

## Objetivo

O objetivo deste projeto é praticar a criação de gráficos interativos a partir de um DataFrame fornecido.

## Etapas

### Exploração e Tratamento dos Dados
  - Verificação da estrutura e estatística básica do DataFrame
  - Conversão de variáveis
  - Análise da correlação entre variáveis

### Visualização dos Dados
  - **Boxplot:** relação entre `Histórico de Inadimplência` e `Limite de Crédito`.
  - **Gráfico de barras:** `Limite de Crédito` por `Profissão`.
  - **Gráfico de dispersão:** relação entre `Salário`, `Estado Civil` e `Limite de Crédito`.

## Requisitos

- **Ambiente:** Jupyter Notebook ou Google Colab.
- **Python:** Versão 3.x ou superior.  
- **Bibliotecas necessárias:**
  - **Pandas**: Para manipulação e limpeza dos dados.  
  - **Matplotlib** e **Seaborn**: Para criação de gráficos. 
  - **Plotly Express**: Para criação de gráficos interativos.
  - **Scikit-learn**: Para codificação de variáveis categóricas, utilizando o `LabelEncoder`.

```python  
import pandas as pd
import plotly.express as px
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import LabelEncoder
```

## Conclusões

Com base nas análises realizadas, é possível concluir que:

* O histórico de inadimplência é o principal fator determinante no limite de crédito. Pessoas sem histórico de inadimplência tendem a ter limites de crédito mais altos.

* O estado civil também influencia, com solteiros apresentando limites mais baixos, o que pode estar relacionado a um maior risco percebido ou uma maior incerteza financeira associada a esse grupo.

* As profissões que indicam maior estabilidade financeira, como a de médico, estão associadas a limites de crédito mais altos.

* Salários muito baixos estão diretamente relacionados a limites de crédito mais baixos, mas o histórico de inadimplência e o estado civil também desempenhem papéis importantes.

Sugere-se que essas análises sejam realizadas com um grupo maior de indivíduos, para verificar se os padrões observados se mantêm, além de aplicar análises estatísticas mais complexas que validem essas conclusões.

## Licença

MIT