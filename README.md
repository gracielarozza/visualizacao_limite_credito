# Visualização de Dados de Limite de Crédito

## Objetivo

O objetivo deste projeto é analisar dados relacionados ao **limite de crédito** de indivíduos, criando três gráficos interativos com o Plotly Express. A análise foca em identificar os principais fatores que influenciam os limites de crédito mais altos, ajudando a entender padrões e relações entre as variáveis.

## Dicionário de Variáveis

Como esse projeto tem foco didático, a base possui apenas 8 entradas e contém as seguintes variáveis:

- **Nome**: O nome completo de cada indivíduo da base de dados.
- **Idade**: A idade de cada indivíduo.
- **Profissão**: A ocupação ou profissão atual do indivíduo.
- **Salário**: O salário registrado do indivíduo.
- **Limite de Crédito**: O limite de crédito disponível para cada indivíduo.
- **Histórico de Inadimplência**: 
  - **0**: Nunca teve histórico de inadimplência.
  - **1**: Já teve histórico de inadimplência em algum momento.
- **Estado Civil**: O estado civil do indivíduo (por exemplo, solteiro, casado, divorciado).
- **Imóvel Próprio**:
  - **0**: Não possui imóvel próprio.
  - **1**: Possui imóvel próprio.

## Bibliotecas Utilizadas

- `pandas`
- `plotly.express`
- `matplotlib`
- `seaborn`

## Tratamento de Dados

Foram observados possíveis outliers no limite de crédito. Mas, por se tratar de uma base de estudo com apenas 8 entradas, não foi realizada alteração na variável. Além disso, foram realizadas transformações para facilitar a análise e visualização.

## Conclusões

Com base nas análises realizadas, é possível concluir que:

* O histórico de inadimplência é o principal fator determinante no limite de crédito. Pessoas sem histórico de inadimplência tendem a ter limites de crédito mais altos.

* O estado civil também influencia, com solteiros apresentando limites mais baixos, o que pode estar relacionado a um maior risco percebido ou uma maior incerteza financeira associada a esse grupo.

* As profissões que indicam maior estabilidade financeira, como a de médico, estão associadas a limites de crédito mais altos.

* Salários muito baixos estão diretamente relacionados a limites de crédito mais baixos, mas o histórico de inadimplência e o estado civil também desempenhem papéis importantes.

Sugere-se que essas análises sejam realizadas com um grupo maior de indivíduos, para verificar se os padrões observados se mantêm, além de aplicar análises estatísticas mais complexas que validem essas conclusões.

## Arquivos

- `visualizacao_limite_credito.ipynb` - Notebook principal do projeto, que contém a análise exploratória e visualizações.

## Observações

Este projeto foi desenvolvido com foco didático e tem como principal objetivo a prática de técnicas de visualização. Por isso, decisões de tratamento e análise foram feitas de forma simples, priorizando o aprendizado.

## Autoria

**Graciela Rozza** - Projeto desenvolvido como parte dos estudos em **Ciência de Dados**, com foco em **visualização e exploração de dados com Python**.

## Licença

MIT