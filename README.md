# 🧠 Treinamento de Redes Neurais com Transfer Learning: Classificação de Búfalos e Elefantes

Este notebook Colab implementa uma rede neural com **Transfer Learning** para classificar imagens de **búfalos** e **elefantes**. A base utilizada foi carregada diretamente do **Google Drive**, com estrutura de diretórios adaptada ao uso do `ImageDataGenerator`.

---

## 📁 Estrutura Esperada do Dataset

O dataset precisa estar no Google Drive com a seguinte organização:

dataset/
└── bufalo_elefante/
├── train/
│ ├── bufalo/
│ └── elefante/
└── val/
├── bufalo/
└── elefante/

---

## > 💡 Cada pasta deve conter apenas imagens da classe correspondente.

---

## ⚙️ Tecnologias Usadas

- Google Colab
- Python 3
- TensorFlow / Keras
- MobileNetV2 (pré-treinada no ImageNet)
- Google Drive (armazenamento dos dados)

---

## 📌 Funcionalidades do Notebook

- Montagem automática do Google Drive
- Pré-processamento e aumento de dados com `ImageDataGenerator`
- Construção de modelo com **MobileNetV2**
- Treinamento e validação com métricas de acurácia
- Predição de imagens externas (classe: búfalo ou elefante)

---

## 🖼️ Exemplo de Predição

```python
Predição: Elefante
```
---

## 🧪 Como Usar

1. Salve suas imagens nas pastas train/ e val/ organizadas por classe.

2. Suba essas pastas no seu Google Drive.

3. Execute as células uma a uma.

4. Altere o caminho da imagem de teste para fazer novas previsões.

---

## 📚 Referências

- MobileNetV2 - Keras Docs

- TensorFlow ImageDataGenerator

- Transfer Learning - Guia prático no Colab

