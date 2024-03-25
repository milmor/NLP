# Procesamiento del Lenguaje Natural 2024-2 (FI, UNAM)

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
- No usar tensorflow==2.15.0 por problemas al reconocer CUDNN https://github.com/tensorflow/tensorflow/issues/60913