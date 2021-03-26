##CHATBOT

An AI-based software that helps the users out with particular tasks trying to imitate a human's actions as much as possible!

Real-Life Examples:
1. Siri 
2. Alexa
3. Google Assistant

Why Chatbots?
1. Cost and Time Effective
2. Cheap Development Cost

Types of Chatbots
1. Rule-Based Bots
2. Self-Learning Bots
    1. Generative Bots
    2. Retrieval-Based Bots
    
About the Project:
Using a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then giving a random response from the list of responses.
1. intents.json – The data file which has predefined patterns and responses.
2. train_chatbot.py – A script to build the model and train our chatbot.
3. words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
4. classes.pkl – The classes pickle file contains the list of categories.
5. chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
6. chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

Step followed:
1. Import and load the data file
2. Preprocess data
3. Create training and testing data
4. Build the model
5. Predict the response

To run the chatbot, there are two main files; train_chatbot.py and chatapp.py.

First,
    
    python train_chatbot.py

then,
    
    python chatgui.py

Category: Machine Learning
Programming Language: Python
Tools & Libraries: Keras, Tensorflow, NLTK
Front End: Python – Tkinter
Back End: Python
Prerequisites: Python, Machine Learning
