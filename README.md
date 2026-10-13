# Furniture Image Classifier

AlexNet is the Neural Network famously used by Geoffrey Hinton, Ilya Sutskever and Alex Krizhevsky to win the 2012 ImageNet Large Scale Visual Recognition Challenge. Their success proved the effectiveness of deep covolutional neural networks in Computer Vision, and demonstrated the use of GPUs to accelerate deep learning.

This project fine tunes the pre-trained AlexNet to recognise five types of furniture: beds, desks, lamps, sofas, and wardrobes, using a small image dataset (furniture.zip). It then explores what the network has learned to look for in images and experiments with making the network smaller via filter selection.

## Getting started

You'll need Python 3 installed. Then run the following in the project folder:

**Windows**
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

**Mac/Linux**
```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Once Jupyter opens in your browser, open `CVassignment.ipynb` and run the cells from top to bottom.

> **Note:** Training runs on CPU and takes a while on first run. Trained weights are saved automatically so subsequent runs skip training and load them straight away.
