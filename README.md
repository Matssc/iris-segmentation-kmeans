# Clusterização de Espécies de Flores com K-Means 🌸

Este projeto utiliza o algoritmo de aprendizado de máquina não supervisionado **K-Means** para agrupar diferentes espécies de flores Iris com base em suas características morfológicas (comprimento e largura de sépalas e pétalas).

## 🚀 Objetivo do Projeto
O desafio principal foi identificar padrões naturais nos dados e agrupar as flores em clusters sem utilizar as etiquetas de classificação pré-existentes, simulando um cenário real de descoberta de dados.

## 🛠️ Tecnologias e Ferramentas
* **Python 3.x**
* **Pandas & NumPy:** Manipulação e estruturação dos dados.
* **Scikit-Learn:** Implementação do modelo de Machine Learning (`KMeans`) e pré-processamento (`StandardScaler`).
* **Matplotlib & Seaborn:** Visualização de dados e análise de clusters.

## 📊 Etapas do Desenvolvimento
1. **Análise Exploratória (EDA):** Verificação de medidas estatísticas e tipos de dados.
2. **Pré-processamento:** Padronização das escalas para garantir que todas as variáveis tenham o mesmo peso no algoritmo.
3. **Método do Cotovelo (Elbow Method):** Execução de múltiplos testes para encontrar o número ideal de clusters ($k$).
4. **Modelagem:** Treinamento do modelo K-Means com o número de grupos otimizado.
5. **Análise de Resultados:** Criação de tabelas dinâmicas para entender o perfil de cada grupo formado.

## 📈 Principais Insights
* O algoritmo conseguiu separar claramente as espécies que possuem dimensões de pétalas menores.
* A padronização dos dados foi crucial, pois variáveis com escalas maiores estavam distorcendo a formação dos grupos inicialmente.
