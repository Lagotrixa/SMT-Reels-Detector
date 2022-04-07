# SMT-Reels-Detector

Script to determine the bar and qr codes on the image. Codes can be placed at any angle, a mechanism for improving blurred areas has been added. In the code, paste your image name and the script will give you the data in the form of a csv file.
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
