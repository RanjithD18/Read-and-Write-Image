# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:Ranjith D
### Register Number:212221240044
i) #To Read,display the image
```
import cv2
c=cv2.imread("test.jpg",1)
cv2.imshow("212221240044(Ranjith D)",c)
cv2.waitKey(0)
```
ii) #To write the image
```
import cv2
c=cv2.imread("test.jpg",1)
cv2.imwrite("1.jpg",c)
cv2.imshow("212221240044(Ranjith D)",c)
cv2.waitKey(0)
```
iii) #Find the shape of the Image
```
import cv2
c=cv2.imread('test.jpg',1)
print(c.shape)
```
iv) #To access rows and columns

```
import random
import cv2
c=cv2.imread("test.jpg",1)
for i in range(100):
    for j in range(c.shape[1]):
        A[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow("212221240044(Ranjith D)",c)
cv2.waitKey(0)
```
v) #To cut and paste portion of image
```
import cv2
c=cv2.imread("photo.jpg",1)
tag=c[20:100,20:100]
c[90:170,90:170]=tag
cv2.imshow("212221240044(Ranjith D)",c)
cv2.waitKey(0)
```

## Output:

### i) Read and display the image

<br>
<br>

### ii)Write the image

<br>
<br>

### iii)Shape of the Image

<br>
<br>

### iv)Access rows and columns
<br>
<br>

### v)Cut and paste portion of image
<br>
<br>

## Result:
Thus the images are read, displayed, and written successfully using the python program.


