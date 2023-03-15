# Lab-5_202001012



# Prakarsh Mathur

# 202001012






Tool Used: Mypy

# Repository 1

https://github.com/prateekralhan/Python-based-Youtube-downloader

# Error:
<img src="https://user-images.githubusercontent.com/96994497/225279155-5e7597e6-0fd8-4527-b29e-ebe0e935258e.png" width="1004" height="306">


# Line of errors:

1. from pytube import YouTube, exceptions


2. from customtkinter import *


3. set_appearance_mode("System")


4. set_default_color_theme("blue")


5. master = CTk()


6. CTkLabel(master, text="Enter YouTube video URL:").grid(row=0, column=0)

7. entry = CTkEntry(master)


8. CTkButton(master, text='Download', command=lambda *args: download_video(entry.get())).grid(row=1, column=0, columnspan=2)

# Understanding:
The library was not installed on the pc. Which lead to the errors.

# Repository 2

https://github.com/binjolaaman10/python-file-manager

# Error:
<img src="https://user-images.githubusercontent.com/96994497/225278549-19e978e2-9198-40dd-aa60-5131b1d5be15.png" width="873" height="215">

# Line of errors:

1. import send2trash

# Understanding:
The library was not installed on the pc. Which lead to the error.

# Repository 3

https://hackr.io/blog/python-projects

# Error:
<img src="https://user-images.githubusercontent.com/96994497/225281259-2d25835d-7fe8-480c-a1c2-fb83e1e39bda.png" width="1186" height="528">

# Line of errors:

1. from nltk.tokenize import word_tokenize

2. import pandas as pd

3. import nltk

4. from nltk.corpus import stopwords

5. binary_actors[k].append(1.0) 

6. binary_actors[k].append(0.0)



# Understanding:
The library was not installed on the pc. Which lead to the error.

Argument type incompatibility.

# Repository 4

https://github.com/Mrinank-Bhowmick/python-beginner-projects/tree/main/projects/JARVIS.PY

# Error:
<img src="https://user-images.githubusercontent.com/96994497/225285509-442be81f-ef33-42a2-9167-1aa9b0491170.png" width="895" height="264">

# Line of errors:

1. import pyttsx3 

2. import speech_recognition as sr 

3. import wikipedia

4. import pyjokes

5. Listener = sr.Recognizer()

6. jarvis()



# Understanding:
The library was not installed on the pc. Which lead to the error.

A variable not defined.

Miscellaneous.

# Conclusion
Mypy is a tool which can catch many programming errors by analyzing your program, without actually having to run it.

