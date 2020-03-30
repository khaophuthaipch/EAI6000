# EAI6000
This repo contains academic projects, lab codes, and assignments from the course EAI6000 <br> 

**Class Assignment** <br>

[Titanic Dataset (Kaggle)](https://github.com/khaophuthaipch/EAI6000/blob/master/PimKhaophuthai_EAI6000_Assignment1(Titanic).ipynb) - Predicting who will survive the sinking with Random Forest

[FMNIST Classification with Linear model](https://github.com/khaophuthaipch/EAI6000/blob/master/PimKhaophuthai_EAI6000Assignment2%20-%20Classification.ipynb) - Classification of fashion data set from MNIST using linear model namely LogisticRegression, LinearSVC, and KNN. This is a practice notebook to get familiar with building model including searching for hyperparameter and visualizing coefficient plots

[FMNIST Classification with Tensorflow](https://github.com/khaophuthaipch/EAI6000/blob/master/PimKhaophuthai_Week3_Lab_Fashion_MNIST.ipynb) - Classification of different types of cloths using tensorflow; Simple Neural Network with error analysis. 

[Street view house number classification](https://github.com/khaophuthaipch/EAI6000/blob/master/Assignment_3_Street_View_House_Numbers.ipynb) - Detect and classify digits from street view house number image. 32-by-32 RGB images centered around a single digit of a house number appearing in Google Street View. Many of the images do contain some distractors at the sides. It consists of 10 classes, 1 for each digit.

**Class Project** <br><br>
[Disaster tweets classification. Real or not?](https://github.com/khaophuthaipch/EAI6000/blob/master/EAI6000_Presentation_FinalProject.ipynb) - Involved NLP and RNN (LSTM, Bidirectional)
<br><br>
The dataset is callled Real or Not? NLP with Disaster Tweet downloaded from Kaggle as a csv file. There are 7613 rows with 5 columns in training set and 3263 rows with 4 columns in testing set. The features are id, keyword, location, text, and target. Target is the label for each sample indicating if the tweet is a real disaster tweet (1) and otherwise (0)
<br><br>
The flow of the project are as follows:
<br><br>
Text cleaning
- Remove special characters
  - Remove emoji
  - Spelling correction. We have written a code to perform correction but it is time consuming therefore we do not run the code and leave it as an option to do in the future.
- Text preprocessing
  - Transform text into proper format to use in the models :
    - Vectorization, one hot coding
    - Word Embedding, GloVe
- Modeling
  - Linear Model
  - Recurrent Neural Network
    - LSTM
