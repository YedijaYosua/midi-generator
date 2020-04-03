# MIDI Generator using LSTM Neural Network

This repository makes use of the CSV dataset provided in: https://www.kaggle.com/saikayala/jazz-ml-ready-midi and acts as completion for Assignment #05 of Bangkit Academy.

We use the first 100 MIDI songs to train a LSTM neural network to generate a MIDI song containing 500 notes.

## Dependencies
This project makes use of the following libraries:
* NumPy
* pandas
* Pickle
* Tensorflow
* Keras
* scikit-learn
* Music21
* Jupyter Notebook

## Usage
Run `model.ipynb` to train the model from the dataset `jazz-midi.csv`. The notes files are saved at `x.pickle` and `notes.pickle`, while the model and weights are saved at `model.json` and `model.h5` respectively.

To generate a MIDI file from the saved notes and model, run `predict.ipynb`, which will save the output MIDI at `output.mid`.
