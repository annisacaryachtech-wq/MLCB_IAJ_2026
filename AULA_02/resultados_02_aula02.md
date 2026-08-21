--- Distribuição de Probabilidades por Classe ---
Classe [duvida_frete]: 27.99%
Classe [rastrear_pedido]: 24.54%
Classe [troca_devolucao]: 47.46%


Avaliação dos resultados: O modelo previu corretamente troca_devolucaoa mensagem de teste, com a maior probabilidade (47,46%), confirmando sua precisão para essa entrada específica.

Aprimoramento do Algoritmo: A melhoria mais crítica seria aumentar e diversificar significativamente os dados de treinamento . Além disso, aprimorar o pré-processamento de texto (como stemming/lematização, remoção de stopwords, n-gramas) e explorar o ajuste de hiperparâmetros também seriam úteis.

Função Naive Bayes: O algoritmo Naive Bayes atua como um classificador probabilístico . Ele utiliza a frequência de palavras nas mensagens para calcular a probabilidade de uma mensagem pertencer a cada classe de intenção predefinida, atribuindo, em última instância, a mensagem à classe com a maior probabilidade, com base na suposição de que as ocorrências de palavras são independentes, dada a classe.
