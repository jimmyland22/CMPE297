# CMPE297 - Perciever Assignment
Implement perceiver ml model for classification in keras

## Implement perceiver ml model for classification in keras. Use it to classify some simple image data set
Using "Image classification with Perciever" example code as a guide: https://keras.io/examples/vision/perceiver_image_classification/

The example used the CIFAR-100 dataset, and I just did a tweak to use the MNIST image set for faster training.
![Sample MNIST images](https://github.com/jimmyland22/CMPE297/blob/main/Perciever%20Assignment/MnistExamples.png)



## Use perceiver IO model code in a colab for an interesting ml task
Using "Perciever - masked language modeling" as a guide: https://colab.research.google.com/github/2796gaurav/code_examples/blob/main/Perceiver/Perceiver_masked_language_modelling.ipynb

Using the pre-trained Perciever IO language model. Tested out the masked token prediction with great result.

Starting with a text string:

![Original String](https://github.com/jimmyland22/CMPE297/blob/main/Perciever%20Assignment/original_string.png)

Masked one word: **entertaining**

![Masked String](https://github.com/jimmyland22/CMPE297/blob/main/Perciever%20Assignment/masked_string.png)

Used Perciever IO to predict the masked word:

![Predicted String](https://github.com/jimmyland22/CMPE297/blob/main/Perciever%20Assignment/predicted_string.png)

 