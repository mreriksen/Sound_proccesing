The goal of the script is to find beats and to estimate the global tempo for an audio clip, this is done by
using spectral flux to determine beats and Fourier-based tempogram analysis to determine the tempo.
The program needs to run the file SimpleBeatTracker.ipynb and it needs an audio file in the .wav
format. Alongside the necessary libraries such as librosa, numpy, and matplotlib. Finally, the user
needs to update the audio file variable (near the bottom of the script) to the local path of the audio
file, that the user wants to use the beat tracker on.

The audio file that is in this repository is from the GTZAN dataset found at:
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
