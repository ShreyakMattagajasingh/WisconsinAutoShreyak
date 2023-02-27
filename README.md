# WisconsinAutoShreyak
Answer
![answer](https://user-images.githubusercontent.com/123520907/221480349-de103fa6-a54c-4cb6-b569-ed95d1cef415.png)

Methodology

I have converted the image to hsv, then used it to extract red colors. 
I then found contours using cv2 find contours method.
I filtered the data to my find all cones and remove all of the extra noise from the backgroud.
I then found the x and y points (rect function using cv2) of all the cones and made smart sets by filtering data to be the left and the right side of cones.
Then used slope and point formula to produce a line passing through the cones.


What I tried

Tried making specifically designed contours for only cones but did not work out for now.
Make line using fitline but line worked better 

Libraries used:

open cv,
numpy,
pandas,
matplotlib ,
