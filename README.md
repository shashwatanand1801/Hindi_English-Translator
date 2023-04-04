# Hindi_English-Translator

A light model which once trained can be used offline for places where there is less internet
connectivity. In India more than 500 million people speak hindi.
To implement this I have done the following things :
1. Data preprocessing: We have preprocessed the IIT Bombay English-Hindi dataset
by cleaning the data, splitting it into train and validation sets, and tokenizing the text
using the HindiTokenizer and MarianTokenizer classes from the transformers
library.
2. Model training: We have trained a transformer-based sequence-to-sequence model
using the MarianMT class from the transformers library. We have used the AdamW
optimizer to update the model parameters during training.
3. Model evaluation: We have evaluated the performance of the trained model on the
validation set by generating translations for the input Hindi sentences using the
generate method of the model.
**This approach can be extended to other languages and datasets as well.
