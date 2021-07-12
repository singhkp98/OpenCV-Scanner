# OpenCV-Scanner
Simple document scanner in C++ using OpenCV library

This repository contains a C++ project implemented using the OpenCV library. 

The application will receive an image as input containing the document to be scanned and will: 
- define the region of interest excluding all elements not necessary
- contour the document
- crop the document
- convert the document in black and white (to make it look as a scan)
- save the document in a specific folder in order to retrieve it 

![Alt text](https://user-images.githubusercontent.com/80750958/125322269-dfab7c80-e33d-11eb-8a0c-37364f007813.jpg)

