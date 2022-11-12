# About this project
This is the first part of the creation of a detection model of Android ransomware.
## APK Semi-automatic download
A script that uses Selenium for a semi-automatic .apk download to build benign sample dataset.
<br>
Needs a csv file as an input with the following structure:
```
apk-name
```
## APK validation
After the benign sample download, the sample validation is ran using bash and python, and the MobSF framework.
Run:
```
python3 nameFormat.py
python3 main.py # This one requires a personal API key.
```
## Important
This was part of a complete solution that can be found in https://github.com/vz000/RansomwareDetectionNSA-Android
