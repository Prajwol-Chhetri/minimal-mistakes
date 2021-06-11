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
    text: "In this project, I created a bot using discord.py module of python. This bot scrapes real time data from NEPSE's official website and presents to user in readable format. User can use various commands like knowing current status of market, top gainers or losers or also real time details of certain scripts."
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

{% include feature_row id="feature_row3" type="left" %}



