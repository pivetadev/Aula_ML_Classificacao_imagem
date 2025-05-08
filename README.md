# Projeto de Classificação de Imagens por Raça

👩🏾‍💻 Autora: Nicole Pessoa
🎯 Objetivo

Desenvolver um modelo de Machine Learning capaz de classificar imagens de rostos humanos de acordo com características raciais (branca/preta), utilizando técnicas de Transfer Learning e Redes Neurais Convolucionais (CNN).
🛠 Tecnologias Utilizadas

    Linguagem: Python

    Frameworks: TensorFlow/Keras, Transformers

    Modelos Pré-treinados: MobileNetV2, ViT (Vision Transformer)

    Processamento de Imagens: OpenCV, PIL

    Visualização: Matplotlib

📂 Estrutura do Projeto

projeto-ml/
├── data/
│   ├── treinamento/
│   │   ├── brancas/
│   │   └── pretas/
│   └── validacao/
├── notebooks/
│   └── Aula_ML_Pretalab.ipynb  # Código principal
├── models/
│   └── modelo_classificacao.h5  # Modelo treinado
└── img/                         # Exemplos de teste

🔍 Funcionalidades

    Pré-processamento de imagens (redimensionamento, normalização, data augmentation)

    Classificação binária usando CNNs e Transfer Learning

    Teste com imagens da web via URL

    Métricas de avaliação (acurácia, loss)

⚙️ Como Executar

    Instale as dependências:

bash

pip install tensorflow transformers pillow matplotlib

    Organize os dados:

    Coloque as imagens em data/treinamento/{classe} (ex: brancas/, pretas/)

    Treine o modelo:

python

    python train.py  # Ou execute o notebook Jupyter

🚧 Limitações

    Viés potencial em datasets desbalanceados

    Dificuldade com imagens de baixa qualidade

    Sensível a variações de iluminação/ângulo

