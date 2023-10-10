# ASR-Javanese
Automatic Speech Recogniton Javanese Language, using TF-Keras.

**Usage**
1. Create Virtual Env if you want using this command
```python
python -m venv venv
```
2. Install Dependency
```python
pip install tensorflow numpy
```
Download [Model](https://huggingface.co/johaness14/ASR-Javanese-Language), then download or clone this file: `stt-openslr-jawa-testing.ipynb`, then open. Set kernel to `venv`.

Change this from Notebook:
```python
MODEL_LOAD = '' # you can change this to load model.
SOUND_PATH = '' # you can change this to predict it. 
```
