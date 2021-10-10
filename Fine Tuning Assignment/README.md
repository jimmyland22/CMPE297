# Fine Tuning Language Models

Using examples from Hugging Face transformer notebooks - https://huggingface.co/transformers/notebooks.html
For Gradio - I used this article and the corresponding repository - https://towardsdatascience.com/building-nlp-web-apps-with-gradio-and-hugging-face-transformers-59ce8ab4a319

## Classification (Sentiment Analysis)
Fine tuning the distilbert language model to do sentiment analysis. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Ran the fine tuning for 5 epochs. It's fastest with a GPU.

![Classification Training](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Classification.png)

## Name Entity Recognition
Fine tuning the distilbert language model to do NER. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Fastest with a GPU.

![NER Training](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/NER.png)

## Text Summarization
Fine tuning the T5-Small model for text summarization. I used the Hugging Face example notebook as a guide, and used the Gradio example to implement the UI. Training just 1 Epoch takes a REALLY long time and ran out of compute and memory sometimes. Example summarization using the CMPE 297 Course Description.

![Summarization Example](https://github.com/jimmyland22/CMPE297/blob/main/Fine%20Tuning%20Assignment/Summarization.png)
