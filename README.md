# Project_Music_Generation
Music can be generated even with the help of artificial intelligence. The following model uses LSTM to train our model on music dataset. Further it generates its own music using some random seed.

# Training Dataset
https://www.kaggle.com/chetanmj23/pop-music-collection

# Model
1) The model used is sequential
2) The model uses two layers of LSTM with two layers of Dropout(All alternatively)
3) The last layer is ofcourse a Dense Layer with linear activation

# Steps involved
1) Reading midi files using mido library functions.
2) Data preparation for feeding our model: Data_Preparation.ipynb does the same, by converting midi files in required numpy arrays.
3) Trainig the model on above dataset
4) Generating a song for random seed and saving it as midi file.

# Results:
The machine was able to generate the music, although it does not sound as much good (nor too bad). But it might be 
possible that in near future, with the help of new innovations, machines can do so.


# How to play midi files in Ubuntu
There may be various ways of playing midi/mid files, The easiest one according to me is summarized below:
Open the terminal and enter:

sudo apt-get install timidity timidity-interfaces-extra

Enter your password, another prompt may appear type, Y and hit enter.

Go to your menu, you should now have an application called TiMidity++ launch it.
