# PyGO
PyGO: The easy way to send and receive files with Python.

Made using Tkinter library. 
This project was aimed to be a simple file transferring program with inspiration 
from AnyDesk and TeamViewer. It allows you to send files between two computers 
using a randomly generated ID/Password. Figma was used to make the UI. Big 
thanks to Parth Jadhav for designing Tkinter Designer for allowing me to extract 
my Figma UI creation and make it work in Python. The rest of the code for buttons, 
functions and logic are done by me. Project can be modded to transfer globally, 
but right now it is set to locally.

Note: The Project is in it's earliest stage of development. More changes may
      come in the future. Right now if you want to transfer between computers
      you need to know their IP address on the sender end of the code 
      (planning to make this feature automatic in the future).
      
Instructions: 
- The sender will open the sender.py file, run it, then a GUI will appear, 
copy the ID and password and send it to a friend/family via 
Discord/SMS/Anything. Next Open the file you want to  send, if you want 
to send multiple files then compress it into a zip file and open it that 
way. Click send.

- The receiver will open the receiver.py file and run it. In the GUI
paste the ID and password in their respective entry box. Next open 
the directory in where you want to save the file, then click receive.
After the file will be transferred into that folder you requested.

Note: You can also just click the purple button at the right bottom corner
      (Doesn't work on exe, not coded for that yet. Only works on python IDE.)
      which allows you to switch between sender and receiver. The ID/Pass
      will change everytime you do that though. Tested to work on a Windows computer
      right now.

That's it! It's as Simple as that and you can do this over and over <3.

