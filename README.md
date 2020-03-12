# FaceRecognition_based_AttendanceSystem

It has two files- setup.ipynb and train.ipynb
When we run the train.ipynb, a window is opened that contains a notification bar and different buttons for taking images, train model and recognize the face and quit. It has following steps-

1) First, the user has to enter the enrollment number & name
2) Click the 'Take Image' button. After clicking the camera will open and take 60 sample images of a person and creates a dataset. It stores all the images in the 'TrainingImage' folder and makes an entry in the 'StudentDetails.csv' file
3) Then click 'Train Image' button. It will train the model with the current image dataset. It will take a few seconds and put a notification 'Image Trained' in the notification bar. It creates a 'Trainner.yml' file and store in the 'TrainingImageLabel' folder.
4) All the initial steps are done. Now click on the 'Track Image' button, it will open the camera and start recognizing the face. if the face is recognized then the enrollment number & name are shown on the face.
5) When we press 'Q' or 'q'  the window is quit and attendance is stored in the Attendance folder in the form of a csv file with current_date and time.
6) The recognized person's enrollment number & name are shown in the 'Attendance' bar.

That's how the whole software work.
