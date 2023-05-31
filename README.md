# SnapAccess

![alt text](https://github.com/Daniel0Marsh/SnapAccess/SnapAccess/image/logo_black.png)

### Table of contents
* [Introduction](#introduction)
* [General info](#general-info)
* [Features](#features)
* [Technologies](#technologies)
* [Install](#install)
* [auto-py-to-exe](#auto-py-to-exe)

### Introduction
Introducing SnapAccess, an innovative desktop application meticulously crafted for the Microsoft Windows operating system (OS). This automation-driven powerhouse is engineered to revolutionize productivity and maximize time efficiency. By harnessing the remarkable capabilities of SnapAccess, users are empowered with the seamless ability to effortlessly launch multiple applications, open files, access web addresses, and explore directories simultaneously. Experience a quantum leap in productivity and unlock newfound efficiency with SnapAccess - your gateway to streamlined multitasking and elevated performance.

### General Information
SnapAccess, the groundbreaking productivity application, is an open-source project written in Python, leveraging the power of the Kivy 2.0.0 Python package. This unique combination allows for a seamless user experience, rich functionality, and cross-platform compatibility. The open-source nature of SnapAccess encourages collaboration and community involvement, enabling users and developers to contribute, customize, and enhance the application. Python, known for its simplicity and versatility, forms the robust foundation of SnapAccess, while the Kivy 2.0.0 package provides a dynamic and intuitive user interface. Embrace the open-source spirit and experience the limitless potential of SnapAccess as it revolutionizes the way you work.

### Features
- Seamlessly open multiple files simultaneously, revolutionizing your workflow.
- Effortlessly access and explore multiple directories with just a few clicks.
- Launch a multitude of applications at once, unleashing your productivity potential.
- Instantly open multiple web addresses, saving you valuable time and effort.
- Personalize four customizable buttons to effortlessly open or launch applications, files, directories, and web addresses in one go.
- Enjoy the flexibility to open or launch up to 10 different applications, files, directories, and web addresses simultaneously, tailoring your multitasking experience to perfection.
- Safeguard your data and privacy with an optional password feature, ensuring only authorized access.
- Opt for automatic application closure after use, streamlining your workflow and minimizing clutter.

### Technologies
- python 3.9.7
- Kivy 2.0.0

### Install
#### Step 1
- download the SnapAccess folder
- store the folder anywhere on your Microsoft Windows machine
#### Set 2
- inside the SnapAccess-app directory locate the file named main.exe
- this will be the only .exe file with the SnapAccess icon
#### step 3
- create a shortcut of the file and rename it SnapAccess
- pin the shortcut to your taskbar and start menu

### auto-py-to-exe
These steps are for those who downloaded the file named 'SnapAccess' for debugging reasons
#### Step 1 (RECOMENDED)
- use the latest version of python see https://www.python.org/downloads/

#### Step 2 (RECOMENDED)
- use a virtual environment for step 3 see https://docs.python.org/3/library/venv.html for instructions on creating a python virtual environment or  https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html for instructions on creating a Anaconda virtual environment


#### Step 3
- install pyinstaller using the command `$pip install pyinstaller` in the console  
- install Kivy 2.0.0 using the command `$python -m pip install kivy[FULL]` in the console
- install auto-py-to-exe using the command `$pip install auto-py-to-exe` in the console
- run auto-py-to-exe using the command `auto-py-to-exe` in the console

#### Step 4
- a web based page will open
- use the browse button at the top of the page to select the main.py file location
- sellect the options 'One Directory' and 'Window based(Hide the console)
- go to 'ICON' and use the browse button to sellect the application icon locatted at C:/your/location/SnapAccess/image/logo.ico
- go to 'Add files' and add all the files in the SnapAccess directory excluding the main.py file
- go to 'Add files' and add the image folder located in the SnapAccess directory
- go to setting 'Output directory' and sellect your desired location
- duoble check all the above and press the 'CONVERT .PY TO .EXE' button
- go to C:\your\chosen\dir\Output\main and locate the main.exe file with the SnapAccess icon
- create a shortcut of the main.exe file and rename it SnapAccess
- pin the SnapAccess file to your taskbar and start menu
