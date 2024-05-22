# Vietnamese to English Translator

## What is this?
This repository contains code for training a simple neural machine translator as well as a trained model for the Vietnamese-to-English translator. 


## Trained model information
The model was trained with the [**OPUS TED2020-v1 en-vi text**](https://opus.nlpl.eu/TED2020-v1.php) data with more than 300.000 pairs of text sequences (see `datasets` folder for details). 

The current model is a simple encoder-decoder with 4-GRU-layer encoder and decoder. Due to the lack of resources, *attention mechanism* (with *bidirectional RNNs*) have not been used.  

In the future, *beam search* and *random translation* may also be added to improve performance of the model.  


**Copyright**  

The training data I have used are taken from the OPUS corpus:  

> Website: http://opus.nlpl.eu
> 
> Please cite the following article if you use any part of the corpus in your own work: J. Tiedemann, 2012, Parallel Data, Tools and Interfaces in OPUS. In Proceedings of the 8th International Conference on Language Resources and Evaluation (LREC 2012)
> 
> This dataset contains a crawl of nearly 4000 TED and TED-X transcripts from July 2020. The transcripts have been translated by a global community of volunteers to more than 100 languages. The parallel corpus is available from https://www.ted.com/participate/translate

