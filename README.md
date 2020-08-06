# Hateful_Memes
My model for detecting if a meme is hateful/dank

## About Hateful Memes
We all come across memes over the internet. They are the craze of today! But some of them are not really for everyone. They are deliberately aimed to hurt religous sentiments which people tend to take offense to. Here's an example:

![Hateful Meme](https://github.com/aryamansriram/Hateful_Memes/blob/master/01235.png?raw=true)

Not very tasteful I know. But then there are also harmless memes like this:

![Non Hateful Meme](https://github.com/aryamansriram/Hateful_Memes/blob/master/01379.png?raw=true)

Classifying them automatically poses a huge challenge and can be framed as a Deep Learning problem.

Our solution  uses a CNN which extracts features from the image, BERT, which is used to get embeddings from the meme caption. The concatenated output of the two
is then passed through as dense layer to finally predict the output

## How do I use it:
You can run the notebook in the above repo using colab.






