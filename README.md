### Classificacao-Binaria-AMNZN


### Outline

* Introdução
* Metodologia
  * Descrição dos procedimentos
*Aplicação
  * Análise Descritiva e Limpeza
  * Treinamento dos modelos 
    * glmnet
    * Random Forest
    * Random Forest com Oversampling
* Resultados e conclusões
    * Estratégia de monitoramento e deploy
    
--------------------------------------------------

Nesse notebook ajustaremos dois modelos preditivos de classificação binária.
 
Começamereos com uma elastic net e em seguida um Random Forest. Por fim, treinaremos uma Random Forest com sobreamostragem e verificaremos o impacto na performance dos modelos.
 
O modelo preditivo escolhido deverá ser capaz de classificar a cada dia a probabilidade de que a ação da empresa ***AMZN*** negociada na Nasdaq alcance nos próximos 10 dias uma valorização de no
mínimo 4% e que não desvalorize mais que 2,5%.
 
Como o objetivo do modelo é alcançar uma boa capacidade preditiva para os critérios acima, não focaremos tanto nos preditores lineares e suas propriedades estatísticas e nem em interpretabilidade. Portanto, tomaremos uma abordagem focada em ***Machine Learning***.
 
 
## Acesse o aruivo  *Analise_amnzn.ipynb* para visualizar a anaálise.
---
