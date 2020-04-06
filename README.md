# Instagram_Bot
Managing an Instagram account for a firm takes a lot of time and effort.  Replying to comments, posting new content, monitoring brand mentions and numerous other tasks fill up your day. As a result, several marketers resort to Instagram automation, including tools frequently referred to as ‘Instagram bots,’ to save time and take care of some of the more monotonous aspects of Instagram marketing. I built this bot with the help of Python 3.8 and Selenium package.  Selenium package bindings provides a simple API to write functional/acceptance tests using Selenium Web Driver. Selenium Python bindings provide a convenient API to access Selenium Web Drivers like Firefox,  Chrome, Remote etc.  This was a fun little project which gave me a vague idea about how web automation works and what it's pros and cons are. To further build upon this project, I might add features like commenting on posts having similar tags and downloading a users image media. 

# Current Features 
> Follow a user
> Unfollow a user
> Search posts by tag
> Like a users latest posts
> Unlike a users latest posts
> Download a users image media

# Some Instructions 
> Download driver for your respective version of Google Chrome into the root directory of the project. To see your Google Chrome version, go to chrome://version/ in your browser. To download the respective driver, go here: http://chromedriver.chromium.org/downloads.

> Add the username and password values in the config.ini file that the Instagram account the bot will use. Username and password combinations can also be passed when creating instances of the InstaBot class in instagram_bot.py.

>Install the dependencies in requirements.txt, with pip install -r Requirements.txt from the root directory of the project, preferably in a Python 3.7 virtual environment.

>In the instagram_bot.py file, add the lines for the functionality desired at the bottom of the file.
