=== Kinect PowerPoint Control
Joshua Blake
Copyright © 2011-2012

This project shows how to use the Kinect SDK to do basic gesture recognition to control PowerPoint.

=== Requirements
•	Kinect for Windows SDK v1.0
Optional:
•	Microsoft Office PowerPoint 

=== History:
v1.1 Now updated for Kinect SDK v1.0. Speech recognition is on by default.
v1.0 Initial version.

=== Usage
1.	Compile and run the application 
2.	Point the Kinect at you and stand at least five feet away 
3.	You can see yourself in the application window and the three circles will track your head and hands. 
4.	Extend your right arm to activate the "right" or "forward" gesture. Extend your left arm to active the "left" or "back" gesture. These gestures will send a right or left arrow key to the foreground application, respectively. 
5.	Run your PowerPoint show so PowerPoint is the foreground application, and the right and left gestures will go forward and back in your deck.

The ellipses grow and change color when your hand exceeds the threshold of 45 centimeters. The gestures will only activate once as your hand exceeds the threshold, and only one of the gestures can be active at once. You must bring your hand back closer to your body to activate the gesture a second time.

The gestures will also work for any other application. For example, open Notepad and type some text then use the gestures to move the cursor left or right one character at a time.

=== Speech recognition

The speech recognizer is set up to recognize and respond to the following commands: 
•	computer show window 
•	computer hide window 
•	computer show circles 
•	computer hide circles

There is a four second delay after starting the program before the speech recognizer will respond.

=== Limitations
1.	There is currently no way to activate embedded videos, so you should add a PowerPoint animation so the video starts when you push the right arrow key. 
2.	The gesture is triggered based upon the distance between the head and the hands, so you might accidentally trigger the gesture if you put your arms out, or bend over to pick something up perhaps. 

=== Book
This code is a sample project from my book, Natural User Interfaces in .NET. If you want to learn more about how to design and develop NUIs, please check my book out. If you like this software, please buy my book to show your support and tell your friends! Thanks!

http://bit.ly/NUIbook 

Chapter 1 is free at that URL.

=== License
The source code is made available under the Ms-PL. 

http://kinectpowerpoint.codeplex.com/license
