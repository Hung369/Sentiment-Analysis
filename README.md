
# Sentiment Analysis

Finetuning the pretrained BERT model for the task of sentiment classification on text data.


## Dependencies

* Python 3.10 - 3.11 is needed
* Python IDE: Google Colab (recommend Pro/Pro+ version)


## Dataset

The Amazon Polarity dataset is a collection of Amazon product reviews (mainly in English) designed for binary classification tasks. It contains product reviews labeled as either positive or negative.

With either 1-star (negative) or 5-star (positive) ratings, the dataset includes millions of reviews, provides a clear polarity between positive and negative sentiments. It is also available on [Hugging Face](https://huggingface.co/datasets/fancyzhx/amazon_polarity)
## Deployment

To deploy this project, you have to:
* Create a folder to save model's checkpoints on your own Google Drive.
* Open the ipynb file in colab, choose GPU runtime.
* Mount the code to the created folder on Google Drive
* Run all cells to start the training pipeline 


