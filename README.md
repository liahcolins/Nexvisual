# Nexvisual - Desafios de Visão Computacional

## Sobre o Projeto

Este repositório reúne as soluções desenvolvidas para os desafios propostos durante a trilha de **Visão Computacional** da Nexvisual.

Os desafios abordam diferentes problemas encontrados em aplicações reais de Visão Computacional, utilizando desde técnicas clássicas até modelos modernos baseados em Deep Learning. Cada atividade foi implementada em Python por meio de notebooks Jupyter, explorando bibliotecas amplamente utilizadas no mercado.

## Objetivos

- Aplicar conceitos fundamentais de Visão Computacional.
- Utilizar modelos pré-treinados para tarefas específicas.
- Desenvolver soluções práticas utilizando OpenCV e Deep Learning.
- Consolidar conhecimentos sobre detecção, reconhecimento e rastreamento de objetos.

---

# Tecnologias Utilizadas

- Python 3.11
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- PyTorch
- Ultralytics YOLO
- OpenFace
- Jupyter Notebook

---

# Estrutura do Repositório

```
.
├── Desafio_1/
├── Desafio_2/
├── Desafio_3/
├── Desafio_4/
└── README.md
```

Cada diretório contém o notebook correspondente, arquivos auxiliares e modelos necessários para a execução.

---

# Desafios Desenvolvidos

## Desafio 1 — Processamento de Imagens

Implementação de operações básicas utilizando OpenCV, incluindo:

- Leitura e exibição de imagens;
- Conversão entre espaços de cores;
- Aplicação de filtros;
- Operações de suavização (Blur);
- Visualização dos resultados.

Principais bibliotecas:

- OpenCV
- Matplotlib

---

## Desafio 2 — Reconhecimento Facial

Construção de um pipeline completo de reconhecimento facial utilizando Deep Learning.

Etapas implementadas:

- Detecção de faces utilizando o detector SSD do OpenCV;
- Extração de embeddings faciais utilizando OpenFace;
- Treinamento de um classificador SVM;
- Reconhecimento de indivíduos em imagens de teste.

Modelos utilizados:

- OpenFace NN4
- SSD Face Detector
- Support Vector Machine (SVM)

---

## Desafio 3 — Rastreamento de Objetos

Implementação de rastreamento automático utilizando o modelo YOLO11.

O desafio contempla:

- Carregamento do modelo pré-treinado;
- Processamento de vídeos;
- Detecção e rastreamento de objetos;
- Geração de vídeo contendo as detecções realizadas.

Modelo utilizado:

- YOLO11 Nano

Biblioteca principal:

- Ultralytics

---

## Desafio 4 — Estimativa de Pose Humana

Aplicação de um modelo de estimativa de pose para detectar pontos-chave do corpo humano em imagens.

O notebook realiza:

- Carregamento do modelo YOLO11 Pose;
- Inferência sobre imagens;
- Identificação dos keypoints corporais;
- Visualização do esqueleto humano sobre a imagem original.

Modelo utilizado:

- YOLO11 Nano Pose

---

# Como Executar

Clone este repositório:

```bash
git clone https://github.com/liahcolins/Nexvisual.git
```

Acesse o diretório:

```bash
cd Nexvisual
```

Instale as dependências necessárias:

```bash
pip install opencv-python matplotlib numpy scikit-learn ultralytics torch torchvision imutils tqdm
```

Abra os notebooks utilizando o Jupyter Notebook ou o Visual Studio Code com a extensão Jupyter instalada.

---

# Competências Desenvolvidas

Durante a resolução dos desafios foram aplicados conhecimentos relacionados a:

- Processamento Digital de Imagens;
- Extração de características;
- Reconhecimento Facial;
- Aprendizado Supervisionado;
- Detecção de Objetos;
- Rastreamento de Objetos;
- Estimativa de Pose;
- Modelos Pré-treinados;
- OpenCV;
- Deep Learning;
- YOLO.

---

# Autor

Desenvolvido por **Liah Colins** como parte da trilha de Visão Computacional da Nexvisual.
