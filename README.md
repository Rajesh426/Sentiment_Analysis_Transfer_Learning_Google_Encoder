# Sentiment_Analysis_Transfer_Learning_Google_Encoder
Using Google colab for sentiment Analysis using the pre trained Google gnews model for the IMDB dataset for review <br>
# Dataset <br>
Dataset is IMDB review dataset with positive and negative reviews <br>

### Using pretrained embedded layer for converting the raw sentences into 20 dimensional vectors using google gnews then a hidden dense layer of 16 neurons and output layer of 1 is added to the google gnews embedded model since it is a binary classification output layer of one neuron is sufficient <br>

[Google gnews model] (https://tfhub.dev/google/tf2-preview/gnews-swivel-20dim/1) <br>
# Google Co Lab <br>
## Google colab can run ipython file using the google gpu in the runtime selection 
[GoogleColab ](https://colab.research.google.com/notebooks/welcome.ipynb) <br>

# Important # 
## Since tensorflow hub support tensorflow of 2.X so it is better to run those versions in google colab so we can restrict the colab to use it by running the first cell or else it may generate error with respect to table initialization 
