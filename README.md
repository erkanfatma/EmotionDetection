# Emotion Detection
Sentiment analysis is one of the most popular applications of Natural Language Processing. The key idea of the sentiment analysis is to analyze a text to understand the opinion that expressed. The text is usually expressed via a person who have moods, emotions, feelings. Sentiment analysis is generally used in social media analysis (to launch better product). 
Sentiment Analysis is an analyze of the sentence. In the dataset, text gives an opinion about the sentence. In the project, a model was implemented that inputs a sentence and finds the most appropriate emotion to be used in the sentence. 

## Methodology
In this assignment the topic which is how to apply deep learning techniques to the emotion analysis. Emotion analysis is the experience about a part of natural language. It determines if the sentence’s emotional tone is positive or negative with the emotions called joy, sadness, anger, fear, love, and surprise. This assignment contains some topics such as word vectors, recurrent neural networks (RNN), and long short-term memory units (LSTM). 

#### Why Deep Learning Fits into Natural Language Processing (NLP) Tasks
Natural language process is to create systems that understand language in order to perform certain tasks such as translating a paragraph of text to another language, computers recognize spoken language, recognition the emotion behind a sentence etc. The main behind the NLP is the advancement of Deep Learning techniques the RNN and CNN models. NLP combines linguistics and computer to create intelligent systems to understand, analyze and extract meaning of text or sentence. 

#### Recurrent Neural Networks (RNN)
RNN is a type of Neural Network where the output from the previous step is fed as the input of the current step. Another saying, it is a generalization of feed forward neural network which has an internal memory. This model is designed to identify the sequential characteristics of the data and use patters to predict the next scenario. 
It is assumed that inputs and outputs are independent from each other in a neural network. On the other hand, RNN model is not suitable for many cases like prediction the next word in the text. In the model, it will be better to know which word came before it. RNN is making use of sequential information. This information called recurrent because they perform the same process for every element of a sequence. Output depends on the previous computations and they have a memory that captures information about what has been calculated. RNN uses its internal memory to process sequence of inputs. 

#### Long Short-Term Memory Units (LSTM)
RNN has problem with short-term memory. If a sequence is long, RNN has hard time carrying information from previous time steps to next ones. If trying to process a paragraph of text for prediction, RNN can leave out important part from the beginning. For this reason, this problem causes the need of Long Short-Term Memory that is a kind of RNN. LSTM remembers the information for a long time. A common LSTM is composed of a cell, input gate, forget gate and output gate. 
 
The main component of the LSTM is the memory cell. The cell remembers values over time intervals consist of cell state vector and gating units. Gating units regulate the data flow into and out of the memory. Cell state vector represents the memory of the LSTM. Forget gate controls the information to throw away from the memory. Input or update gate controls the new data is added to cell state from current input. Output gate decides what to output from the memory. 
