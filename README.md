# Chatbot on tiger
![Royal_Bengal_Tiger_(40961228)](https://user-images.githubusercontent.com/77840111/181678629-d961b2d3-9008-4f50-b56d-24aa28ba45e7.jpeg)

## This chat bot uses cosine similarity to answers queries about tigers
## Requirements
- files
- nltk
- transformer
- sklearn
- os
- random

## methodology
This is not a simple AI based chatbot or rule based chatbot. Our psudocode for this chatbot is..  
**step 1.** we have prebuilt a corpus of information about tigers from different sources  
**step 2.** we will tokenize the text  
**step 3.** define a function "answer" inside which a lot of things happen. we use sentence embeddings. and then calculate the cosine similarity between every sentence in the corpus and the query. and get the 10 best sentences. now we use a pretrained text summarizer 'transformer' to summarize the 10 sentences.  
**step 4.** If our query contains the word 'tiger' then it would execute that function otherwise it will return some other Responses

## Responses

