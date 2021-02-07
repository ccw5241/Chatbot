# Chatbot

A chatbot is a software that provides a real conversational experience to the user, A well-optimized chatbot can converse as well as humans can: asking and answering a wide range of questions, displaying knowledge, and being empathetic, personable, engaging, serious, or fun. 
Here for our project, I use generation strategy to create an open domain chatbot which can generate a response as the name implies. It can be a great addition to a company’s business because it can help to boost conversation rates. 

I use Tensorflow and Keras to build  LSTM Seq2Seq model, recurrent neural network to identify the context the user is asking and then provide it with the relevant answer. Since the dataset is relevant small and the limitation of computation, for preprocessing step, I separately use two main vector representation in Natural Language Processing(NLP) which are one-hot encoding and embedding to convert human conversation to vectors. For optimization performance process, I change the optimizer hyperparameter. 

I used Python and Keras API, NLP techniques and google colab to build our deep learning models. The datasets I used are collected from Kaggle which consists of 2363 entries records conversations between a human and other human acting as a companion bot.
