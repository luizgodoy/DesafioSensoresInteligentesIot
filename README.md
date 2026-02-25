O YOLO (You Only Look Once) permite a detecção em tempo real dentro do ambiente do Google Colab.
Para este projeto, utilizamos a versão YOLOv8 (da Ultralytics), que é a mais amigável para implementação e possui excelente documentação.
Abaixo, apresento um roteiro estruturado para implementarmos isso no seu notebook.

🛠️ #Estrutura do Projeto no Colab#
Para que o projeto funcione, seguiremos estas etapas fundamentais:
Configuração do Ambiente: Instalação das bibliotecas e verificação da GPU.
Carregamento do Modelo: Download dos pesos pré-treinados (geralmente treinados na base COCO, que detecta 80 tipos de objetos comuns).
Processamento da Imagem: Upload e inferência na imagem escolhida.
Exibição dos Resultados: Plotagem da imagem com as Bounding Boxes (caixas delimitadoras).
