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

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row6" type="left" %}

{% include feature_row id="feature_row3" type="left" %}



