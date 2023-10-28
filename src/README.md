# Terminal_app_T1A3

## Statement of Purpose

"Catering Services for your party" This is an application that is a food catering planning guide for users.
The final quote changes depending on the user's selections, and the user can confirm their selections on the final screen.

The purpose of this application is to represent skills in utilizing all operational system functions.

It is a requirement to accept user input and produce printed output or interact with the file system

## Target Audience

The application is designed to be relatable to a wide range of age groups so that anyone can be targeted.

Catering services are familiar in daily life, and the appliocation is designed to allow you to easily select a plan and check the total cost.

## Features of Catering Services

### 1: Display menus and price list

This feature appears shortly after the application has started. The title can be expressed with more impact by importing pyfiglet. The contents of the menu and price list displayed after the title are managed in advance by a dictionary and are designed to be easily changed. Changes are designed to link to other features.

### 2:　Menu Selection

This feature is designed to output the user's selections and record the user's selections. The loop is designed so that if there is a mistake in the selection, an error message will be displayed and the process will be retried.

### 3:　Exit or Retry

This feature will appear at the end of this application. It is designed so that the user can select "Yes" to start over or "No" to exit the application.

### 4:　Main Function

This feature is the core of this application.
Most functions are called from the main function and are designed to cycle through outputs and selections to help users navigate the application.

It also has a function that automatically calculates the information received from the user, and displays and the total amount to the user on the final screen.

## Code Style Guide and Styling Conventions

I followed PEP8 guidelines in coding with python. I wrote the code with a consistent style such as indentation and line length of 79 characters or less. [PEP8 Style Guide](https://peps.python.org/pep-0008/)

## Implementation Plan

I used one of github's features, projects, to manage tasks. kanban style task management was very efficient and gave me a great view of tasks ahead. I prioritized tasks on a small, medium, and large scale as needed.


## Help Documentation

Currently, this application is only suppoerted on Linux and macOS. If you are a windows user, please make sure you have WSL Ubuntu on your PC. If you don't have, please follow this guide to install : [WSL Ubuntu](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview)

### Open the terminal

-Linux systems usually come with Python pre-installed.
Please check the version following this command.

### Check a version of Python you have installed

```
python --version
```
-If you don't have Python installed or you have a version less than 3.10, please follow this guide to install : [Python](https://www.python.org/downloads/)

-You need to have Bash to run this applocation.
 Terminal for MacOS and Linux
 Git Bash for windows

### Copy a file from github and Clone in your terminal

- Please create new file and move into your new file in the termianl.

```
mkdir newfile
cd newfile
```
![Terminal App]()
```
git clone https://git@github.com:YoshihiroNak/Terminal_app_T1A3.git
```
After that,

```
cd Terminal_app_T1A3

```

```
bash catering.sh
```


This command executes the following: 

## Dependencies

```
colorama==0.4.6
iniconfig==2.0.0
packaging==23.2
pluggy==1.3.0
pyfiglet==1.0.2
pytest==7.4.3
pytest-mock==3.12.0
tenacity==8.2.3
```


