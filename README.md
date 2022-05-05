# attendance-system-using-python.

A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. 
I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. 
GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:

 1. tkinter for whole GUI
 2. OpenCV for taking images and face recognition.
 3. CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:

 1. Easy to use with interactive GUI support.
 2. Creates/Updates CSV file for deatils of students on registration.
 3. Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
 4. Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

# how-it-work

When we run main.py a window is opened and ask for Enter Id and Enter Name.

After enter name and id then we have to click Take Images button. 

By clicking Take Images camera of running computer is opened and it start taking image sample of person.

This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 100 images as sample and
store them in folder TrainingImage.

After completion it notify that images saved.

After taking image sample we have to click Take Attendance button.Now it take few seconds to train machine for the 
,images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.

By clicking Take Attendance button camera of running machine is opened again. If face is recognised by system then 
Id and Name of person is shown on Image.

Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with 
name, id, date and time and it is also available in window.

# thanks you 👍
