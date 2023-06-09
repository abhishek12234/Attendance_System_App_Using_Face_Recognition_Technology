# Attendance System using Face Recognition

The Attendance System Using Face Recognition is a cutting-edge attendance management solution that leverages the power of machine learning and computer vision to accurately and efficiently track attendance in real-time. The system is built using Python and relies on the face_recognition library for face detection and recognition, as well as pandas for handling Excel files and updating attendance records.

One of the standout features of the Attendance System Using Face Recognition is its use of face liveness detection. This technology helps ensure that the faces being detected are real and not just static images or videos, which is a common challenge faced by traditional face recognition systems. By using a face liveness model, the system can more accurately identify and track attendance, making it ideal for use in high-security environments where accuracy is paramount.

The system also features a user-friendly graphical interface built using the tkinter library, which provides a simple and intuitive way to perform various attendance-related tasks. With just a few clicks, users can add new faces to the system, update attendance records, and generate detailed reports on attendance trends and patterns.


![Screenshot (168)](https://user-images.githubusercontent.com/117164257/233001988-b4ae2c70-87b4-48ac-90f5-9ae88efbe484.png) ![Screenshot (169)](https://user-images.githubusercontent.com/117164257/233002415-e07e2b74-48fc-4bdc-be74-b6c22d8da3e1.png)

![Screenshot (170)](https://user-images.githubusercontent.com/117164257/233002554-913c10a5-baf3-4cce-ab65-1e529125a1dc.png)


## Requirements


To run this project, you need the following software and libraries:

* Python 3.7 or higher
* face_recognition library (version 1.3.0 or higher)
* pandas library (version 1.3.0 or higher)
* OpenCV library (version 4.5.3 or higher)
* tkcalendar
* Tensorflow
* Keras
* Pillow
* numpy
* tkinter library (built-in with Python)

To install all the libraries, you can refer to the file requirments.txt which i have provided.

## Description

In major_project.zip file there are various files and folders:

1. The Major Project.py- this is the main file if you run this file your attendence system will start.

2. newfacedectect1.xml- this xml file is used to detect the face and draw bounding box when recognition face.

3. UI folder-  This folder consist of all the background images of different pages of application and the face liveness detection model

4. images folder- this folder will contain images of all the person who updated or added their record in the face recognition model so that whenever the model see their face next time it will recognition and mark their attendence.

5. deleted_per folder- this folder contain images of all the persons whos record has been deleted

6. data folder- this folder contain excel sheets of all 12 months to see present and absent status of all the persons whos record has been registered in the model.

7. admin image folder- this folder contain image of admin means only admin can delete the record of other person.

## Usage

1. download all the folders and files which is in major_project.zip and makes sure that you dont change any folder or file name and keep it as it is.

2. put all the folders and files in one folder as it was in major_project.zip.


## Acknowledgements

* The face_recognition library: https://github.com/ageitgey/face_recognition
* The pandas library: https://pandas.pydata.org/
* The OpenCV library: https://opencv.org/
* The Tensorflow library: https://www.tensorflow.org/
* The Keras library: https://keras.io/

## Made By


- Abhishek Jain- https://www.linkedin.com/in/abhishek-jain-59a760210
- Garima Patel- https://www.linkedin.com/in/garima-patel-58b656241




