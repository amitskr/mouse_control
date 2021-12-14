# Mouse_control
Control Mouse pointer using hand gestures

ABSTRACT

This project is a mouse simulation system which performs all the functions performed by your mouse corresponding to your hand movements and gestures. Simply speaking, a camera captures your video and depending on your hand gestures, you can move the cursor and perform left click, right click, drag, select and scroll up and down. The predefined gestures make use of only three fingers marked by different colors.

You are watching a movie with your friends on a laptop and one of the guys gets a call. You must get off your place to pause the movie. You are giving a presentation on a projector and need to switch between applications. You must move across the whole stage to the podium to use your mouse. How better would it be if you could control your mouse from wherever you were? Well, we have a solution!

The project is essentially a program which applies image processing, retrieves necessary data and implements it to the mouse interface of the computer according to predefined notions. The code is written on Python. It uses of the cross-platform image processing module OpenCV and implements the mouse actions using Python specific library PyAutoGUI. Thus, in addition to a webcam (which almost all laptops are already loaded with) a computer needs to be pre-equipped with the following packages for the project to run such as:
1. Python 2.7 interpreter
2. OpenCV
3. Numpy
4. PyAutoGUI
 

<b>AIM</b><br>
The project’s primary aim is to improve the scope of human and computer interaction by developing an effective alternative way of controlling the mouse pointer and its various functions such as left click, right click, scroll up, scroll down and selection. It helps user interact with the computer from a considerable distance without any issue and efficiently without actually touching the mouse. It also decreases the hardware requirement for the interaction by eliminating the necessity of a mouse. All the user needs is a web camera (which is mostly present in all laptops these days) which can record real-time videos. 


The system can be broken down in four main components, which are:



i.	Color detection

ii.	Color Contour Extraction

iii.	Hand Tracking

iv.	Gesture Recognition

v.	Cursor Control
