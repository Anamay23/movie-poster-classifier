# movie-poster-classifier
Using fast-ai, this project attempts classifies a dataset of movie posters into their respective genres

In this project, we use [fastai](https://www.fast.ai/), a library used to train models and provides high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains. 
First we create 3 databases containing movie posters of 3 genres (horror, romance, superhero) and train our model on the dataset. I have provided the database for all 3 genres. Each database is a .txt file containing the URLs of the movie posters. In the project, we use fastai's download_images functions to extract and store the images.
After training the model, we clean up our dataset to try and improve the accuracy.
Lastly we test our classifier by selecting a movie poster and checking whether the model can correctly classify it.

