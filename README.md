# EDGE-DETECTION
## Aim:
To perform edge detection using Sobel, Laplacian, and Canny edge detectors.
## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Import all the necessary modules for the program.
### Step2:
Load a image using imread() from cv2 module.
### Step3:
Convert the image to grayscale
### Step4:
Using Sobel operator from cv2,detect the edges of the image.
### Step5:
Using Laplacian operator from cv2,detect the edges of the image and Using Canny operator from cv2,detect the edges of the image.
## PROGRAM:
## DEVELOPED BY:PREM KUMAR K
## REGISTER NUMBER: 212222230111
## IMPORT PACKAGES AND LOAD IMAGES
  ```python
  canny=cv2.Canny(gray,120,150)
plt.imshow(canny,cmap='gray')
plt.title("Canny Edge Detector")
plt.axis("off")
plt.show()
```
## SOBEL EDGE DETECTOR:
## SOBEL X:
  ```python
  sobelx = cv2.Sobel(gray,cv2.CV_64F,1,0,ksize=5)
plt.imshow(sobelx,cmap='gray')
plt.title("Sobel X axis")
plt.axis("off")
plt.show()
```
## SOBEL Y:
```python
sobely = cv2.Sobel(gray,cv2.CV_64F,0,1,ksize=5)
plt.imshow(sobely,cmap='gray')
plt.title("Sobel Y axis")
plt.axis("off")
plt.show()
```
## SOBEL XY:
  ```python
  sobelxy = cv2.Sobel(gray,cv2.CV_64F,1,1,ksize=5)
plt.imshow(sobelxy,cmap='gray')
plt.title("Sobel XY axis")
plt.axis("off")
plt.show()
```
## LAPLACIAN EDGE DETECTOR:
```python
lap=cv2.Laplacian(gray,cv2.CV_64F)
plt.imshow(lap,cmap='gray')
plt.title("Laplacian Edge Detector")
plt.axis("off")
plt.show()
```
## CANNY EDGE DETECTOR:
```python
canny=cv2.Canny(gray,120,150)
plt.imshow(canny,cmap='gray')
plt.title("Canny Edge Detector")
plt.axis("off")
plt.show()
```
## Output:
## ORIGINAL IMAGE:
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/f28799ff-7f73-4e6d-9466-fa2042fdfcba)
### SOBEL EDGE DETECTOR:
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/bc8ed57e-5cf2-4833-b6d9-ea59d10e34f0)
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/86a92b10-0e69-4e0b-aadd-d734815522fa)
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/e0aaa41b-b4a4-4e66-8f1e-5d2e425435fd)
### LAPLACIAN EDGE DETECTOR
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/18b00b2d-dd9b-4cd9-9c1f-783a0c7ba616)
### CANNY EDGE DETECTOR
![image](https://github.com/gpavana/EDGE-DETECTION/assets/118787343/89255595-bc54-4582-8e30-be96f21d6e74)
## Result:
Thus the edges are detected using Sobel, Laplacian, and Canny edge detectors.
