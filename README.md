# -Pandemic-Helper-AI-Python
This is a chatbot that will give answers to most of your corona-related questions/FAQ. The chatbot will give you answers from the data given by WHO(https://www.who.int/). This will help those who need information or help to know more about this virus.

It uses a neural network with two hidden layers(enough for these QnA) that predicts which pattern matches the user’s question and sends it towards that node. More patterns can be added to the user’s questions to train it for more improved results and add more info about coronavirus in the JSON file. The more you train this chatbot the more it gets precise. The advantage of using deep learning is that you don’t have to ask the same question as written in the JSON file cause stemmed words from the pattern are matched with the user question
Training Data: 
To feed the data to the chatbot I have used JSON with possible question patterns and our desired answers. 
The JSON file used for the project is WHO 
For this project, I have named my JSON file WHO.json 
The JSON file tag is the category in which all those responses fall. 
patterns are used for listing all possible question patterns. 
responses contain all the responses with respect to the patterned questions 
Bag of Words: 
As we know neural networks and machine learning algorithms require numerical input. So our list of strings won’t cut it. We need some way to represent our sentences with numbers and this is where a bag of words comes in. What we are going to do is represent each sentence with a list of the length of the number of words in our model vocabulary. Each position in the list will represent a word from our vocabulary the position in the list is a 1 then that will mean that the word exists in our sentence, if it is a 0 then the word is not present.
