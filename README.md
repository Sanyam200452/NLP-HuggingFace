# NLP-HuggingFace
This repo contains notebooks and links of the NLP models on the hugging-face website that i fine-tuned or made from scratch using the transformers library by huggingface.

## Token Classification(POS Tagging)
Notebook: https://github.com/Sanyam200452/NLP-HuggingFace/blob/main/Token_Classification.ipynb
<br>
Huggingface Model Link: https://huggingface.co/Sanyam52/bert-pos-tagging

POS tagging means to Mark each word in a sentence as corresponding to a particular part of speech (such as noun, verb, adjective, etc).
I fine-tuned bert on conll dataset for POS tagging and results:
Train Loss: 0.6701
Validation Loss: 0.5308
'overall_precision': 0.7811213028828154,
'overall_recall': 0.6691925266618555,
'overall_f1': 0.7208378320017275,
'overall_accuracy': 0.8086042374251982

## Translation
Finetuned MarianMT model for translating from english to shakespearean
Dataset Used is called Shakespearify.csv(don't have the link now, but I uploaded the csv file above)
Achieved a validation loss of 2.14 and a training loss of 2.03 by training over 40000 rows of data for 3 epochs
BLEU Score couldn't be calculated because it needs a lot of computational power
Notebook Link: https://github.com/Sanyam200452/NLP-HuggingFace/blob/main/Translation.ipynb
<br>
Model Link: https://huggingface.co/Sanyam52/marian-finetuned-english-to-shakesperian
<br>
Deployed Model on Huggingface Link: https://huggingface.co/spaces/Sanyam52/shakespearean_translation

## Summarization, Extractive Question Answering are on the way(Don't hold your breath)


