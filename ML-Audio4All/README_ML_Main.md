# Main Directory for All things ML!
The following directory serves as all things ML. This will include Collab/Jupyter Notebooks where tinkering, training, evaluation, 
and dataset manipulation took place. Most collabs will have hard file links to my personal collab, however the provided datasets are
given under the "Datasets" directory. If you use the collabs, make sure to change the path to the given file within that Directory.
This Dir will also house any inferencing code for the Jetson Nano. Further Explanation for each folder will be given below.

## Datasets
Our datasets our broken into 2 primary areas:
  1. Midi Files  
  .Midi is a digital file format to store music. Without going to indepth, the primary attributs are "note_on, note_off, and "pitch". 
  These are the basic attributes that were used for training.
  3. TensorFlow or Torch based Datasets created from scrubbing the Midi Files  
  The converted datasets convert the .Midi files into an organized dataset that can be used for training  
  
## GoogleCollabNotebooks
This folder contains all notebooks for processing our data, and training our models. This is the playground for all the ML

## StaticChord_Jetson_Inferencing
Contains the code for inferencing on the Jetson. Is primary made up of binary_tree code that was created and tested inside 
"/GoogleCollabNoteboooks/TreeModel/Tree_Model_Creator.ipynb", as well as, serial code from both I2C and UART protocols which were 
used for communicating with both a Jetson Nano, and BELA (3rd party controller built on top of Begal Bone)
