# Projeto de Classificação de Leads

## Descrição
Este projeto consiste em um modelo de machine learning desenvolvido para prever a conversão de leads em clientes com base em dados históricos. Utilizamos técnicas de regressão logística para modelar a probabilidade de conversão e aplicamos métodos de seleção de características para otimizar o modelo, garantindo eficiência e eficácia.

## Ferramentas Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**: Utilizada para implementar regressão logística e RFE (Recursive Feature Elimination).
- **Matplotlib** e **Seaborn**: Bibliotecas para visualização de dados.

## Estrutura do Projeto
1. **Preparação de Dados**: Carregamento dos dados e realização da limpeza inicial, tratando valores ausentes e removendo características irrelevantes.
2. **Análise Exploratória de Dados**: Visualizações e estatísticas para entender melhor os dados.
3. **Pré-processamento de Dados**: Normalização dos dados e conversão de variáveis categóricas em formatos adequados para modelagem.
4. **Modelagem**: Implementação da regressão logística com uma seleção de características usando RFE para identificar os atributos mais significativos.
5. **Avaliação de Modelo**: Uso de métricas como a matriz de confusão, AUC-ROC, precisão, recall e F1-score para avaliar o desempenho do modelo.
