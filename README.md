# Chatbot
Know basics of python from this pybot
Run chat_gui.py to start 

# chat_gui.py
It is made of tinkter GUI. 

* if you are running this in linux or ubuntu: use "@*.xbm" 
* if you are running this in windows : use "*.ico"
but both of them are different files. you can not change the name to make it work.

Requirements:
1. python 3.6+
2. tkinter
3. pyttsx3
4. threading
5. nltk
6. numpy


# Screenshot:

![](https://github.com/soham1024/Chatbot/blob/master/Screenshot%20.png)

you can use different themes, different fonts.

This chatbot can speak if you are not getting any sound:
*  if you ar using linux: sudo apt-get update && sudo apt-get install espeak
*  if you are using ubuntu: sudo apt install libespeak1

Other than that, you can use
* sapi5 - SAPI5 on Windows
* nsss - NSSpeechSynthesizer on Mac OS X

like: pyttsx3.init(driverName='sapi5') 
