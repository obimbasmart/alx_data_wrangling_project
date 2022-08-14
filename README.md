# Data Wrangling on Twitter data - (alx-udacity)

The aim of this project is **to gather, access and clean data, to create reliable analysis.**  The data for this project is the tweet archive of `@dog_rates`, also known as `WeRateDogs`. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

The initial WeRateDogs twitter archive doesn't contain all the required information/variables for this project. Such variables include number of retweet, number of likes. This variables are very important for this analysis, hence I'll be using the **Twitter API** to query this additional information

Additionally, an image_prediction.txt file has been provided. The content is the result from a neural network that can classify breeds of dogs.The file is full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images). This file would be downloaded programmatically

Therefore, the aim is to gather and convert these three data files into a high-quality data, reliable for analysis

## Motivation

The project is part of the requirement for a successfull completion of the `Alx-Udacity Data Analytics nanodegree program`

## Technologies/libraries
- Twitter API
- [tweepy](https://www.tweepy.org/)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [json](https://docs.python.org/3/library/json.html)
- [seaborn](https://seaborn.pydata.org/)
- [request](https://docs.python.org/3/library/urllib.request.html)
- [os](https://docs.python.org/3/library/os.html)