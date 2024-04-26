# MVP3-PUC
## Projeto MVP - Machine Learning - Classificação
### Michele Tempos Sarai


**Acesso ao código**: 
* Uma cópia do código está disposta neste repositório (Classificacao_pipeline.ipynb)
* Ou poderá ser acessado via link:
  https://colab.research.google.com/drive/1liIOhINvP11zcjkFSglfNHS43IpWUHJm?usp=sharing


### Resumo MVP

  Este MVP proporcionou a elaboração de etapas essenciais na construção de Modelos de Machine Learning. Em resumo, pode-se dizer:


1. **Pré-processamento de Dados**:
   - Análise inicial do conjunto de dados, incluindo estatísticas descritivas e visualização das distribuições das variáveis.
   - Identificação de dados faltantes (nulos) e verificação do tipo de dados.
   - Normalização das variáveis Time e Amount usando RobustScaler para mitigar o efeito de outliers.
   
2. **Avaliação do Balanceamento das Classes**:
   - Cálculo da proporção de ocorrências de cada classe no conjunto de dados, destacando o desbalanceamento entre as classes.
   
3. **Separação em Conjuntos de Treino e Teste**:
   - Divisão do conjunto de dados em atributos (X) e rótulos (y) para posterior treinamento e teste dos modelos.

4. **Resampling e Modelagem**:
   - Utilização de técnicas de resampling (Random Under Sampler e Random Over Sampler) para balancear as classes minoritárias.
   - Aplicação de diversos modelos de classificação (Decision Tree, Logistic Regression e KNN) em conjunto com validação cruzada estratificada para avaliar o desempenho dos modelos.
   - Avaliação de métricas de desempenho, como acurácia, precisão, recall, área sob a curva ROC (ROC AUC) e precisão média (average precision).
   - Visualização dos resultados por meio de gráficos de boxplot para comparar o desempenho dos modelos com resampling.

5. **Otimização de Hiperparâmetros**:
   - Realização de uma busca em grade (Grid Search) para encontrar os melhores hiperparâmetros para o modelo selecionado (Logistic Regression) em termos de recall e precisão média.
   - Avaliação dos melhores parâmetros e do desempenho associado a eles.
