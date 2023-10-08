# Trainner-Process-Image-Python
Treinamento de processamento de imagem para reconhecimento de 5 obejetos usando openCV Com Keras linguagem Python

## Descrição do Projeto:
Este projeto demonstra como fazer previsões em tempo real usando um modelo de rede neural treinado anteriormente. O modelo é carregado a partir de um arquivo chamado "keras_model.h5" e é usado para classificar imagens capturadas pela webcam em tempo real.

## Instruções de Instalação:
Para executar este código, você precisará das seguintes bibliotecas Python instaladas: Keras, OpenCV (opencv-python), e NumPy.

Certifique-se de ter o arquivo "keras_model.h5" contendo seu modelo treinado e um arquivo de etiquetas (rótulos) chamado "labels.txt" no mesmo diretório que este script. O modelo deve ser treinado previamente usando uma ferramenta como o Teachable Machine.

## Instruções de Uso:

Execute o código em um ambiente Python com as bibliotecas necessárias instaladas.
Certifique-se de ter uma câmera disponível e conectada ao seu computador.
Você pode ajustar a câmera que será usada alterando o valor de "camera = cv2.VideoCapture(1)" para "camera = cv2.VideoCapture(0)" se você quiser usar a câmera padrão.
Quando o código é executado, a imagem da webcam será exibida em uma janela.
O código fará previsões sobre o que a câmera está capturando e imprimirá a classe prevista e a pontuação de confiança no terminal.
Para encerrar o programa, pressione a tecla "esc" (código ASCII 27).

## Créditos:
Este código foi desenvolvido como parte de um projeto realizado no laboratório de Sistemas de Informação da UFOPA na disciplina de processamento de imagem Ministrada pelo professor Danio Figueredo.
