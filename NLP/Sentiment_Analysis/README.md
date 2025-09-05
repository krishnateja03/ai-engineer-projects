# ai-engineer-projects
Sentiment Analyis : 

1) Rule-Based Sentiment Analysis 
	- it uses predefined words and associates them with sentiments
	- e.g. word great = +ve, sad = "-ve"
	- it defines a polarity_score to each word ranging from -1 to 1
	- it is speed as it doesn't train the data but uses predefined list of +ve and -ve words to determine sentiment
	- It can't understand sarcasm/irony in text
	- it struggles with context and nuances around the text
	- can be implemented using TextBlob or VaderSentiment (FYI, I have used vaderSentiment in this implmentation)
	
2) Pre-trained Transformers
	- these are newly developed transformers that uses deeplearning techniques to determine how words relate to each other
	- can be implemented by transformers pipeline function
	- it defines a confident_score on how confident the model is about the result
	- Sometimes, this pre trained transformer model also gets it wrong (we can use any other specific models available)
	- can be found in huggingface transformers models
 
