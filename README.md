#Speech Recognition

This is basically a python code to execute simple tasks like playing or downloading youtube videos and peforming simple tasks like opening calculator,searching in google etc.

This uses Google speech recognition for recognising the audio and also uses that to get the id of the video you want to stream.I used  [pafy] to download the video with the video id I had found



##Requirements
* First you need to intall Python 2.7.You can [download] it here  
* Install python speech recognition library 
```sh
pip install SpeechRecognition
```
* Install Pyaudio
```sh
pip install pyaudio
```
* Install [pafy] to download YouTube content and retrieve metadata
```sh
pip install pafy
```
* Install lxml
```sh
pip install lxml
```
* Install requests
```sh
pip install requests
```
##List of commands
Given below are a list of commands you can speak
* Download video_name:
  Downloads the youtube video.The default storage location is "D:\songs".
  See the [source code] for changing the video qulity and default storage location

* Play video_name:
  Opens the video in the default webbrowser

* Open calculator and close calculator 
  For opening and closing calculator

* Open paint and close paint 
  For paint and closing paint

* google search_word
  Searches the text in google in  the default webbrowser 

[pafy]:<http://pythonhosted.org/Pafy/>
[download]:<https://www.python.org/downloads/>
