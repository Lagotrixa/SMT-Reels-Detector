# SMT-Reels-Detector
[![Supported Python versions](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)](https://www.python.org/downloads/)

Script to determine the bar and qr codes on the image. Codes can be placed at any angle, a mechanism for improving blurred areas has been added. In the code, paste your image name and the script will give you the data in the form of a csv file.

## Installation
```
pip install -r requirements.txt
```
Change the name of the photo here
```
image = cv2.imread("IMAGE.jpg", cv2.IMREAD_GRAYSCALE)
```
Run!
```
./Detector.py
```

Resources: [Barcode reader](https://github.com/Dynamsoft/barcode-reader-python-samples/) , [Blurry qr-code](https://hackaday.com/2017/10/26/reconstructing-a-blurry-qr-code/), [QR reader](https://www.geeksforgeeks.org/reading-generating-qr-codes-python-using-qrtools/).
