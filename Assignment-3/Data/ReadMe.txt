1. The data set Corona_NLP_test file contains many number of rows and columns, As all the operations for the dataset are being performed on OriginalTweet column.
2. The first stage is to clean the data, which involves finding and deleting null values in the dataset as well as identifying and removing duplicate entries Within the dataset.
3. Using the OriginalTweet column as a new dataset and applying some preprocessing procedures on it:
    1. removing the special characters
	2. removing the URLS in the string
	3. converting to lowercase
	4. stopwords removal
4. Word tokenization is used to convert the text corpus into tokens.
5. Counting word frequencies and plotting the top ten words.
6. Created the word clouds and plotted the result.