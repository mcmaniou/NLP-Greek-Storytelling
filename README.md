# nlp_greek_storytelling

This project presents an implementation of the GPT-2 model, trained to generate short fairytale stories in the Greek language. 

The repo is organized in the following folders:
- code : the python notebooks
- data : the raw, as long as, the processed input files with the fairytales (gathered from the web)
- results : the training metrics (gathered during the training) and the evaluation scores (extracted from a google form)
- model : the final trained model 

Moreover, the code folder includes the following scripts:
- `preprocessing.ipynb` : used to clean-up the raw input `.txt` files and produce the `_processed.txt` files 
- `greek_storytelling.ipynb` : includes the tokenization, model configuration, training and saving steps
- `use_pretrained_model.ipynb` : a short script that can be used to load our trained model and generate your own stories!
