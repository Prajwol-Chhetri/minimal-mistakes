---
permalink: /portfolio/
title: "Portfolio"
header:
    overlay_image: /assets/images/background.jpg
    caption: "Photo by [Vitaliy Gavrushchenko](https://unsplash.com/@gavrushchenko) on [Unsplash](https://unsplash.com)"
classes: wide
layout: single
title: "Portfolio"
author_profile: true
classes: wide


feature_row1:
  - image_path: assets/images/discord.png
    alt: "placeholder image 2"
    title: "Discord Bot"
    text: "In this project, I created a bot using discord.py module of python. This bot scrapes real time data from NEPSE's official website and presents to user in readable format. User can use various commands like knowing current status of market, top gainers or losers or also real time details of certain scripts. The bot is developed using discord py module along with Beautiful Soup to scrape real time data from NEPSE's official website. Than to keep the bot alive I've used Flask to create a server and run the code in my repl account. The created server is continuously pinged every five minutes through [Uptime Robot](https://uptimerobot.com/) which helps to keep the server alive in repl."
    url: https://github.com/Prajwol-Chhetri/Discord_bot
    btn_label: "Code"
    btn_class: "btn--primary"


feature_row2:
  - image_path: assets/images/image_ai.PNG
    alt: "placeholder image 2"
    title: "Image Detector"
    text: "In this project, I developed a script that predicts the content in the image. Using open CV module of python implementing this script was pretty easy."
    url: https://github.com/Prajwol-Chhetri/image-detector
    btn_label: "Code"
    btn_class: "btn--primary"


feature_row3:
  - image_path: assets/images/sms.jpg
    alt: "placeholder image 2"
    title: "SMS Bot"
    text: "In this project, I developed a script that can be used to send sms to one's phone number. I used twwilio API to send message. This script can be pretty handy and the possibilities to use it are endless."
    url: "https://github.com/Prajwol-Chhetri/Sms-Bot"
    btn_label: "Code"
    btn_class: "btn--primary"
    

