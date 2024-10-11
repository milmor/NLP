# Procesamiento del Lenguaje Natural 2025-1 (FI, UNAM)

Este repositorio contiene todo el código y los laboratorios de software para el curso de Procesamiento del Lenguaje Natural de la FI, UNAM.

## Dependencias
- Python 3.9.16
- Pytorch 2.2.0
- Keras 3.0.0
- KerasNLP 0.8.2
- Tensorflow 2.14.0
- Transformers 4.39.1

## Ambiente local
```
conda create --name keras3 python=3.9.16
conda activate keras3
pip install tensorflow==2.14.0 jupyterlab numpy pandas matplotlib scikit-learn ipywidgets
pip install torch==2.2.0 torch-summary torchtext
pip install keras==3.0.0
pip install spacy transformers keras_nlp opencv-python
```

## Colab
```
pip install torch==2.3.1 torchvision==0.18.1 torchaudio==2.3.1 --index-url https://download.pytorch.org/whl/cu121
pip install torchtext==0.18
```