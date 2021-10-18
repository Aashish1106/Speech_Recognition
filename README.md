# Speech_Recognition

**Documentation:**

**How does speech recognition work?**

First, internally the input physical audio will convert into electric signals. The electric signals convert into digital data with an analog-to-digital converter. Then, the digitized model can be used to transcribe the audio into text.

**Modules used:-**

**Speech Recognition Module:** It is a library with the help of which Python can recognize the command given. We have to use pip for Speech Recognition. 
 
**PyAudio Module:** It is a set of Python bindings for PortAudio, a cross-platform C++ library interfacing with audio drivers. We need to also install Pyaudio as the Speech Recognition module is dependent on it.

**Installation:-**

(we are using Windows Command Prompt as example, user can try different examples)

Installing the Python Speech Recognition Module:

       pip install SpeechRecognition

Audio files that support speech recognition are wav, AIFF, AIFF-C, and FLAC.
 
Installing the PyAudio Module:

       pip install PyAudio

If the above command doesn’t work in windows then use the below commands in the windows command prompt:

       pip install pipwin

       pipwin install pyaudio


We will be using Google Speech Recognition API for letting the software understand our given languages

https://cloud.google.com/speech-to-text/docs/languages

**Accuracy:- **

The reliability of speech-to-text hinges on its accuracy rate – i.e., how many errors it would contain on an average. This is measured in Word Error Rate (WER) which is the percentage of errors for every 100 words. Technically, accuracy is the exact inverse of WER; if a piece of transcribed text contains 2% of errors, then it means that it is 98% accurate.
As per benchmarks published in March 2020, Google came in at 79% and a May benchmark found Google largely the same at 84.46%.
