# NLP-HuggingFace
This repo contains notebooks and links of the NLP models on the hugging-face website that i fine-tuned or made from scratch using the transformers library by huggingface.

## Token Classification(POS Tagging)
Notebook: https://colab.research.google.com/drive/1ljdlRFecoy-jkemi97pV9qvNskZkrYnl
Huggingface Model Link: https://huggingface.co/Sanyam52/bert-pos-tagging

POS tagging means to Mark each word in a sentence as corresponding to a particular part of speech (such as noun, verb, adjective, etc).
I fine-tuned bert on conll dataset for POS tagging and results:
Train Loss: 0.6701
Validation Loss: 0.5308
'overall_precision': 0.7811213028828154,
'overall_recall': 0.6691925266618555,
'overall_f1': 0.7208378320017275,
'overall_accuracy': 0.8086042374251982


## Summarization, Extractive Question Answering are on the way
