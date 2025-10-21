# LSTM-projeto
Rede neural LSTM treinada para análise de sentimentos em reviews de filmes, utilizando processamento de linguagem natural (NLP).
Este projeto utiliza Processamento de Linguagem Natural (PLN) e redes neurais recorrentes (LSTM) para analisar reviews de filmes, classificando-os como positivos ou negativos.

Descrição

O modelo foi treinado a partir de textos previamente rotulados, passando por etapas de tokenização e padding das sequências. A arquitetura foi otimizada com callbacks do Keras, incluindo ajuste dinâmico da taxa de aprendizado (Learning Rate), para melhorar a convergência e estabilidade do treinamento.

Tecnologias Principais

Python

TensorFlow / Keras

Processamento de Linguagem Natural (tokenização e pad_sequences)

Redes Neurais LSTM

Callbacks (EarlyStopping, ReduceLROnPlateau)
