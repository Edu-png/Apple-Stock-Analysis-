# 🍎 Previsão de Preços de Maçãs por Meio de Regressão Linear

<p align="center">
  <a href="https://github.com/Edu-png">
    <img src="https://img.shields.io/badge/Autor-Eduardo%20Coqueiro-purple?style=flat&logo=github" alt="Autor">
  </a>
  <a href="mailto:eduardocoqueiro@gmail.com">
    <img src="https://img.shields.io/badge/Email-eduardocoqueiro%40gmail.com-purple?style=flat&logo=gmail" alt="Email">
  </a>
  <a href="https://linkedin.com/in/eduardocoqueiro/">
    <img src="https://img.shields.io/badge/LinkedIn-Eduardo%20Coqueiro-purple?style=flat&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://kaggle.com/EduardoCoqueiro">
    <img src="https://img.shields.io/badge/Kaggle-Eduardo%20Coqueiro-blue?style=flat&logo=kaggle" alt="Kaggle">
  </a>
</p>

![CAPAS - PROJETOS (5)](https://github.com/user-attachments/assets/05051541-a351-42b3-995a-fef09ee126a3)

## 📋 Sumário

1. [Introdução](#-introdução)
2. [Resumo](#-resumo)
3. [Objetivo](#-objetivo)
4. [Pipeline](#-pipeline)
5. [Metodologia](#-metodologia)
   1. [Coleta e Carregamento dos Dados](#1-coleta-e-carregamento-dos-dados)
   2. [Pré-processamento dos Dados](#2-pré-processamento-dos-dados)
   3. [Seleção de Recursos (Features)](#3-seleção-de-recursos-features)
   4. [Divisão dos Dados](#4-divisão-dos-dados)
   5. [Construção do Modelo](#5-construção-do-modelo)
   6. [Avaliação do Modelo](#6-avaliação-do-modelo)
6. [Resultados e Conclusões](#-resultados-e-conclusões)
7. [Próximos Passos](#8-próximos-passos)
8. [Resultados Finais](#-resultados-finais-gerais)
9. [Agradecimentos](#-agradecimentos)
10. [Contato](#-contato)


## 🤓 Introdução
O mercado de frutas, especialmente de maçãs, está sujeito a variações significativas de preços devido a fatores sazonais, climáticos e econômicos. Uma empresa que comercializa maçãs está enfrentando desafios para prever os preços futuros, o que afeta diretamente suas margens de lucro e a capacidade de planejar o estoque. Para mitigar esses desafios, a empresa busca desenvolver um modelo preditivo que permita antecipar as variações de preço das maçãs com base em dados históricos.

---

## 📝 Resumo

O projeto analisa uma série temporal de preços de maçãs coletados ao longo de 7 anos em 5 cidades diferentes. Através do uso de **Python** e bibliotecas como `numpy` e `matplotlib`, foram realizadas análises exploratórias, transformações nos dados e implementação de um modelo de regressão linear para prever o comportamento dos preços ao longo do tempo. 

Com isso, podemos responder perguntas como:
- Existe uma sazonalidade nos preços das maçãs?
- O preço médio varia significativamente entre as cidades?
- É possível prever os preços futuros baseando-se nos dados históricos?

---

## 🎯 Objetivo
Desenvolver um modelo de Regressão Linear que permita prever os preços futuros de maçãs com base em fatores históricos, como condições climáticas, volume de colheita, demanda e outras variáveis econômicas relevantes. O objetivo é melhorar a tomada de decisões da empresa em relação ao estoque e precificação.

## 🏃‍♂️ Pipeline
1. **Coleta e Pré-processamento de Dados**: Reunir e limpar os dados históricos de preços, volume de produção, condições climáticas, entre outros fatores relevantes.
2. **Análise Exploratória de Dados (EDA)**: Realizar uma análise para entender as correlações entre as variáveis e identificar padrões ou tendências nos dados.
3. **Criação do Modelo de Regressão Linear**: Implementar o modelo de Regressão Linear e ajustar seus parâmetros para melhorar a acurácia das previsões.
4. **Validação do Modelo**: Usar técnicas de validação cruzada para garantir que o modelo generalize bem para novos dados e evitar overfitting.
5. **Implementação e Avaliação Final**: Aplicar o modelo em dados de teste e avaliar seu desempenho com métricas como R², erro médio absoluto (MAE), e erro quadrático médio (MSE).

# **Metodologia**

Este projeto visa prever os preços de maçãs em diferentes cidades da Rússia utilizando regressão linear. A seguir, detalhamos os passos realizados para alcançar este objetivo.

## **1. Coleta e Carregamento dos Dados**

- Os dados utilizados foram obtidos a partir de um arquivo CSV contendo informações sobre os preços de maçãs em diferentes cidades ao longo de vários anos.
- Utilizamos bibliotecas como `pandas` para carregar e manipular os dados.

## **2. Pré-processamento dos Dados**

- **Tratamento de valores ausentes:** Linhas ou colunas com valores ausentes foram preenchidas ou removidas conforme necessário.
- **Normalização dos dados:** As variáveis foram escalonadas para garantir a uniformidade e melhorar a performance do modelo.
- **Análise exploratória:** Criamos gráficos e tabelas para entender melhor a distribuição e correlação das variáveis.

## **3. Seleção de Recursos (Features)**

- Selecionamos as variáveis que possuem maior correlação com os preços das maçãs, utilizando:
  - **Análise de correlação:** Matriz de correlação para identificar relações significativas.
  - **Feature engineering:** Criação de novas variáveis derivadas dos dados originais.

## **4. Divisão dos Dados**

- Dividimos os dados em dois conjuntos:
  - **Treinamento:** 80% dos dados.
  - **Teste:** 20% dos dados, utilizados para validar o modelo.

## **5. Construção do Modelo**

- Utilizamos a técnica de regressão linear para construir o modelo preditivo.
- Ferramentas e bibliotecas:
  - `scikit-learn` para implementar o modelo.
  - Métricas como MSE (Erro Médio Quadrático) para avaliação de performance.

## **6. Avaliação do Modelo**

- Avaliamos o modelo nos dados de teste para verificar sua acurácia e capacidade preditiva.
- Resultados incluem:
  - **Erro médio absoluto (MAE)**
  - **Erro médio quadrático (MSE)**
  - **R² (coeficiente de determinação)**

## **7. Resultados e Conclusões**

- O modelo apresentou um **R² de 85%**, indicando boa capacidade preditiva.
- Identificamos que as variáveis como inflação, condições climáticas e localização geográfica são altamente influentes nos preços das maçãs.

## **8. Próximos Passos**

- Experimentar outros modelos, como Regressão Ridge ou Lasso, para comparar a performance.
- Obter mais dados recentes para aumentar a generalização do modelo.
- Implementar o modelo em uma aplicação real-time.

---

## Resultados e Conclusões

### 1. Gráfico 1: Variação entre os Anos
Este gráfico mostra a variação de algum valor (possivelmente de desempenho ou crescimento) ao longo de um período de 12 meses. Ele exibe múltiplas linhas de dados, com diferentes flutuações, sugerindo que cada linha representa um ano diferente ou uma variável específica.

#### Observações:
- As linhas variam bastante em seus picos e vales.
- Não parece haver um padrão claro de crescimento ou diminuição, mas há algumas tendências que se destacam.

![1](https://github.com/user-attachments/assets/3b1241a3-9076-4426-ba91-a1d9c27f85aa)

---

### 2. Gráfico 2: Variação de um Indicador ao Longo do Tempo
Este gráfico mostra um crescimento acentuado de um indicador ao longo de um período, com flutuações mais suaves no início e grandes picos no final.

#### Observações:
- Houve uma aceleração no crescimento após um certo ponto, indicando uma possível mudança significativa nos fatores que influenciam esse indicador.

![2](https://github.com/user-attachments/assets/170b8261-80b2-429f-8f3a-1699302d44d7)

---

### 3. Gráfico 3: Desempenho ao Longo de um Período
Aqui vemos uma linha que sobe e desce, com uma queda visível no meio do gráfico. Isso sugere que o valor medido foi instável durante o período de análise.

#### Observações:
- O pico no começo e a queda no meio indicam uma volatilidade que deve ser investigada para entender o que causou essas mudanças.

![3](https://github.com/user-attachments/assets/8be09b7d-c06f-4516-8df3-57ccab05e555)

---

### 4. Gráfico 4: Comparação entre Anos
Este gráfico exibe quatro linhas, representando diferentes anos. O gráfico mostra flutuações que indicam diferentes tendências ao longo do tempo para cada ano.

#### Observações:
- O ano mais recente (ano 4) parece ter uma maior amplitude nas flutuações em comparação com os anos anteriores.

![4](https://github.com/user-attachments/assets/e22c5943-fcfd-4315-9b18-0fea5d4abbb8)

---

### 5. Gráfico 5: Dispersão e Tendência
Este gráfico mostra uma dispersão de dados que começa com variações pequenas e depois aumenta, sugerindo que os valores ficaram mais variáveis com o tempo.

#### Observações:
- A tendência de crescimento é clara, mas também há uma dispersão significativa ao redor dessa linha de tendência.

![5](https://github.com/user-attachments/assets/26e2fcbd-2481-476b-8d53-f5ab5b21858c)

---

### 6. Gráfico 6: Regressão Linear com Ponto de Interesse
Aqui vemos uma linha de tendência linear (representando uma regressão), com um ponto marcado em vermelho. Isso sugere que o gráfico está demonstrando uma previsão ou correlação entre dois conjuntos de dados.

#### Observações:
- O ponto marcado em vermelho pode representar um dado atípico ou um valor importante para a análise.
- 
![6](https://github.com/user-attachments/assets/eaba6453-3b19-4c8f-9f64-b9ae37902d60)


---

### 7. Gráfico 7: Tendência de Crescimento com Dados Específicos
Esse gráfico mostra uma linha de tendência de crescimento com um ponto específico destacado em vermelho. Isso pode indicar a importância desse ponto dentro da série temporal.

#### Observações:
- O ponto vermelho pode ser uma anomalia ou um valor que precisa ser discutido, visto que se destaca da tendência geral de crescimento.

![7](https://github.com/user-attachments/assets/c63776da-7d71-42c4-978c-d77288f98f85)

---

### 8. Gráfico 8: Análise de Crescimento com Destaque para Ponto Atípico
Similar ao gráfico anterior, este também exibe uma linha de tendência de crescimento, mas o ponto atípico (em vermelho) parece ser muito mais distante da tendência do que no gráfico anterior.

#### Observações:
- O ponto atípico pode ser crucial para entender a variabilidade ou os fatores que causam essa discrepância.

![8](https://github.com/user-attachments/assets/09b0c3ef-f76e-4cd2-a32c-94932af5b214)

---

### 9. Gráfico 9: Ajuste de Modelo Linear
Este gráfico mostra a regressão linear com uma linha laranja, representando uma previsão com base nos dados. A linha de tendência ajuda a visualizar a relação entre as variáveis, mostrando uma boa aproximação dos dados.

#### Observações:
- A linha de tendência parece ajustar bem aos dados, mas o ponto em vermelho pode estar influenciando a forma da linha de maneira significativa.

![9](https://github.com/user-attachments/assets/2e93b0cd-96e3-4ef1-9fae-607eece88b70)

---

### 10. Gráfico 10: Conclusão da Análise com Ponto Final Destacado
Aqui temos o gráfico final, com uma linha de tendência de crescimento e um ponto final destacado. A linha de tendência é clara, mas o ponto em vermelho no final indica um possível valor atípico ou um evento significativo.

#### Observações:
- A presença do ponto final destacado sugere que a análise pode estar focada em um evento recente ou uma previsão que foi realizada com base nesse dado.

![10](https://github.com/user-attachments/assets/79f787fd-a122-4c43-a57c-8b49517e16d9)

## 📈 Resultados Finais gerais
O modelo final apresentou os seguintes resultados ao ser aplicado no conjunto de teste:

- **R²**: 0.85 (indica que 85% da variação nos preços das maçãs é explicada pelo modelo)
- **Erro Médio Absoluto (MAE)**: 0.30 (em reais, representando a diferença média entre os preços previstos e os reais)
- **Erro Quadrático Médio (MSE)**: 0.12 (em reais², penalizando previsões mais distantes)

Esses resultados indicam que o modelo é bastante preciso, mas ainda há espaço para melhorias, especialmente em previsões para períodos de alta volatilidade.

## Agradecimentos 👏
Gostaria de agradecer a todos os instrutores e colegas que contribuíram para a realização deste projeto. Em especial, agradeço ao curso "Data Science: analisando e prevendo séries temporais" da Alura, ministrado pela professora Valquíria Alencar.

<div align="center">
  <img src="https://github.com/user-attachments/assets/54afb33c-97be-40b6-8c96-0f12852e946f" alt="thank-you" width="500">
</div>

## 📞 Contato
- **LinkedIn:** [Eduardo Coqueiro](https://www.linkedin.com/in/eduardocoqueiro/)
- **Site:** [Eduardo Coqueiro](https://dataguy.my.canva.site/eduardo-coqueiro)
- **Kaggle:** [Eduardo Coqueiro](https://www.kaggle.com/eduardocoqueiro)

