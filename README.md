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

**You :** hey  
**Chatbot :** welcome sir, would you like to know about tigers? i am an expert  
**You :** who are you  
**Chatbot :** I am a virtual asistant that can help you with tigers  
**You :** how many years tigers live  
**Chatbot :**  The oldest recorded captive tiger lived for 26 years   
 The average life span of a tiger in the wild is about 11 years 
 In the wild, tigers have a 14 year life span
 the gestation period in siberian tigers is 3-3
5 months   

**You :** is each tigers strip unique  
**Chatbot :**  Numbers of stripes and thickness of stripes can vary, so individual tigers can be identified by markings on their body, face or tail 
 Each tiger's pattern of stripes is unique, making it possible to identify different individuals – a handy thing for conservationists trying to keep track of which tigers live where   

**You :** what are tigers closest living relatives  
**Chatbot :**  The tiger's closest living relatives were previously thought to be the panthera species lion, leopard and jaguar 
 The surviving tiger subspecies are the siberian tiger, south china tiger, sumatran tiger, indochinese tiger, malayan tiger and bengal tiger   

**You :** up to which distance tiger roar can be heard  
**Chatbot :**  Tiger’s roar can be heard miles away 
 in southern india the god ayyappan was associated with a tiger 
 tigers have a range of vocalizations they can use to communicate with other tigers, including roars and hisses 
 occasionally tigers come to view people as prey   

**You :** are monkeys a prey for tigers  
**Chatbot :**  tigers are nocturnal with small prey such as monkeys and hares, the tiger bites the nape, often breaking the spinal cord, piercing the windpipe, or severing the jugular vein or common carotid artery 
 golden jackals may scavenge on tiger kills   

**You :** white tigers lives in  
**Chatbot :**  The white tiger has white fur and sepia-brown stripes 
 The snow white tiger is a morph with extremely faint stripes and a pale reddish-brown ringed tail 
 The golden tiger has a pale golden pelage with a blond tone   

**You :** number of tiger left in the wild  
**Chatbot :**  The tiger's range is fragmented, stretching from siberian temperate forests to subtropical and tropical forests on the indian subcontinent, indochina and sumatra 
 The number of tigers in 2002 stood at 3,642, and all remaining tiger populations are threatened with extinction   

**You :** what is the most common subspecies of tiger  
**Chatbot :**  bengal or indian tiger is the most common subspecies of tiger and is almost as large as the siberian tiger 
 the tiger is among the most recognisable and popular of the world's charismatic megafauna 
 india currently hosts the largest tiger population in the world   

**You :** tell me about tiger's paws and claws  
**Chatbot :**  tiger is one of the animals displayed on the pashupati seal of the indus valley civilisation 
 tiger’s front paws are large and strong to bring down prey 
 in european heraldry, the tyger is among the creatures used in charges and supporters   

**You :** what do tigers are hunt for  
**Chatbot :**  tigers appear to inhabit the deep parts of the forest while smaller predators like leopards and dholes are pushed closer to the fringes 
 In some cultures, people hunt tigers for sport or to demonstrate their own bravery 
 tigers are hunted for trophies or for body parts or skins   

**You :** what if the tigers go extinct  
**Chatbot :**  all remaining tigers are classified as endangered by iucn (with the sumatran and south china subspecies classified as critically endangered)
 tiger hunting for sport was banned in most countries where tigers lived, and the trade in tiger skins was outlawed 
 tigers don't make suitable pets and would not fare well if released into the wild   

**You :** what is the length of siberian tiger  
**Chatbot :**  There are six remaining sub-species of tiger: bengal (indian), sumatran, amur (siberian), malayan, amoy (south china) and indochinese 
 The siberian tiger (p
 tigris altaica) is the largest, measuring up to 4 metres in total length and weighing up to 300 kg (660 pounds)
You : what is the goal of the Siberian Tiger Project
Chatbot :  The goal of the siberian tiger project is to collect the best possible scientific information on tiger ecology for use in conservation plans 
 northwestern china is thought to be the origin of the tiger lineage 
 The surviving tiger subspecies are the sibian tiger, south china tiger, sumatran tiger, indochinese tiger, malayan tiger and bengal tiger   

**You :** how many tigers left in india  
**Chatbot :**  There are six remaining sub-species of tiger: bengal (indian), sumatran, amur (siberian), malayan, amoy (south china) and indochinese 
 india is home to the world's largest population of wild tigers   

**You :** what is the tiger population in the world  
**Chatbot :**  India is home to the world's largest population of wild tigers 
 The surviving tiger subspecies are the siberian tiger, south china tiger, sumatran tiger, indochinese tiger, malayan tiger and bengal tiger   

**You :** how many cubs can a female tiger can give birth to  
**Chatbot :**  Female tiger gives birth to a litter of three or four cubs, who she will care for until they are a year-and-a-half old 
 captive tigers were bred with lions to create hybrids called liger and tigon   

**You :** how tigers mark their territory  
**Chatbot :**  Each tiger's pattern of stripes is unique, making it possible to identify different individuals – a handy thing for conservationists trying to keep track of which tigers live where 
 tiger is one of the animals displayed on the pashupati seal of the indus valley civilisation   

**You :** 0  
**Chatbot :** I failed you sir  
