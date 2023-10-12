# ASR-Javanese
Automatic Speech Recogniton Javanese Language, using TF-Keras.

**Usage**
1. Create Virtual Env if you want using this command:
```python
python -m venv venv
```
2. Install Dependency, 
```python
pip install tensorflow numpy
```

i using `"tensorflow<2.11"` to activated GPU in my machine, you can install it as same as me or you can read the docs in tensorflow.org


Download [Model](https://huggingface.co/johaness14/ASR-Javanese-Language), then download or clone this file: `stt-openslr-jawa-testing.ipynb`, then open. Set kernel to `venv`.

Change this from Notebook:
```python
MODEL_LOAD = '' # you can change this to load model.
SOUND_PATH = '' # you can change this to predict it. 
```

# Training
You can training this model, in file `stt - openslr - jawa - training.ipynb`, and run it step by step.
