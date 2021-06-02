# Google Collab Directory for Audio4All Machine Learning

**Note: if you use any of the following collabs, please remap the dataset folder locations, which will be the same from  
r".../Datasets/somesubfolderORfile"

## TreeModel
This is the primary code used on the Jetson. This makes up the code that creates our binary tree for Jetson Inferencing. In its given state an assumption of pure odds is made for the next choise in a chord progression.

## NLP_Model
This directory contains both RNN & LSTM networks that work, but have some issues that pertain specifically to Dataset format.

## Misc.
This is more of a tinkering space, feel free to look over the code, but none of this was used for any of the final product (YET!)

## DatasetCreation.ipynb
This notebook contains the code that was used to create our clean dataset. Unfortunately, the dataset only works well with computer 
created .Midi files because of thresholding issues. In simple terms, to create 'chords' you must first decide where a chord ends and a new chord begins. But humans to not turn 3 keys on and off simultaneously, and more importantly, sometimes you will start the next 
chord, before releasing the previous. This creates issues in pre-processing, that in the given state were not resolved.
