# Multiclass Speech Identification

[[Paper]](https://github.com/Joshimello/SpeechIdentification/raw/main/paper.pdf)

We present an approach to multiclass speechidentification, focusing on the simultaneous identification ofmultiple speakers in an audio stream. Utilizing a deep neuralnetwork, our method demonstrates potential in differentiatingand recognizing individual speakers from a composite audiosignal. The system's effectiveness is evaluated throughexperiments, showcasing its applicability in diverse real-worldscenarios where multiple-speaker recognition is crucial.


## Repo files

Notebooks folder holds the notebooks we used to complete this paper.

- demo.ipynb : demo notebook from recording your voice, training, then identifying in realtime.
- model.ipynb : notebook to test the architecture of the selected model.
- playground.ipynb : notebook used during initial testing phase for data processing.
- processdata.ipynb : processing data and augmentation, to saving as pkl files done in this notebook. 
- readdata.ipynb : testing the reading of the pkl files. 


Datasets folder holds the compressed data we used for training. The data was compiled from processdata.ipynb.

Results folder holds the TensorFlow training logs, viewable via tensorboard.


## Setup

The whole process was done in a Google Colab environment.

We do not expect these be ran on individual local environments.

You may copy the ipynb files to a Google Colab environment.

Change paths to fit local testing directories.

Click run.


## Performance

The performance is available as a TensorFlow training logs folder.

You may view the training performance via tensorboard.


## Demo

A demo video is viewable in root of project as demo.mp4