feature_row4:
  - image_path: assets/images/pass.PNG
    alt: "placeholder image 2"
    title: "Password Checker "
    text: "In this project, I developed a script that one can use most securely to check if their password has been hacked. Many big companies get hacked with data breaches and passwords get leaked all the time. We can check if our password has been leaked through [haveibeenpwned](https://haveibeenpwned.com/) but entering our password in another website to check it is not a wise idea. So, I used API provided by [haveibeenpwned](https://haveibeenpwned.com/). The API checks the password through K-anonymity technique so we hash the password and send it to the api through this technique without worrying about the security. The script than returns the number of times the password has been found."
    url: "https://github.com/Prajwol-Chhetri/password_checker"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row5:
  - image_path: assets/images/jpg2png.PNG
    alt: "placeholder image 2"
    title: "JPG to PNG Converter "
    text: "In this project, I developed a python script that solves hassle to convert jpg images to png format. Converting multiple jpg format images to png format can be easily done with this module. I used PIL and OS module to convert and store the images. We can easily call this script through the command line by entering the path of the folder that contains images that need to be converted as first argument and path of the folder to store the converted images as second argument."
    url: "https://github.com/Prajwol-Chhetri/jpt-to-png_converter"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row6:
  - image_path: assets/images/watermark.PNG
    alt: "placeholder image 2"
    title: "PDF Watermarker and Merger"
    text: "In this project, I developed a python script that merges multiple pdf or watermarks the pdf file. Using PyPDF2 module this script can easily be called through command line. The pdf_merger.py merges multiple pdfs into one file. The pdf's that need to be merged are passed as arguments during running the script through the command line. The watermarker.py watermarks the pdf file that is passed as argument while running the script through the command line."
    url: "https://github.com/Prajwol-Chhetri/pdf-playground"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row7:
  - image_path: assets/images/translator.PNG
    alt: "placeholder image 2"
    title: "translator App"
    text: "In this project, I developed an application that can translate any text into any one of 89 languages of User's choice. The GUI for the application I built was developed using Tkinter module of python and the translation is done using google trans module which uses Google translator API to translate the text. The text that needs to be translated is entered in the first text box and the translated text is displayed in the translated box."
    url: "https://github.com/Prajwol-Chhetri/Translation_App"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row8:
  - image_path: assets/images/weather.PNG
    alt: "placeholder image 2"
    title: "Weather App"
    text: "In this project, I developed an application that can display the weather of any district of Nepal. To develop this application I used tkinter to create a GUI in which user can enter the name of the district he/she wishes to look. The weather of the district is fetched from [Nepal Weather API](https://nepal-weather-api.herokuapp.com/en/). The fetched data is parsed and displayed to the user."
    url: "https://github.com/Prajwol-Chhetri/weather_app"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row9:
  - image_path: assets/images/contact.PNG
    alt: "placeholder image 2"
    title: "Contact App"
    text: "In this project, I developed contact book application. The GUI is created with Tkinter. The user can store the details of the contact, edit certain record, delete a certain record or show stored records. The records are stored in the database using SQLLite3 module of python."
    url: "https://github.com/Prajwol-Chhetri/Contact_App"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row10:
  - image_path: assets/images/viewer.PNG
    alt: "placeholder image 2"
    title: "Image Viewer App"
    text: "In this project, I developed an application that works as a image Viewer. One can easily see the images in the images folder using this app. Buttons are added in the app to move to next image or go back to previous image or terminate the app. This app is developed using Tkinter and PIL module of python."
    url: "https://github.com/Prajwol-Chhetri/img_viewer"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row11:
  - image_path: assets/images/calculator.PNG
    alt: "placeholder image 2"
    title: "Calculator"
    text: "In this project, I developed a calculator using Tkinter module of python to create a simple gui based calculator. It can performs addition, subtraction, multiplication and division function."
    url: "https://github.com/Prajwol-Chhetri/calculator"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row12:
  - image_path: assets/images/flask.png
    alt: "placeholder image 2"
    title: "Contact Page Using Flask"
    text: "In this project, I developed a server which saves the form details filled by the user in the contact us form page to a csv file. I created the server using Flask to retreive and store the details provided by user in the csv file. The webpage is hosted in [pythonanywhere](https://www.pythonanywhere.com/)."
    url: "https://github.com/Prajwol-Chhetri/Contact_Me_Flask"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row13:
  - image_path: assets/images/blog.png
    alt: "placeholder image 2"
    title: "Blog Using Django"
    text: "In this project, I developed a CRUD Application with Django and Bootstrap. I have implemented Login system so that only staff and admin can make changes like create, update or delete to the blog or authors."
    url: "https://github.com/Prajwol-Chhetri/CRUD_Django"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row14:
  - image_path: assets/images/todo.png
    alt: "placeholder image 2"
    title: "Todo Application Using Django"
    text: "In this project, I developed a todo application using django. User can add their daily tasks and easily view them. I've used sqlite3 to store the model."
    url: "https://github.com/Prajwol-Chhetri/todo"
    btn_label: "Code"
    btn_class: "btn--primary"

feature_row15:
  - image_path: assets/images/rest.png
    alt: "placeholder image 2"
    title: "Backend REST API Using Django REST Framework"
    text: "In this project, I developed a Backend REST API using Django REST Framework. The API allows to create, update, delete & manage user profiles. It Authenticates user using their username and password. It also allows user to view feed items only if they are aauthenticated and only manage feed items that they own."
    url: "https://github.com/Prajwol-Chhetri/Profiles-REST-API"
    btn_label: "Code"
    btn_class: "btn--primary"  
---

# Skills
Python, Bash Scripting, MySQL, HTML/CSS3, Git, Linux, XML
<br>
<br>
# Projects
Here I present selected projects that show my Programming skills.  
For full list of the projects I worked on checkout my [Github](https://github.com/Prajwol-Chhetri).
<br>
<br>
{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row15" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row14" type="left" %}

{% include feature_row id="feature_row7" type="left" %}

{% include feature_row id="feature_row12" type="left" %}

{% include feature_row id="feature_row9" type="left" %}

{% include feature_row id="feature_row13" type="left" %}

{% include feature_row id="feature_row10" type="left" %}

{% include feature_row id="feature_row11" type="left" %}

{% include feature_row id="feature_row8" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row6" type="left" %}

{% include feature_row id="feature_row3" type="left" %}



