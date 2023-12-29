Threatening Calls Alert System:

This project aims to detect threatening content in audio calls and send a message through WhatsApp
using PyWhatKit if any threatening content is detected. It utilizes the PyAudio library to capture
audio input, converts it into text using the SpeechRecognition library, and employs machine learning
models such as Logistic Regression, Decision Tree, Random Forest, and Multinomial Naive Bayes to
determine the presence of threatening content based on a trained dataset.

Repository Contents:

Dataset File (final_dataset.csv): The final_dataset.csv file is a manually created dataset used to train the models. 

Code File(Threatening_Call_Alerter.ipynb): The code file in this repository contain the source code used to perform various tasks in the project.

Report File: The report file provides a detailed overview of the project, including the objectives, methodology, and results. This document is essential for understanding the context and outcomes of the project.

phywhatkit_DB File: This file in this repository contain the details regarding the whatsapp messages sent by the code.

Please refer to the files for more specific details about their contents and how they contribute to the overall project.

Installation

1. Download the jupyter source code file which contain all the code.

2. Install all the required libraries.

3. Make sure you have a WhatsApp account and have installed the WhatsApp application on your
device.

Usage

1. Run the Threatening_Call_Alerter.ipynb file in jupyter notebook.

2. When prompted, start recording audio from your default audio input device using PyAudio.

3. Once the audio recording is complete, the script will convert the audio into text using the
SpeechRecognition library.

4. The obtained text will be processed by the machine learning model (Logistic Regression, Decision
Tree, Random Forest, and Multinomial Naive Bayes) with high accuracy to determine the presence of
threatening content.

5. If the model predict the presence of threatening content, a message will be sent through
WhatsApp using PyWhatKit and PyWhatKit_DB file will be created. Make sure you have a stable internet connection and your device is connected to your WhatsApp account.

Configuration

You can customize the project by modifying the following parameters in the threaten_call_alert.ipynb file:

- Model used for predicting: You can customize the model used for predection of the text with a
different machine learning model of your choice that is present in the code.

- Whatsapp Contact: The phone numbers of the recipient for sending the WhatsApp message should be added. Make sure to include the country code.

Please note that this project assumes you have access to a trained dataset for the machine learning
models and have already trained and saved the models using libraries like scikit-learn. 

Acknowledgments

This project relies on the following libraries and resources:

[PyAudio](https://people.csail.mit.edu/hubert/pyaudio/): Used to capture audio input.

[SpeechRecognition](https://github.com/Uberi/speech_recognition): Utilized to convert
audio into text.

[scikit-learn](https://scikit-learn.org/): Used for training and utilizing machine learning
models.

[PyWhatKit](https://github.com/Ankit404butfound/PyWhatKit): Enables sending WhatsApp
messages through code.

Please refer to the documentation and licenses of these libraries for more information.

Disclaimer

This project is intended for educational and informational purposes only. The effectiveness of threat
detection may vary, and it is not guaranteed to detect all threatening content accurately. Use the
results with caution and rely on human judgment in critical situations. The developers and
contributors of this project are not responsible for any consequences arising from the usage of this
code.

