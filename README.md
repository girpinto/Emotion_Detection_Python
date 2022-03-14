# Read this before to download and run the projet

Hi fellow coders! Before to dive in with the description of the project I suggest you to read this before. 

If you're experienced in Python (as I guess), well you can skip to [Run the code](#run-the-code) part. ***_But if not, please read this document_***. It' very important! Thanks 🙌

# Table of contents
1. [Emotion detection in Python](#emotion-detection-in-python)
      - [Project description](#project-description)
2. [Install Python](#install-python)
      - [How to check Python version on Windows](#how-to-check-python-version-on-windows)
      - [Install Python with Microsoft Store](#install-python-with-microsoft-store)
      - [How to install Python with the Full Installer](#how-to-install-python-with-the-full-installer)
3. [Before to run the project Emotion detection](#before-to-run-the-project-emotion-detection)
      - [Pycharm IDE Windows installation](#pycharm-ide-windows-installation)
      - [How to check pip version on Pycharm in Windows](#how-to-check-pip-version-on-pycharm-in-windows)
      - [How to check pip version installed on your Windows machine using the terminal](#how-to-check-pip-version-installed-on-your-windows-machine-using-the-terminal)
4. [Run the code](#run-the-code)
      - [OpenCV package](#opencv-package)
      - [DeepFace package](#deepface-package)
      - [Packages installation](#packages-installation)
      - [Brief description of components](#brief-description-of-components)
5. [References](#references)

# Emotion detection in Python

Welcome back, developers. In this repository I want to share with you my last project about Python. Currently I stopped my learning about Swift and started a new path in Python and in many other programming languages. 

Today I want to share the Emotion detection using Python, a very funny projects that allows you to become more skilled in python. 

Remember to follow me on my other social media, in this way you'll be updated every time I publish something new about Python. Below you'll find a list of my other social media.

Let's start!

## Project description

This project it was made completely in Python and it's basically a script which allows user to open the pc camera to detect the face and through an `.xml` file the script is able to recognize which emotion is on your face. 

The `.xml` file we will using it's `haarcascade_frontalface_default.xml` and you cnad it attached in the repository. It's one of the **haarcascades** data file that you can use with *cv2* package. 

The project was made by using **PyCharm** as **IDE**, but you can use whatever IDE you prefere or also the terminal. It's important to understand that if you want to run this project you should install **cv2** package, it doesn't matter if you install it in PyCharm or directly on you machine.

**Note**: This particular guide is intended for Windows users. I don't have a Mac. 

Below I'll explain how to install everything you need on your machine to run the project. 

# Install Python 

**Note** : We will install the newest version of Python on our machines, at the moment I’m writing this I’m using Python 3. Things can change (software developers know well this sh@!t), so in case there will be some changes I will post another guide.

To install **Python** on your machine and run the project directly from the terminal you should know that there are three methods to install Python on your machines, I will display all the methods here, than you can choose whatever method you prefer:

1. **The Microsoft Store** : This method involves installing Python from the Microsoft Store app. This is recommended for beginner Python users looking for an easy-to-set-up experience.
2. **The full installer** : This approach involves downloading Python directly from the [Python.org website](https://www.python.org/). This is recommended for intermediate and advanced developers who need more control during the setup process.
3. **Windows Subsystem for Linux** : The WSL allows you to run a Linux environment directly in Windows. If you don’t know how to enable the WSL on your Windows PC you can check the [Microsoft Documentation on Installing WSL on Windows](https://docs.microsoft.com/it-it/windows/wsl/install).

**Note**: In this section, we’ll focus on only the first two options, which are the most popular installation methods in a Windows environment.

Before to install Python let’s check if we already have Python on our Windows machine.

## How to check Python version on Windows 

First let’s open the Terminal.

1. Click on search bar in Windows (if you can't see search bar on your Desktop click **Windows button ⊞**)
2. Type *cmd* in Search Bar
3. Then press *Enter*
4. After you opened the Terminal type: 

```
python --version
```

The `--version` switch will allows you to check what version of Python is installed on your machine. In either case, if you see a version less than 3.10, which was the most recent version at the time of writing, then you’ll want to upgrade your installation.

If you have Python on your machine, the result should be:

<img width="680" alt="cattura1" src="https://user-images.githubusercontent.com/56441252/158163117-a6793166-1e94-4e4a-8665-787a1bc9daa8.PNG">

**Note: If you don’t have a version of Python on your system, the above command will launch the Microsoft Store and redirect you to the Python application page. You’ll see how to complete the installation from the Microsoft Store in the next section.**

###### Bonus

If you’re interested in where the installation is located, then you can use the `where.exe` command, in this way:

```
where.exe python
```

The result should be: 

<img width="678" alt="cattura2" src="https://user-images.githubusercontent.com/56441252/158163529-20496551-254c-4c6a-b115-538cad8390e2.PNG">

**Note: Remember that the where.exe command will work only if Python is installed on your machine.**
**Note: Remember that the terminal commands are case sensitive and space sensitive use spaces or upper/lower cases where needed.**

## Install Python with Microsoft Store

The official Python documentation has this to say about the Microsoft Store package:

> The Microsoft Store package is an easily installable Python interpreter that is intended mainly for interactive use, for example, by students. [(Source)](https://docs.python.org/3/using/windows.html#the-microsoft-store-package)

The key takeaway here is that the Microsoft Store package is “intended mainly for interactive use.” That is, the Microsoft Store package is designed to be used by students and people learning to use Python for the first time.

To install Python with Microsoft Store, follows these two easy steps:

1. Open the **Microsoft Store** app and search for `Python`.

![1_WbTRsaU5zPbsEP1b1KoCyw](https://user-images.githubusercontent.com/56441252/158164198-1a60ca16-6bf0-44de-8de0-f2e8e312c9fa.png)

As you can see you can choose among multiple versions.

Select Python 3.10, or the highest version number you see available in the app, to open the installation page.

**Warning**: Make sure that the Python application you’ve selected is created by the **Python Software Foundation**. The official Microsoft Store package will always be free, so if the application costs money, then it’s the **wrong** application.

**Note**: if you don't have Python on your machine, you can get access the **Microsoft Store** by opening the Terminal and typing `python` , in this way you will open the Microsoft Store on the latest version of Python.

2. Install the **Python** app

After you’ve selected the version to be installed, follow these steps to complete the installation:

1. Click *Get*.
2. Wait for the application to download. When it’s finished downloading, the *Get* button will be replaced with a button that says *Install on my devices*.
3. Click *Install on my devices* and select the devices on which you’d like to complete the installation.
4. Click *Install Now* and then *OK* to start the installation.
5. If the installation was successful, then you’ll see the message “This product is installed” at the top of the Microsoft Store page.

Congratulations! You now have access to Python, including [pip](https://www.w3schools.com/python/python_pip.asp) and [IDLE](https://docs.python.org/3/library/idle.html)!

## How to install Python with the Full Installer

Follow these steps to download the full installer:

1. Open a browser window and navigate to the Python.org [Downloads page for Windows](https://docs.microsoft.com/it-it/windows/wsl/install).
2. Under the “Python Releases for Windows” heading, click the link for the *Latest Python 3 Release — Python 3.x.x*. As of this writing, the latest version was Python 3.10.
3. Scroll to the bottom and select either *Windows x86–64 executable installer for 64-bit* or *Windows x86 executable installer for 32-bit*.

When the installer is finished downloading, run the installer.

![1_NrenptSg1Qd0cZY1JWD1yQ](https://user-images.githubusercontent.com/56441252/158165465-655db60a-0b13-4e13-9f15-6522d690e191.png)

The full installer gives you total control over the installation process. 

Then click *Install Now*. That’s all there is to it!

Congratulations, you now have the latest version of Python 3 on your Windows machine! 🎉 🎉

Now stop with the boring part and let's start to code.

# Before to run the project Emotion detection

Now that you have Python 3 on your Windows machine, you can run it, but before to download this project you need an **IDE (Integrated Developement Environment)**.

To bring to life this script I used **PyCharm IDE**. I think that's a good IDE and gives you a lot of control on your project. 

Let's jump to install the IDE.

## Pycharm IDE Windows installation

Since PyCharm is a computer program we need to install it on our machine, so follow these easy steps to install it fast:

1. Go to [JetBrains website](https://www.jetbrains.com/pycharm/download/#section=windows).
2. Click on Download button under **PyCharm Community Edition** tab.
3. Wait for download…
4. Click on downloaded `.exe` file in your *Download* folder and install *PyCharm Community* on your machine.

![1_2edVFK2mABhn43gPhUTTJA](https://user-images.githubusercontent.com/56441252/158167488-9e2dda49-77ee-4f01-b556-bccc8ab66e26.png)

Click on PyCharm Community Edition icon and start the IDE.

Once you opened the program, click on *File*, in the upper left corner, then in the drop down menu click on *New Project…* . 

You’ll see this window:

![1_hmsZ3NLqrA1AYexOOamFpg](https://user-images.githubusercontent.com/56441252/158167601-cc653728-6ec4-4de7-8080-bda19251147a.png)

As *Location* choose the location you prefer, in location part if you change the last part of the path you change also the name of the project, in my case I will name the project *EmotionDetection*. The *Virtualenv* is the virtual environment of **PyCharm**, it’s perfect for now. As *Base interpreter* choose the most updated version of Python, you can check it by looking at the path, in my case is *Python310*, that stands out for Python 3.10 (at the time of writing Python 3.10 is the most recent version). Last, check the *Create a main.py welcome script* option. 

When you’ve done, the PyCharm window shoul look like this:

![1_mpyt_IdtiEY9sQft-mFJkg](https://user-images.githubusercontent.com/56441252/158167929-a34a5cbf-5bed-4ee8-b263-c5fddf56bce6.png)

PyCharm it's very easy to understand. On the left you can find the *Project Navigator* named just *Project*. Here you can find all the folders you need or you will add to your project. In the project folder there's also the ***main.py*** file, it's your starting file. Here you will write your code. You can rename it if you want, you just should ***Right click*** on it to open the dropdown menu. Here you will see a bunch of options, go to **Refactor** option, then on **Rename...** and type the name you want. 

![Screenshot (1)](https://user-images.githubusercontent.com/56441252/158169321-c8512a78-524f-4653-b133-c9671779bb92.png)

Down on PyCharm window, you can see some other options like: **TODO**, **Problems**, **Terminal**, **Python Packages** and **Python Console**. For now you need the Problems tab, where you can see some issues in your code, and Python Packages, where you can download various packages in Python to run your projects. 

<img width="421" alt="cattura3" src="https://user-images.githubusercontent.com/56441252/158192664-8f134abe-1405-48c3-ba1d-72ead78c9fe0.PNG">

These tabs are very helpfull. For example:

- **TODO** tab lets you add special types of comments that are highlighted in the editor, indexed, and listed in the TODO tool window. This way you and your teammates can keep track of issues that require attention.
- **Problems** tab window displays problems that PyCharm detects in your project using several tabs: **Current file**, **Project Errors**, **Inspection Results**. You can select any problem in the window and press `F4` or double-click any problem to jump to the corresponding line in the editor.
- **Terminal** tab: use it to run Git commands, set file permissions, and perform other command-line tasks without switching to a dedicated terminal application.
- **Python packages** tab provides a list of possible packages that can be installed to perform some particular actions in your code
- **Python console** tab Python console enables executing Python commands and scripts line by line, similar to your experience with Python Shell.

Now, there's just a last thing to check: the **pip**.

This is basically something that you should do every time, because the pip just as like as Python can be updated in the meanwhile, so we should check if we have the latest version. I'll dedicate it a section.

## How to check pip version on Pycharm in Windows

1. Open project settings (*File -> Settings...*)
2. *Project -> Python Interpreter*
3. Press the **+** button
4. Type *pip* in the top search box
5. In the lower right corner choose *specify version*
6. Choose the latest version and press **Install Package**

![Screenshot (4)](https://user-images.githubusercontent.com/56441252/158204645-54b4c9b0-2fd9-432b-a808-17511ba92db5.png)

## How to check pip version installed on your Windows machine using the terminal

If you're struggling with the pip installed on your Windows machine, this section can be helpful for you.

**Note**: skip this if you don't need to check pip version on your Windows machine

In order to upgrade PIP in Windows, you’ll need to follow these steps.

1. Open the Windows **Command Prompt**.
2. You'll see something like : `C:\Users\topogigio>`, type `where.exe python`, in order to locate foldere where Python was installed and press **Enter**.
3. Copy the first path
4. You now should be able to write again in the **Command Prompt** and you should see something like: `C:\Users\computername>`, after the arrow type `cd\`, in this way your starting point is the drive name.
5. Press **Enter** and you should see something like: `C:\>`
6. Now type `cd`, then give **one** space with space bar and paste the path you copied before, the path related to Python installation folder and press **Enter**
7. Now you should be able to see something very similar to the path you copied before. To upgrade the pip type/copy the command below:

```
python -m pip install --upgrade pip
```

The **Command Prompt** window should look like this: 

<img width="530" alt="cattura4" src="https://user-images.githubusercontent.com/56441252/158208195-8d8e2917-de92-4e23-bcb8-6d85445dd7ab.PNG">

Press **Enter** and wait for the message: `Successfully installed pip-2x.x.x`.

**Note**: The x stands for the version number, I don't know when you upgrade the pip version so my version could be different from yours.

Congratulations, you've set it up and you're ready to run the project! 🎉🎉🎉

# Run the code

In the repository you'll find all the material you need, but before to proceed with the analysis of the content I suggest you to install few packages in order to run the code correctly.

Since the project use two different packages. it's crucial that you install them, otherwise the code won't run. 

The packages imported in this project are: **OpenCV** and **deepface**.

## OpenCV package

OpenCV is the huge open-source library for **computer vision**, **machine learning**, and **image processing** and now it plays a major role in real-time operation which is very important in today's systems.

In the project you'll see that I wrote `import cv2`, well for those who are not experienced in Python, OpenCV-Python is the library of Python bindings designed to **solve computer vision problems** and cv2 (**old interface** in old OpenCV versions was named as cv ) is the name that OpenCV developers chose when they created the binding generators.

## DeepFace package

DeepFace is a deep learning facial recognition system created by a research group at Facebook. It **identifies human faces in digital images**. The program employs a nine-layer neural network with over 120 million connection weights and was trained on four million images uploaded by Facebook users.

## Packages installation

In order to install these packages in our project, follow these steps:

1. Go to **Python packages** tab
2. A panel with a search box will appear, type in the search box *opencv* and click the *Install* button on the right of the panel 
3. Wait for the installation

![Screenshot (5)](https://user-images.githubusercontent.com/56441252/158234828-e70c7e6d-d6e2-4cb7-9022-5ff957235e49.png)

4. Then in the same search box type *deepface* and install it in the same way.

![Screenshot (3)](https://user-images.githubusercontent.com/56441252/158203254-ec15f949-fc24-4a12-958a-4c5d7ca90e30.png)

Once you've done you can easily run the code. 

## Brief description of components

The project run the camera of your machine in order to recognize your face and detect the emotion. It's pretty accurate. It creates a square around your face and put a text where there's the emotion detected. 

In order to create the square I used the `cv2.rectangle()` method from `OpenCV` in this way: 

```python
while video.isOpened():
    _, frame = video.read()
    
    gray = cv2.cvtColor(frame, cv2.COLOR_BGR2GRAY)
    face = face_cascade.detectMultiScale(gray, scaleFactor=1.1, minNeighbors=5)
    
    for x, y, w, h in face:
        image = cv2.rectangle(frame, (x, y), (x + w, y + h), (89, 2, 236), 1)
        ...
```

**cv2.rectangle()** method is used to draw a rectangle on any image. 

- **Syntax**: *cv2.rectangle(image, start_point, end_point, color, thickness)* 
- **Parameters**:
    - **image**: It is the image on which rectangle is to be drawn.
    - **start_point**: It is the starting coordinates of rectangle. The coordinates are represented as tuples of two values i.e. (X coordinate value, Y coordinate value).
    - **end_point**: It is the ending coordinates of rectangle. The coordinates are represented as tuples of two values i.e. (X coordinate value, Y coordinate value).
    - **color**: It is the color of border line of rectangle to be drawn. For BGR, we pass a tuple. eg: (255, 0, 0) for blue color.
    - **thickness**: It is the thickness of the rectangle border line in px. Thickness of -1 px will fill the rectangle shape by the specified color.
- **Return value**: It returns an image.

The OpenCV package provides a training method (see [Cascade Classifier Training](https://docs.opencv.org/3.4/dc/d88/tutorial_traincascade.html)) or pretrained models, that can be read using the **cv::CascadeClassifier::load** method.

In this project I used it so: 

```python
face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + "haarcascade_frontalface_default.xml")
```

*haarcascade_frontalface_default.xml* : **Detects faces**.

There are a lot of trained models that you can add to your project to make it more accurate. See this [link](https://github.com/opencv/opencv/tree/master/data/haarcascades).

To analyze the emotion detected on the face the script was made by using a **try-except** block, in order to launch an exception whenever the video opening fails: 

```python
    ...
        try:
            analyze = DeepFace.analyze(frame, actions=['emotion'])
            cv2.putText(image, analyze['dominant_emotion'], (x, y), cv2.FONT_HERSHEY_SIMPLEX, 1, (224, 77, 176), 2)
            print(analyze['dominant_emotion'])
        except:
            print('no face')
    ...
```

Last but not least, remember to release the video and destroy all the windows: 

```python
video.release()
cv2.destroyAllWindows()
```

This will improve a lot the output of your code. 

Thanks for reading!! 🎉🎉🎉

# References

- [GeeksForGeeks](https://www.geeksforgeeks.org/)
- [Pypi.org](https://pypi.org/project/opencv-python/)
- [DataToFish](https://datatofish.com/upgrade-pip/)
- [OpenCV documentation](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)
