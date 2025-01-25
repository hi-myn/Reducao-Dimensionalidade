# Redução de Dimensionalidade de Imagens  

Este repositório contém um projeto de **redução de dimensionalidade de imagens**, desenvolvido como parte de um desafio de projeto no bootcamp de **Machine Learning**. O objetivo é processar uma imagem original e transformá-la para uma representação mais simples, utilizando técnicas como:  

1. **Conversão para Tons de Cinza**  
2. **Binarização (Preto e Branco)**  

## 📜 Descrição  

A redução de dimensionalidade é um passo importante na manipulação e análise de imagens, especialmente em tarefas de Machine Learning e Visão Computacional, **pois diminui o tempo de processamento, assim não fazendo com que o algoritmo armazene informações 'desnecessárias'.**

Este projeto apresenta duas etapas principais:  

### 1️⃣ Conversão para Tons de Cinza  

Na primeira etapa, a imagem original é processada para remover as informações de cor (RGB) e convertida para **tons de cinza**. 

### 2️⃣ Binarização  

Após a conversão para tons de cinza, a imagem é transformada em uma imagem **binária** (preto e branco). Cada pixel é avaliado com base em um **limiar (threshold)** definido (padrão: 127).  

- **Se o valor do pixel for maior que o limiar**, ele será convertido para **branco (1)**.  
- **Caso contrário**, ele será convertido para **preto (0)**.  

## 🛠️ Ferramentas Utilizadas  

- **Python**: Linguagem de programação principal.  
- **Pillow**: Biblioteca para manipulação de imagens (processamento de pixels).  
- **Google Colab**: Ambiente de execução online para Python, usado para desenvolver e executar o projeto.  <br>

***

<br>**English version**

# Image Dimensionality Reduction  

This repository contains an **image dimensionality reduction** project, developed as part of a project challenge in the **Machine Learning** bootcamp. The aim is to process an original image and transform it into a simpler representation, using techniques such as:  

1. **Grayscale conversion**  
2. **Binarization (Black and White)**  

## 📜 Description  

Dimensionality reduction is an important step in the manipulation and analysis of images, especially in Machine Learning and Computer Vision tasks, **as it reduces processing time, thus not causing the algorithm to store 'unnecessary' information.

This project has two main stages:  

### 1️⃣ Conversion to Grayscale  

In the first stage, the original image is processed to remove the color information (RGB) and converted to **grayscale**. 

### 2️⃣ Binarization  

After conversion to grayscale, the image is transformed into a **binary** (black and white) image. Each pixel is evaluated based on a defined threshold (default: 127).  

- If the pixel value is greater than the threshold, it will be converted to white (1).  
- **Caso contrário**, ele será convertido para **preto (0)**.  

## 🛠️ Ferramentas Utilizadas  

- **Python**: Linguagem de programação principal.  
- **Pillow**: Biblioteca para manipulação de imagens (processamento de pixels).  
- **Google Colab**: Ambiente de execução online para Python, usado para desenvolver e executar o projeto.  <br>
