# Automatic Music Generation

In this project, we create a music generator using the LSTM (Long Short-Term Memory) model, a machine learning algorithm to create pieces of music from existing music data. The model utilizes deep learning techniques (LSTM neural network) to analyse the patterns and structure of music pieces and create new ones of similar style.

Recurrent Neural Network (RNN) is a type of artificial neural network which uses sequential data or time series data. These deep learning algorithms are commonly used for ordinal or temporal problems. They are known to be incorporated in applications such as Siri, voice searching, Google Translate, natural language processing (nlp), etc.

LSTM is a type of RNN which can produce to remember outputs of each node and produce the next output efficiently. The reason for selecting LSTM is its ability to combat the RNN model’s vanishing gradient or long-term dependence issue. Gradient vanishing refers to loss of information in a neural network. LSTM tackles this issue by simply ignoring information which is useless for further processing.

The system works by training the LSTM model on a large dataset of music pieces. Once the model is trained, it generates new pieces of music by predicting the next note or sequence of notes based on the previous input notes. The output is processed to produce a finished piece of music in MIDI format.
