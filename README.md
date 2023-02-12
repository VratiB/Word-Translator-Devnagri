# Word-Translator
Create a word translator that translates English Word to Hindi

1. LSTM Word Translator Model
- Created a LSTM Model to translate English Word to Hindi Word
- Loaded the XML training file using the library xml.etree.ElementTree and extracted English words as input_texts and Hindi words as target_texts
- Tokenized the data using tensorflow.keras.preprocessing.text.Tokenizer(filters='')
- Created a sequential model using keras.Sequential() under the Tensorflow library
- Trained the model with loss as 'categorical_crossentropy' and Number of EPOCHS are 45 with batch_size of 128
- Model's Accuracy on Training data is 99%
- Loss on Training data is 0.16
- Tested the model on the Testing data using loss function as 'categorical_crossentropy'
- Loss on Testing data is 1.70
- Models accuracy on testing data is 0.86
- Python code file is uploaded as 'Word-Translation-LSTM-model'
- LSTM Model uploaded is 'LSTM-wordTranslator.h5'


2. RNN Word Translator Model
- Created a Seq2Seq RNN Word Translator Model to translate word from English to Hindi
- Created a LSTM Model to translate English Word to Hindi Word
- Loaded the XML training file using the library xml.etree.ElementTree and extracted English words as input_texts and Hindi words as target_texts
- Tokenized the data using tensorflow.keras.preprocessing.text.Tokenizer(filters='')
- Created a sequential model using keras.Sequential() under the Tensorflow library
- Trained the model with loss as 'categorical_crossentropy' and Number of EPOCHS are 40 with batch_size of 128
- Model's Accuracy on Training data is 99%
- Loss on Training data is 0.067
- Tested the model on the Testing data using loss function as 'categorical_crossentropy'
- Loss on Testing data is 1.78
- Models accuracy on testing data is 0.8644
- Python code file is uploaded as 'Word-Translation-RNN2'
- RNN Model uploaded is 'RNN-wordTranslator.h5'

CREDITS: ChatGPT
