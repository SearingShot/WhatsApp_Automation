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
- Before Going Further you must know how to inspect The Webpages And get the required ID, CLASS_NAME, and XPATH from them, For These Follow The below Steps :-
![step-1](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/9815b8ab-3956-4917-a6ab-c61078ddd981)
  - Right Click On Your mouse and then Click On inspect Element
** **
![step-2](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/21013d9b-a314-461b-adb8-50d4d86c61da)
  - You'll Get Something like This
** **
![step-3](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/5049f9e0-4a02-4343-9d8d-1a83ee5068ae)
  - Then Click On the arrow
** **
![step-4](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/cbfc0c49-d82a-4057-bdf6-84435239cb6d)
  - then Hover the cursor over attachment Button
** **
![step-5](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/1bcbd1cc-721b-4ed6-ac28-3424e5cb1fbd)
  - then you'll get the XPATH to attachment button
** **
- Use That XPATH in [Whatsapp Automation using Selenium](Whatsapp_Automation_using_Selenium.ipynb) to get the location of button, Similarly You Can get The CLASS_NAME, ID too, and use it there to get the location of particular elements.
- Now follow the instructions And your Automated Messages Should Look Something Like This :-
  ![AutomationTesting](https://github.com/SearingShot/WhatsApp_Automation/assets/121299642/b7af4ba5-672e-486d-9c90-deacb9aac50a)
** ** 
 

# Contribute 

Feel free to fork this repository and make some changes, add more functionalities and send pull requests.
