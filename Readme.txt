It is an interactive whiteboard in which you can save information you write on the whiteboard using a key and recall the information using the same key.

The zip folder contains all the codes.

Layout.py is the main code which calls the other codes on getting input from arduino.

Camera.py and the Camera2.py are the codes of t he two cameras. One is used for clicking the picture of key and the other is used for clicking the information related to that key.

tryinglens.py is the code used for converting the handwritten to text. It is using the API's of google lens.

Recall.py is the code activates when the recall button is presssed.

imageopen.py is the code for displaying the image whenever recall button is pressed.

sketch_mar03a(1).ino is the code of arduino.

Whiteboard-5860c17def84.json is the json file of the google lens.

KeynInfo.txt is the txt file which conains all the information about which key is related to which information.

serialMonitor(1).py is the code for taking input from arduino whenever reacall or new informaion button is pressed.
