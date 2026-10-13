# Furniture Image Classifier

This project trains a neural network to recognise five types of furniture: beds, desks, lamps, sofas, and wardrobes, using a small image dataset. It adapts a pre-trained network (AlexNet) for the task, explores what the network has learned to look for in images, and then experiments with making it smaller via filter selection.

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
