# Image_Classification_Artificial_Neural_Network

## Classificando imagens com redes neurais artificiais

### Objetivo

O objetivo deste projeto é fazer uma classificação de 2 tipos de imagens, sendo elas: Bart e Homer. Para isso, foi utilizado uma rede neural artificial, que é um modelo de aprendizado de máquina inspirado na estrutura neural do cérebro humano. Nesse modelo, cada neurônio é uma unidade de processamento que recebe um sinal e dispara um sinal de saída. A rede neural artificial é composta por camadas de neurônios, sendo a primeira camada a camada de entrada, a última camada a camada de saída e as camadas intermediárias são chamadas de camadas ocultas. A rede neural artificial é um modelo de aprendizado supervisionado, ou seja, é necessário que os dados de entrada e saída sejam fornecidos para que o modelo possa aprender. A rede neural artificial é um modelo de aprendizado profundo, pois possui mais de uma camada oculta.

### Dataset

O dataset utilizado neste projeto foi obtido no Kaggle, através do link: https://www.kaggle.com/datasets/juniorbueno/neural-networks-homer-and-bart-classification. O dataset contém 169 imagens do bart e 124 imagens do homer, totalizando 293 imagens. As imagens estão no formato .bmp com diferentes tamanhos.

### Pré-processamento

Para o pré-processamento das imagens, foi feito o redimensionamento das imagens para o tamanho 128x128, a conversão das imagens para escala de cinza e a normalização dos pixels das imagens para o intervalo [0,1]. Foi separados em 2 vetores as imagens e suas respectivas classes, sendo 0 para homer e 1 para bart. Foi feito o embaralhamento dos dados e a divisão dos dados em treino e teste, sendo 75% dos dados para treino e 25% para teste.

### Rede Neural Artificial

A rede neural artificial utilizada neste projeto foi uma rede neural artificial do tipo perceptron de múltiplas camadas (MLP). A MLP é uma rede neural artificial com uma ou mais camadas ocultas. A MLP é um modelo de aprendizado supervisionado, ou seja, é necessário que os dados de entrada e saída sejam fornecidos para que o modelo possa aprender. A MLP é um modelo de aprendizado não linear, pois possui uma função de ativação não linear. A MLP é um modelo de aprendizado de máquina, pois é capaz de aprender a partir dos dados fornecidos. A MLP é um modelo de aprendizado de máquina do tipo classificação binária com 2 classes, sendo elas: 0 e 1, pois é capaz de classificar os dados de entrada em 2 classes, sendo elas: 0 para homer e 1 para bart.

### Treinamento

Para o treinamento da MLP, foi utilizado o algoritmo de otimização Adam, que é um algoritmo de otimização estocástica baseado em gradiente descendente. O algoritmo de otimização Adam é um algoritmo de otimização de primeira ordem, pois utiliza apenas a primeira derivada da função de custo.

### Resultados

A fazer...