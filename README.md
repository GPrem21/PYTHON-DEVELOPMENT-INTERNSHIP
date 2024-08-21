# PYTHON-DEVELOPMENT-INTERNSHIP
This project is a simple chatbot built using Python, Keras, and TensorFlow.

Requirements 
1. keras_nightly
2.tensorflow
3. numpy 
4. nltk 
5. keras

Install the dependencies: pip install -r requirements.txt Before running the code, ensure you have the necessary NLTK data files by running: import nltk nltk.download('punkt') nltk.download('wordnet')

To train the chatbot model: Ensure that intents.json is populated with the necessary intents, patterns, and responses. Run the train_chatbot.py script to preprocess data and train the model. The trained model is saved as chatbot_model.h5, and the processed words and classes are saved as words.pkl and classes.pkl.
