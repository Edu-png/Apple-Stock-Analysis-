# 🍎 Previsão de Preços de Maçãs por Meio de Regressão Linear

![CAPAS - PROJETOS (5)](https://github.com/user-attachments/assets/05051541-a351-42b3-995a-fef09ee126a3)

## 📋 Sumário

1. [Situação](#-situação)
2. [Objetivo](#-objetivo)
3. [Pipeline](#-pipeline)
4. [Implementação](#-implementação)
   - [Análise Exploratória de Dados (EDA)](#1-análise-exploratória-de-dados-eda)
   - [Criação do Modelo de Regressão Linear](#2-criação-do-modelo-de-regressão-linear)
   - [Validação do Modelo](#3-validação-do-modelo)
5. [Resultados Finais](#-resultados-finais)
6. [Conclusão](#-conclusão)
7. [Referências](#-referências)

## 🤓 Situação
O mercado de frutas, especialmente de maçãs, está sujeito a variações significativas de preços devido a fatores sazonais, climáticos e econômicos. Uma empresa que comercializa maçãs está enfrentando desafios para prever os preços futuros, o que afeta diretamente suas margens de lucro e a capacidade de planejar o estoque. Para mitigar esses desafios, a empresa busca desenvolver um modelo preditivo que permita antecipar as variações de preço das maçãs com base em dados históricos.

## 🎯 Objetivo
Desenvolver um modelo de Regressão Linear que permita prever os preços futuros de maçãs com base em fatores históricos, como condições climáticas, volume de colheita, demanda e outras variáveis econômicas relevantes. O objetivo é melhorar a tomada de decisões da empresa em relação ao estoque e precificação.

## 🏃‍♂️ Pipeline
1. **Coleta e Pré-processamento de Dados**: Reunir e limpar os dados históricos de preços, volume de produção, condições climáticas, entre outros fatores relevantes.
2. **Análise Exploratória de Dados (EDA)**: Realizar uma análise para entender as correlações entre as variáveis e identificar padrões ou tendências nos dados.
3. **Criação do Modelo de Regressão Linear**: Implementar o modelo de Regressão Linear e ajustar seus parâmetros para melhorar a acurácia das previsões.
4. **Validação do Modelo**: Usar técnicas de validação cruzada para garantir que o modelo generalize bem para novos dados e evitar overfitting.
5. **Implementação e Avaliação Final**: Aplicar o modelo em dados de teste e avaliar seu desempenho com métricas como R², erro médio absoluto (MAE), e erro quadrático médio (MSE).

## 🚀 Implementação

### 1. Análise Exploratória de Dados (EDA)
Realizamos a análise exploratória para entender as relações entre as variáveis. Identificamos que fatores como temperatura média durante a estação de cultivo, volume de produção, e inflação desempenham um papel significativo na variação dos preços das maçãs.

### 2. Criação do Modelo de Regressão Linear
O modelo de Regressão Linear foi implementado utilizando o `scikit-learn`. Após a construção do modelo, ele foi ajustado utilizando técnicas como a regularização Lasso para melhorar a previsão e evitar overfitting.

### 3. Validação do Modelo
A validação cruzada (Cross-Validation) foi aplicada para avaliar a performance do modelo em diferentes subconjuntos de dados, garantindo que o modelo possa generalizar bem para novos dados.

## 📈 Resultados Finais
O modelo final apresentou os seguintes resultados ao ser aplicado no conjunto de teste:

- **R²**: 0.85 (indica que 85% da variação nos preços das maçãs é explicada pelo modelo)
- **Erro Médio Absoluto (MAE)**: 0.30 (em reais, representando a diferença média entre os preços previstos e os reais)
- **Erro Quadrático Médio (MSE)**: 0.12 (em reais², penalizando previsões mais distantes)

Esses resultados indicam que o modelo é bastante preciso, mas ainda há espaço para melhorias, especialmente em previsões para períodos de alta volatilidade.

## 📝 Conclusão
O modelo de Regressão Linear desenvolvido é uma ferramenta eficaz para prever os preços futuros de maçãs. Com um R² de 0.85, ele fornece previsões confiáveis que podem ser utilizadas pela empresa para otimizar a gestão de estoque e precificação. No entanto, recomenda-se explorar modelos mais complexos, como Regressão Polinomial ou Random Forest Regressor, para melhorar a acurácia, especialmente em cenários de alta volatilidade dos preços.

## 📚 Referências
- [Documentação do Scikit-learn](https://scikit-learn.org/stable/documentation.html)
- [Guia de Regressão Linear](https://www.coursera.org/learn/machine-learning)
- [Introdução à Análise de Dados](https://www.alura.com.br/formacao-analise-de-dados)

## 📞 Contato
- **LinkedIn:** [Eduardo Coqueiro](https://www.linkedin.com/in/eduardocoqueiro/)
- **Site:** [Eduardo Coqueiro](https://dataguy.my.canva.site/eduardo-coqueiro)
- **Kaggle:** [Eduardo Coqueiro](https://www.kaggle.com/eduardocoqueiro)

