# Image-Caption-Generator-using-Deep Learning


## Description
This repository contains files related to the  project on Image Caption Generation using Deep learning

----
## Dataset
1. Flickr30k Dataset has been used for the training of model.
   [Flickr30K](https://www.kaggle.com/hsankesara/flickr-image-dataset)
2. Glove6B dataset [Link](https://drive.google.com/open?id=1GI5sWeCxgJEgToeVmakL69oDlXowXGU4)

## Requirements
* Python 3.7
* Matplotlib
* Pandas
* Numpy
* PIL 
* Tkinter
* keras
* tensorflow


## Run Model in steps

***Image Feature Extraction***

$ python3 ImageFeature_extraction.py

***Caption Preprocessing step***

$ python3 clean_captions.py

***Generating Vocabulary of Caption words***

$ python3 vocabulary.py

***Training of the Model***

$ python3 training.py

***Test model***

$ python3 gui.py

use tkinter for GUI

## Testing The Model
 
to run gui write the command  in the  command prompt  python gui.py

***Test Results***

When you run the gui.py using above command it will show you welcome screen and will ask you to choose the image from your local directory. 


