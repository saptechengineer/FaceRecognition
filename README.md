# FaceRecognition
Face Recognition using OpenCV and Python (PIL)

## Requirement
- Python 3.5 and above
- OpenCV 3.1.0 and above
- Numpy

## Install Libraries:
* pip install tensorflow
* pip install opencv-python
* pip install pillow
* pip install opencv-contrib-python

## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)
2. Train the model (training.py)
3. Face Recognition (face_recognition.py)

## How to Run:
1. Run "face_datasets.py" to generate the dataset of faces. Set unique name (like "User.1.1", "User.1.2", "User.1.3" for one person's face). Just increament "face_id = " for each person's face.
2. Run "training.py" to train your dataset.
3. 'datasets' and 'trainer' folders will be created automatically.
4. Finally run "face_recognition.py".
