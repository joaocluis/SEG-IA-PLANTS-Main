# Classificador de Plantas Domésticas

Esse proejeto foi desenvolvido pelo ramo IEEE UFBA,no capítulo computer society. O projeto se baseia na construção de uma rede neural convolucional (CNN) para classificação e segmentação de imagens.
O classificador conta ainda com uma interface interativa utilizando o Tkinter.

## Sobre o projeto e a base de dados
A base de dados utilizada no projeto foi extraíxa do https://www.kaggle.com/datasets/russellchan/healthy-and-wilted-houseplant-images. A base conta com imagens de plantas saudáveis e doentes. 

## Tecnologias Utilizadas

- Python
- TensorFlow/Keras
- OpenCV
- Matplotlib
- NumPy
- Tkinter (para interface gráfica)

## Treinamento do Modelo

O modelo de classificação foi treinado com a seguinte arquitetura:

- Três camadas convolucionais (Conv2D) com ReLU
- Camadas de MaxPooling2D
- Camada Flatten
- Camada densa com 128 neurônios
- Dropout para evitar overfitting
- Camada de saída softmax


## Resultados e Métricas

- Acurácia e perda do modelo são exibidas graficamente após o treinamento.

- Matriz de confusão e relatório de classificação podem ser gerados usando sklearn.metrics.
