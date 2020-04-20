# speech_recognition


the employees recognize customers’ emotions from speech, so they can improve their service and convert more people. In this way, they are using speech emotion recognition

What is Speech Emotion Recognition?
Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

SER is tough because emotions are subjective and annotating audio is challenging.

What is librosa?
librosa is a Python library for analyzing audio and music. It has a flatter package layout, standardizes interfaces and names, backwards compatibility, modular functions, and readable code. Further, in this Python mini-project, we demonstrate how to install it (and a few other packages) with pip.

What is JupyterLab?
JupyterLab is an open-source, web-based UI for Project Jupyter and it has all basic functionalities of the Jupyter Notebook, like notebooks, terminals, text editors, file browsers, rich outputs, and more. However, it also provides improved support for third party extensions.

To run code in the JupyterLab, you’ll first need to run it with the command prompt:
pip install librosa soundfile numpy sklearn pyaudio

Prerequisites
You’ll need to install the following libraries with pip:

pip install librosa soundfile numpy sklearn pyaudio
If you run into issues installing librosa with pip, you can try i


In this Python mini project, we learned to recognize emotions from speech. We used an MLPClassifier for this and made use of the soundfile library to read the sound file, and the librosa library to extract features from it. As you’ll see, the model delivered an accuracy of 72.4%. That’s good enough for us yet.