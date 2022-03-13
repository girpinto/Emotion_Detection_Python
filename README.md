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

1. Click on search bar in Windows (if you can't see search bar on your Desktop click Windows button )
Type PowerShell in Search Bar
Then press Enter
After you opened the PowerShell, type:

We've already set-up a GitHub Pages website for you, based on your personal username. This repository is called `hello-world`, but you'll rename it to: `username.github.io`, to match your website's URL address. If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

Let's get started! To update this repository’s name, click the `Settings` tab on this page. This will take you to your repository’s settings page. 

![repo-settings-image](https://user-images.githubusercontent.com/18093541/63130482-99e6ad80-bf88-11e9-99a1-d3cf1660b47e.png)

Under the **Repository Name** heading, type: `username.github.io`, where username is your username on GitHub. Then click **Rename**—and that’s it. When you’re done, click your repository name or browser’s back button to return to this page.

<img width="1039" alt="rename_screenshot" src="https://user-images.githubusercontent.com/18093541/63129466-956cc580-bf85-11e9-92d8-b028dd483fa5.png">

Once you click **Rename**, your website will automatically be published at: https://your-username.github.io/. The HTML file—called `index.html`—is rendered as the home page and you'll be making changes to this file in the next step.

Congratulations! You just launched your first GitHub Pages website. It's now live to share with the entire world

## Making your first edit

When you make any change to any file in your project, you’re making a **commit**. If you fix a typo, update a filename, or edit your code, you can add it to GitHub as a commit. Your commits represent your project’s entire history—and they’re all saved in your project’s repository.

With each commit, you have the opportunity to write a **commit message**, a short, meaningful comment describing the change you’re making to a file. So you always know exactly what changed, no matter when you return to a commit.

## Practice: Customize your first GitHub website by writing HTML code

Want to edit the site you just published? Let’s practice commits by introducing yourself in your `index.html` file. Don’t worry about getting it right the first time—you can always build on your introduction later.

Let’s start with this template:

```
<p>Hello World! I’m [username]. This is my website!</p>
```

To add your introduction, copy our template and click the edit pencil icon at the top right hand corner of the `index.html` file.

<img width="997" alt="edit-this-file" src="https://user-images.githubusercontent.com/18093541/63131820-0794d880-bf8d-11e9-8b3d-c096355e9389.png">


Delete this placeholder line:

```
<p>Welcome to your first GitHub Pages website!</p>
```

Then, paste the template to line 15 and fill in the blanks.

<img width="1032" alt="edit-githuboctocat-index" src="https://user-images.githubusercontent.com/18093541/63132339-c3a2d300-bf8e-11e9-8222-59c2702f6c42.png">


When you’re done, scroll down to the `Commit changes` section near the bottom of the edit page. Add a short message explaining your change, like "Add my introduction", then click `Commit changes`.


<img width="1030" alt="add-my-username" src="https://user-images.githubusercontent.com/18093541/63131801-efbd5480-bf8c-11e9-9806-89273f027d16.png">

Once you click `Commit changes`, your changes will automatically be published on your GitHub Pages website. Refresh the page to see your new changes live in action.

:tada: You just made your first commit! :tada:

## Extra Credit: Keep on building!

Change the placeholder Octocat gif on your GitHub Pages website by [creating your own personal Octocat emoji](https://myoctocat.com/build-your-octocat/) or [choose a different Octocat gif from our logo library here](https://octodex.github.com/). Add that image to line 12 of your `index.html` file, in place of the `<img src=` link.

Want to add even more code and fun styles to your GitHub Pages website? [Follow these instructions](https://github.com/github/personal-website) to build a fully-fledged static website.

![octocat](./images/create-octocat.png)

## Everything you need to know about GitHub

Getting started is the hardest part. If there’s anything you’d like to know as you get started with GitHub, try searching [GitHub Help](https://help.github.com). Our documentation has tutorials on everything from changing your repository settings to configuring GitHub from your command line.
