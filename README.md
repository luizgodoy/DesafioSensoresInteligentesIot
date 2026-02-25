# Projeto: Detecção de Objetos com Inteligentes com YOLOv8

Este projeto tem como objetivo implementar um sistema de visão computacional capaz de identificar e classificar objetos em imagens digitais. Utilizando a arquitetura **YOLO (You Only Look Once)**, o sistema oferece alta performance e precisão, sendo ideal para aplicações que exigem processamento rápido de dados visuais.

## 🚀 Sobre o Projeto
O sistema utiliza o modelo **YOLOv8** (da Ultralytics), treinado na base de dados COCO, para detectar diversos objetos em tempo real. O foco principal é demonstrar a aplicabilidade da Inteligência Artificial em Sensores Inteligentes, permitindo a automação e análise de cenários através de imagens.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Framework de Deep Learning:** Ultralytics YOLOv8
* **Ambiente de Desenvolvimento:** Google Colab (utilizando aceleração por GPU T4)
* **Processamento de Imagem:** OpenCV

## 📋 Pré-requisitos
Para rodar este projeto, você precisará de:
1. Uma conta no Google.
2. Acesso ao Google Colab.
3. GPU ativada (Em *Configurações do Notebook*, selecione T4 GPU).

## ⚙️ Como Executar
1. Abra o arquivo `.ipynb` no seu Google Colab.
2. Certifique-se de que a GPU está habilitada.
3. Instale as dependências:
   ```bash
   pip install ultralytics
