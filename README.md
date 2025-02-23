# Treinamento de Redes Neurais com Transfer Learning

# Classificação de Gatos e Cachorros com TensorFlow e Keras

Este repositório contém um código para classificação de imagens de gatos e cachorros utilizando uma rede neural convolucional (CNN) com TensorFlow e Keras. O código foi desenvolvido para ser executado no Google Colab.

## Descrição do Projeto

O objetivo deste projeto é treinar um modelo de rede neural para classificar imagens de gatos e cachorros. O código faz o seguinte:

1. **Download do Dataset**: O código baixa um dataset de imagens de gatos e cachorros da Microsoft.
2. **Pré-processamento dos Dados**: As imagens são divididas em conjuntos de treino e teste.
3. **Construção do Modelo**: Uma rede neural convolucional é construída usando TensorFlow e Keras.
4. **Treinamento do Modelo**: O modelo é treinado com as imagens de treino e validado com as imagens de teste.
5. **Classificação de Imagens**: Após o treinamento, o modelo pode ser usado para classificar novas imagens de gatos e cachorros.

## Como Executar o Código

1. **Abrir no Google Colab**: O código foi desenvolvido para ser executado no Google Colab. Você pode copiar e colar o código em um novo notebook no Colab.

2. **Executar o Código**: Execute todas as células do notebook. O código fará o download do dataset, treinará o modelo e permitirá que você classifique novas imagens.

3. **Testar Novamente**: Para testar o modelo novamente com uma nova imagem, basta copiar e colar a última parte do código (a partir do comentário `# Classificação de uma imagem carregada pelo usuário`) e executá-la novamente. Isso permitirá que você carregue uma nova imagem e veja a classificação feita pelo modelo.

## Estrutura do Código

- **Download e Extração do Dataset**: O código baixa o dataset de gatos e cachorros e extrai os arquivos.
- **Divisão dos Dados**: As imagens são divididas em conjuntos de treino e teste.
- **Construção do Modelo**: Uma CNN é construída com várias camadas convolucionais e densas.
- **Treinamento do Modelo**: O modelo é treinado com as imagens de treino e validado com as imagens de teste.
- **Classificação de Imagens**: O modelo é usado para classificar novas imagens carregadas pelo usuário.

## Dependências

- TensorFlow
- Keras
- NumPy
- Matplotlib

## Exemplo de Uso

Após executar o código e treinar o modelo, carregue uma imagem e verifique se o modelo acertou a classificação.
