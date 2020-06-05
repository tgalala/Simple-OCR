# OpenCV OCR and text recognition with Tesseract

<b>Language</b><br>
Python

<b>Description</b><br>
<b>Text detection: </b>OpenCV frozen east
frozen_east_text_detection.pb : The EAST text detector. This CNN  is pre-trained for text detection and ready to go. It is provided with OpenCV. (Download below) <br>
<b>Text recognition: </b> pytesseract engine

<b>Instruction</b><br>
Download frozen east text detection from:
https://raw.githubusercontent.com/oyyd/frozen_east_text_detection.pb/master/frozen_east_text_detection.pb

<b>Sample Result</b>
<br><center>
<img src="https://github.com/tgalala/Simple-OCR/blob/master/images/sample.png?raw=true" width="300">
</center>


<b>Usage</b><br>
Function can be run in command line example Anaconda Prompt or from Jupyter<br>
Example running script on command line:<br>
	1- move to the script's folder (..submission\ocr) <br>
	2- type :<br>
		python ocr.py --east frozen_east_text_detection.pb --image test/1.jpg   <br>
		python ocr.py --east frozen_east_text_detection.pb --image test/4.jpg --padding 0.25 <br>
	3- output is the input image with a red bounding box on the number labelled in text with that number. Also a report is printed in cmd with the number detected. 
  
  
<b>Credit</b><br>
www.pyimagesearch.com
