# Python Web Scraping Projects

These python web scraping projects are built in correspondence with " [100 Days of Code - The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) " course. This course was taught by London's App Brewery top instructor Angela Yang.<br/>

Each project has been built from scratch with minimal to no assistance.<br/>

### Day 045 - Top 100 Movies to Watch

This project involves scraping "The Top 100 Movies of All Time" webpage (from the [Empire](https://www.empireonline.com/movies/features/best-movies-2/) website). Use the requests module to get the contents of the webpage. Store the newly acquired webpage content as text (i.e., string). Use the bs4 (Beautiful Soup 4) library to parse the contents of the webpage and acquire the  "The Top 100 Movies of All Time". Finally, push top 100 movies into a text file.

For a live version, go [here](https://replit.com/@grandeurkoe/top-100-movies-to-watch?v=1) .

![Top 100 Movies to Watch](top-100-movies-to-watch/top-100-movies-to-watch.gif)

### Day 046 - Musical Time Machine

This project simulates the Musical Time Machine by scraping the "Billboard Hot 100" webpage (from the [Billboard](https://www.billboard.com/charts/hot-100) website) and adding each song to a Spotify playlist using the spotipy library. 

Get time travel date as user input. Use the requests module to get the contents of the webpage. Store the newly acquired webpage content as text (i.e., string). Use the bs4 (Beautiful Soup 4) library to parse the contents of the webpage and acquire the "Billboard Hot 100". 

Use the spotipy library to perform the following operations:
- Create an empty playlist.
- Use the spoitpy API to search for tracks that you scraped from "Billboard Hot 100" webpage in Spotify.
- Add tracks to the playlist.

![Musical Time Machine](musical-time-machine/musical-time-machine.gif)

### Day 047 - Amazon Price Tracker

This project involves scraping a product page from the Amazon website. Use the requests module to get the contents of the webpage. Store the newly acquired webpage content as text (i.e., string). Use the bs4 (Beautiful Soup 4) library to parse the contents of the webpage and acquire the product name and price. If the produce price is less than the target price, then send an email to oneself using the smtplib library.

For a live version, go [here](https://replit.com/@grandeurkoe/automated-amazon-price-tracker?v=1) .

![Amazon Price Tracker](automated-amazon-price-tracker/automated-amazon-price-tracker.gif)

## Getting Started

### Prerequisites

<b>For Windows:</b>
<br/> 

Download and Install the latest version of [Python](https://www.python.org/downloads/).<br/><br/>
Download and Install the latest version of [PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/?section=windows).<br/>


<b>For Linux:</b>
<br/> 

<b>Linux</b> comes preinstalled with Python.<br/><br/>
To install the latest version of PyCharm Community Edition, run the following command:
```
sudo snap install pycharm-community --classic
```

### Installing

You can install all the required packages listed in the requirements.txt file for the project at the same time: 


<b>On Windows type:</b>
<br/> 
```
python -m pip install -r requirements.txt
```

<b>On MacOS type:</b>
<br/> 
```
pip3 install -r requirements.txt
```

## Built Using
<p>
  <img alt="Python" src="https://img.shields.io/badge/-Python-ffde57?style=flat-square&logo=python&logoColor=#4584b6" />
  <img alt="Pycharm" src="https://img.shields.io/badge/-Pycharm-ffe873?style=flat-square&logo=pycharm&logoColor=black" />
  <img alt="Replit" src="https://img.shields.io/badge/-Replit-CD5C08?style=flat-square&logo=replit&logoColor=white" />
  <img alt="Obsidian" src="https://img.shields.io/badge/Obsidian-7E1DFB?style=flat-square&logo=obsidian&logoColor=white" />
  <img alt="git" src="https://img.shields.io/badge/-Git-f34f29?style=flat-square&logo=git&logoColor=white" />
  <img alt="Github" src="https://img.shields.io/badge/-Github-14232c?style=flat-square&logo=github&logoColor=white" />
</p>

## Authors

*Initial work* - [grandeurkoe](https://github.com/grandeurkoe)
