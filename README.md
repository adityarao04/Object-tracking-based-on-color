# Object tracking based on color
object tracking based on color using OpenCV

this is a part of my 30 day journey to learn Artificial Intelligence by doing practical projects.
On my 6th day I made this project.

If you are using any other external webCam, in main.py on line 7: camera = cv2.VideoCapture(0) change the value passed to VideoCapture from 0 to 1 or 2.




### 1.setting up the HSV value using colorCalibrationforHSV.py(this will be according to your color)

the values that make the object appear totally white will be the correct values

![](Images/ColorCalibrationHSV.JPG)




### Output

the output will display a frame where object is being tracked and its position will be displayed in the console

![](Images/output.JPG)

