### **Análise de Objetos Próximos à Terra (NEOs) da NASA**

Este repositório contém uma análise exploratória de um conjunto de dados da NASA sobre Objetos Próximos à Terra (NEOs), com o objetivo de prever a perigosidade de asteroides. O conjunto de dados original foi obtido de:

- [https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)

contém mais de 338.199 registros abrangendo observações de 1910 a 2024.

**Objetivo:**

- **Análise Exploratória:** Compreender a distribuição das características dos NEOs e identificar padrões relevantes.

**Análise Exploratória:**

- **Limpeza e Preparação dos Dados:**
    - Verificação de tipos de dados e tratamento de valores nulos.
- **Análise Univariada:**
    - **Magnitude Absoluta:** Análise da distribuição da magnitude absoluta dos asteroides, que está relacionada ao seu brilho e tamanho.
    - **Diâmetro Máximo:** Análise da distribuição do diâmetro máximo dos asteroides, comparando asteroides perigosos e não perigosos.
    - **Velocidade Relativa:** Análise da distribuição da velocidade relativa dos asteroides em relação à Terra.
    - **Distância Mínima de Aproximação:** Análise da distribuição da distância mínima de aproximação dos asteroides à Terra.
- **Análise Bivariada:**
    - **Correlação:** Cálculo da matriz de correlação para identificar relações lineares entre as variáveis.
    - **Gráficos de Dispersão:** Visualização das relações entre pares de variáveis, como diâmetro máximo e distância mínima.

**Tecnologias Utilizadas:**

- **Python:** Linguagem de programação principal.
- **Pandas:** Manipulação e análise de dados.
- **NumPy:** Operações numéricas.
- **Matplotlib e Seaborn:** Visualização de dados.
