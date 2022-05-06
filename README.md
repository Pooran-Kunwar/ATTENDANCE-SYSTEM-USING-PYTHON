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

# screen-shots

 1. Homescreen :

![Homescreen](https://user-images.githubusercontent.com/94557457/167061209-7d9fa3d2-2946-48c6-9a44-a0d6bf67c0ca.png)

2. Enter Rollno and Name :

![add ID and Name](https://user-images.githubusercontent.com/94557457/167061415-df2848ba-7c74-4f96-8603-3424f928fe19.png)

3. Take Images :

![take images](https://user-images.githubusercontent.com/94557457/167061473-912d838e-e3e6-4a4c-bd9f-3363e038a3e0.png)

4. Save Profile :

![save profile](https://user-images.githubusercontent.com/94557457/167061545-0de54880-d2aa-41e8-80d2-8dc14133f05e.png)

5. Take Attendance :

![take attendance](https://user-images.githubusercontent.com/94557457/167061581-e10f50c2-6977-4507-8854-4d10b2ea53f9.png)

6. Attendance Lists :

![attendance list](https://user-images.githubusercontent.com/94557457/167061635-d0f26a0b-3dce-4a5e-8b67-be77a2c0f61f.png)

# thanks you 👍






