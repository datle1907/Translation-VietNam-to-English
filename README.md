# Vietnamese to English Translator

## What is this?
This repository contains code for training a simple neural machine translator as well as a trained model for the Vietnamese-to-English translator. 


## Trained model information
The model was trained with the [**OPUS TED2020-v1 en-vi text**](https://opus.nlpl.eu/TED2020-v1.php) data with more than 300.000 pairs of text sequences (see `Dataset` folder for details). 

The current model (in `translator.py`) is a simple encoder-decoder with 4-GRU-layer encoder and decoder. Due to the lack of resources, *attention mechanism* (with *bidirectional RNNs*) have not been used.  

### DEMO 

![Screenshot 2024-05-22 205817](https://github.com/datle1907/Translation-VietNam-to-English/assets/149254854/ecca9af0-857a-4498-b4a5-41b3922f457c)


After translate:

![Screenshot 2024-05-22 210123](https://github.com/datle1907/Translation-VietNam-to-English/assets/149254854/9e6d4d63-3a37-412b-ac17-afea830b9130)
