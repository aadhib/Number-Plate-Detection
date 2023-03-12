# Number-Plate-Detection
The Number Plate Detection and Recognition System is a computer vision project developed using Python 3.6, OpenCV 4.0.0, and Pytesseract. The system is designed to detect and recognize the license plates of vehicles captured in images or video footage. The project can be used for a variety of purposes, including automated toll collection, parking management, and law enforcement.

The system works by using computer vision techniques to first detect the license plate within the image or video frame. This is accomplished by analyzing the image for features that are characteristic of license plates, such as rectangular shapes with certain aspect ratios and color combinations. Once the license plate has been detected, the system then uses optical character recognition (OCR) techniques to extract the characters on the license plate and recognize the license plate number.

The OpenCV library is used to perform the image processing and computer vision tasks necessary for license plate detection and recognition. Pytesseract, a Python wrapper for the Tesseract OCR engine, is used for optical character recognition. Pytesseract allows the system to recognize the characters on the license plate and convert them into a text format that can be used for further processing and analysis.

Overall, the Number Plate Detection and Recognition System is a powerful tool for automating license plate recognition tasks. With its ability to accurately detect and recognize license plates in a variety of contexts, the system has the potential to significantly improve the efficiency and accuracy of a wide range of applications, from toll collection and parking management to law enforcement and security.

## Requirements
* Python 3.6
* OpenCV 4.0.0
* Pytesseract 

## Installation
1. Install python 

Click Here: https://www.python.org/downloads/ or https://www.anaconda.com/distribution/#download-section

2. Install OpenCV

```
pip install opencv-python
```

3. Install pytesseract

```
pip install pytesseract
```

4. Install Numpy

```
$ pip install numpy
```

5. Install pillow

```
$ pip install pillow
```
6. Run:
````
main.py
````
## Process
1. System captures the image and send to the preprocessing stage to enhance the quality of image.
![This is an image](xyz)
2. The process of RGB to Gray Scale Convertion has been done using threshold value. It is also known as Thershold image.
![This is an image](xyz)
3. Here localization process has been done through binary image convertion.
![This is an image](xyz)
4. Detecting the number plate using image processing technique.
![This is an image](xyz)
5. The alphanumerics of the number plate were detected and displayed using Optical Character Recognition technique.
![This is an image](xyz)
