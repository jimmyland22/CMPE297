# Fine Tuning Language Models

Using examples from Hugging Face transformer notebooks - https://huggingface.co/transformers/notebooks.html
For Gradio - I used this article and the corresponding repository - https://towardsdatascience.com/building-nlp-web-apps-with-gradio-and-hugging-face-transformers-59ce8ab4a319

## (1) Classification (Sentiment Analysis)
Fine tuning the distilbert language model to do sentiment analysis. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Ran the fine tuning for 5 epochs. It's fastest with a GPU.

![Classification Training](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Classification.png)

## (2) Name Entity Recognition
Fine tuning the distilbert language model to do NER. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Fastest with a GPU.

![NER Training](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/NER.png)

## (3) Text Summarization
Fine tuning the T5-Small model for text summarization. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Training just 1 Epoch takes a REALLY long time and ran out of compute and memory sometimes. Example summarization using the CMPE 297 Course Description.

![Summarization Example](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Summarization.png)


## (4) Multiple Choice
Fine tuning the Bert model for multiple choice. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. I only ran the training for 1 epoch as it takes a really long time.

![Summarization Example](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Multiple.png)

## (5) Sentence Pairs
Fine tuning the Bert model for semantic equivalence in sentence pairs. I followed the TensorFlow tutorial here: https://www.tensorflow.org/text/tutorials/fine_tune_bert
It goes much deeper into TenshrFlow code and preprocessing data than the Hugging Face guides.

![Sentence Pair Example](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Sentence_Pairs.png)