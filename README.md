# pcs5029_trabalho_final
Código fonte do trabalho final da disciplina PCS5029 - Processamento de linguagem natural com redes neurais artificiais

## 1. Descrição
Este código-fonte executa a classificação de textos do conjunto de dados IBM Debater - Evidences Sentences (disponível em: <https://www.research.ibm.com/haifa/dept/vst/debating_data.shtml>). Há uma exploração básica dos dados (sentenças e suas classes), seguida de um preprocessamento. Alguns gráficos obtidos da análise exploratória são salvos em uma pasta 'images', a qual deve ser criada no diretório do código. Depois, o treinamento de 2 classificadores de redes neurais e a avaliação dos resultados.

## 2. Modelos usados
O trabalho foi desenvolvido para o estudo do processamento de linguagem natural com o uso de redes neurais artificiais. Neste estudo, realizei a comparação entre uma rede LSTM bidirecional e uma BERT na tarefa de classificar tópicos de sentenças.

## 3. Execução do código
Para rodar o código, basta ter as bibliotecas do Python instaladas, realizar o download do conjunto de dados no link fornecido e descompactá-lo na mesma pasta do notebook, e criar uma pasta 'images' no diretório do código-fonte. Caso esteja em outra pasta, o caminho deve ser ajustado na seção 2 (LOAD DATA).
Com os arquivos e os caminhos corretamente instalados e configurados, basta rodar o código e observar os resultados.
Os modelos treinados são salvos com os nomes "model_lstm_bidirectional" e "model_bert".
