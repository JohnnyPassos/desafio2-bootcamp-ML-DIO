# Desafio 2 - Processamento de Imagens (Bootcamp Machine Learning - DIO)

## Visão Geral do Projeto

Este projeto foi desenvolvido como parte do Desafio 2 do Bootcamp de Machine Learning oferecido pela DIO pela Baires Dev. O objetivo principal é implementar, do zero e sem o uso de bibliotecas de processamento de imagem (como OpenCV), funções Python para redimensionar uma imagem colorida de duas formas:

1.  **Conversão para Tons de Cinza:** Transformar a imagem colorida para uma escala de 0 a 255 tons de cinza.
2.  **Conversão para Preto e Branco (Binária):** Binarizar a imagem (transformá-la em pixels apenas pretos ou brancos) a partir de sua versão em tons de cinza, utilizando um limiar.

O foco é entender a manipulação de pixels e arrays NumPy para realizar transformações de imagem.

## Estrutura do Repositório

* `desafio_processamento_imagem.ipynb` (ou o nome que você deu ao seu notebook): O notebook Jupyter/Colab contendo todo o código Python, incluindo as funções de redimensionamento e a visualização dos resultados.
* `street.jpg`: A imagem original utilizada para o processamento neste desafio.

## Como Rodar o Projeto

Você pode executar este projeto facilmente no Google Colab, onde ele foi desenvolvido.

1.  **Acesse o Google Colab:** Vá para [Google Colab](https://colab.research.google.com/).
2.  **Abra o Notebook:**
    * No menu do Colab, selecione `File > Open notebook`.
    * Vá para a aba `GitHub`.
    * Cole o link do seu repositório (ex: `https://github.com/JohnnyPassos/desafio2-bootcamp-ML-DIO`) e pressione Enter.
    * Selecione o arquivo `desafio_processamento_imagem.ipynb` (ou o nome do seu notebook).
3.  **Execute as Células:**
    * Certifique-se de que a imagem `street.jpg` está no diretório raiz do Colab (se você a subiu arrastando para a barra lateral). O código já está configurado para procurá-la como `/street.jpg`.
    * Execute todas as células do notebook sequencialmente. Isso fará as importações, definirá as funções, carregará a imagem e exibirá os resultados.

## Resultados Esperados

Ao executar o notebook, você verá três imagens lado a lado:

1.  **Imagem Original:** A imagem `street.jpg` em sua forma colorida.
2.  **Imagem em Tons de Cinza:** A mesma imagem convertida para escala de cinza (valores de 0 a 255).
3.  **Imagem Binária:** A imagem em preto e branco, resultante da aplicação de um limiar sobre a imagem em tons de cinza.

Você pode experimentar o valor do `limiar_binario` dentro do notebook para ver como ele afeta a imagem binária.

## Autor

* **Seu Nome Completo**
    * https://github.com/JohnnyPassos/JohnnyPassos
    * https://www.linkedin.com/in/johnny-passos-1aa06359/

---
