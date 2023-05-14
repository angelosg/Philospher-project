# Philospher text generator
Do you ever wonder what philosphers may have said about certain topics? I don't really either but this was is a project to learn a bit about text generation from an NLP course. I haven't spent much time reading philosophical essays but this project took a larget set of sentences from five different philosphers and built a model based on these sentenes. Now you can enter some starting phrase for each phillospher and it outputs text generated based on their prior work. It is actually kind of fun and you can get some entertaining results. Feel free to try it out and see what you get, make sure you check comments because not all code blocks need to run. To run it yourself it's best to open in Colab https://colab.research.google.com/drive/1vAwfqkFLCXJR_MwCIEOurTrIst9RyWZq#scrollTo=fKUh9Z7ympNi

Some examples include
1: Plato: The meaning of life is not to be determined either in the sense that a man is dead, or in the sense that he is alive. 

1: Kant: The meaning of life is that which is the object of our conception of our existence, and which is the object of our intuition, and is the object of our intuition.

1: Aristotle: The meaning of life is that which is in the state of mind.

1: Hume: The meaning of life is that when we consider the person who is a slave, we will consider him who has not his liberty to govern.

1: Nietzsche: The meaning of life is a necessary consequence of the state of mind.


#Philospher classifier
A second aspect of the project is training a classifier. I split the data into a 70/30 ratio for train-test split and given trained a classifer to determine what author wrote a sentence. Following training the classifier, the model is about 85% accurate, which for a classifier with five categories is actually pretty good.

