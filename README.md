# 🐶🐱 Classificador de Gatos e Cachorros com PyTorch

Este projeto usa Deep Learning com PyTorch para treinar uma rede neural convolucional (CNN) capaz de classificar imagens como **gato** ou **cachorro**. Foi feito com foco educacional, com explicações passo a passo para iniciantes em redes neurais.

---

## 📁 Estrutura de Pastas

O dataset deve seguir esta estrutura (baseada em `torchvision.datasets.ImageFolder`):

dataset/
├── treino/
│ ├── 0_gato/
│ └── 1_cachorro/
├── teste/
│ ├── 0_gato/
│ └── 1_cachorro/

yaml
Copiar
Editar

> As pastas `0_gato` e `1_cachorro` foram nomeadas assim para garantir que o PyTorch atribua os rótulos corretos: `0 = gato`, `1 = cachorro`.

---

## ⚙️ Tecnologias Usadas

- Python 3.11+
- PyTorch
- torchvision
- matplotlib
- PIL (Pillow)
- CUDA (opcional, para treinar na GPU)

---
