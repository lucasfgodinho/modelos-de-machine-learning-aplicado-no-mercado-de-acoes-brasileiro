# Modelos de machine learning aplicados no mercado de ações brasileiro

Este trabalho explora a aplicação de algoritmos de Machine Learning na previsão de tendências de ações brasileiras, com foco no Índice Brasil 50 (IBrX 50 B3. 08-09-23). Para garantir clareza e precisão, utilizamos uma variedade de algoritmos, como Regressão Logística, Classificador de Floresta Aleatória, Máquina de Vetores de Suporte (SVM), Classificador MLP e Classificador K-Vizinhos Mais Próximos (KNN).

Durante o desenvolvimento, abordamos a coleta e preparação de dados, enfatizando a escolha de métricas relevantes baseadas na análise técnica para prever tendências. Isso envolveu médias móveis, médias ponderadas por volume, cálculos estocásticos, Índice de Força Relativa (RSI), Média Móvel Convergente e Divergente (MACD) e Bandas de Bollinger.

Para testar nosso algoritmo, será necessário instalar as bibliotecas usadas. É importante notar que os resultados podem variar um pouco devido aos diferentes períodos de observação.

Adotamos uma abordagem escalonada, variando o número de ativos e o período de observação. Observamos que o desempenho dos modelos variou consideravelmente em treinos e testes com diferentes configurações. Priorizamos a previsão da tendência futura das ações em vez de prever o valor exato de fechamento para aumentar a precisão do modelo.

Os resultados revelaram variações significativas nas acurácias dos modelos, dependendo do número de ativos e do período de observação. Por exemplo, o MLP Classifier obteve a melhor acurácia em alguns cenários, enquanto o KNN teve um desempenho inferior em outros. A escolha da métrica também influenciou o desempenho do modelo.

Em resumo, este estudo fornece insights valiosos sobre a aplicação de Machine Learning na previsão de tendências de ações brasileiras. No entanto, é fundamental considerar que o desempenho dos modelos é sensível à configuração e à métrica escolhida. Essas conclusões podem ser úteis para investidores e profissionais do mercado financeiro, oferecendo uma compreensão mais profunda das complexidades envolvidas na previsão de tendências de ações.
