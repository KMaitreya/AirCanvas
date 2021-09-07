# AirDraw
AirDraw is a python project involving machine learning and computer vision using which we are able to draw objects and erase them on a computer window using simple palm gestures. It consists of 2 stages-


a)Palm detection

In this stage the palm is detected using Google's mediapipe. It uses machine learning to track the movements of your palm using 21 reference points. It is made with the help of mediapipe(https://google.github.io/mediapipe/solutions/hands) a library built by google.

Download mediapipe with the following command- 

```
pip install mediapipe
```

The palm is tracked using 21 reference points. These reference points are predefined. The reference points are as follows-

![image](https://user-images.githubusercontent.com/47482433/121740885-5bd25a80-cb1b-11eb-8501-9270fb396746.png)


b)Drawing

In this phase the actual drawing takes place using palm gestures shown below. Drawing stage consists of three modes-

i)Pen down phase-

In this phase the user can actually draw in the window. Demonstation of pal gesture to activate the eraser phase is show in the image below. Only the index finger should be upright to activate the pen down mode.

<img width="478" alt="penup" src="https://user-images.githubusercontent.com/47482433/127768811-82ed5bf2-10ae-458a-9ec6-532cc41888af.png">

ii)Pen up phase-

In this phase no drawing or erasing takes place, you can moves your finger around the window to change the location of your pen down position. Demonstation of pal gesture to activate the eraser phase is show in the image below. Both the index finger and the middle finger should be upright to activate the pen up mode.

<img width="479" alt="pendown" src="https://user-images.githubusercontent.com/47482433/127768880-4870bd0f-9435-4b0a-b5d8-9d7c405c42c4.png">

iii)Eraser phase-

In the eraser phase you can erase previously drawn objects. Demonstation of pal gesture to activate the eraser phase is show in the image below. The index finger, the middle finger, the ring finger and the pinky should be upright to activate the eraser mode.

<img width="479" alt="eraser" src="https://user-images.githubusercontent.com/47482433/127768922-21cda401-aae1-48d6-992f-54a3257a8c69.png">



