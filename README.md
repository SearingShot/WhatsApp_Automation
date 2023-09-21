# WhatsApp_Automation Using Selenium And Python

## Overview

This project provides a Python-based automation script for sending multiple messages, photos, and videos on WhatsApp using Selenium WebDriver. It aims to optimize communication processes by allowing you to automate tasks on WhatsApp.

## Features

- Send text messages to individual contacts or groups.
- Send photos and videos to contacts or groups.
- Automate repetitive tasks, such as sending daily messages.
- Customizable and extensible for your specific needs.
- Simple and user-friendly automation for WhatsApp Web.

## Prerequisites

Before you begin, Ensure that you must have :

- Python 3.x installed on your system.
- Google Chrome browser installed.
- ChromeDriver installed (compatible with your Chrome version).
- `selenium` package.
- Preferably open the repository on jupyter Notebook For better Understanding.
- Know How to Inspect a Webpage To get Their class_name, id, and XPATH.
- We will Also Be sending an image, So you can choose Any but we are using this one - https://github.com/SearingShot/WhatsApp_Automation/blob/main/jerry.jpg 😏

## Steps 

- Clone the repository or Download ZIP file 
- Visit  https://sites.google.com/a/chromium.org/chromedriver/downloads and download chromedriver that matches with the version of your chrome browser 
- Add chromedriver to your project environment 
- Install selenium using "pip install selenium" command in terminal
- First We will perform a random Automation task on random Website to get the basic Idea Of working Of Selenium. Check Out [Intro to Selenium Automation](Intro_to_Selenium_Automation.ipynb) , Performing task given there, you'll be able to open particular link in the website without having to click on it directly. This part is what we call automation task. 
- After getting the basic of Selenium we will be diving a bit deeper, by using selenium for WhatsApp Automation. Now check [Whatsapp Automation using Selenium](Whatsapp_Automation_using_Selenium.ipynb)
- In There, You Will First import all The necessary Modules of the Selenium And time Library. Now Using Chrome Webdriver Open WhatsApp web, Scan The BarCode Given There With The WhatsApp app in your phone, now the WhatsApp is Opened in your Automation browser, and the chat that you entered in target variable will be opened Directly.
- Before Going Further you must know how to inspect The Webpages And get the required ID, CLASS_NAME, and XPATH from them, For These Follow The Steps given in - [How_To_Inspect_Elements](How_To_Inspect_Elements.md)
- Now follow the instructions in [Whatsapp Automation using Selenium](Whatsapp_Automation_using_Selenium.ipynb) And your Automated Messages Should Look Something Like This :-
  ![AutomationTesting](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/b7af4ba5-672e-486d-9c90-deacb9aac50a)
** ** 

# Examples
**Here are some common use cases for this WhatsApp automation script:**
- Sending a daily morning message to a family group.
- Sharing images with friends.
- Automating repetitive tasks without manual intervention.

# Contributing 

Contributions are welcome, Feel free to fork this repository and make some changes, add more functionalities and send pull requests. 😉
