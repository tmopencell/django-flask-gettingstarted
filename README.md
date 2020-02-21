# Django and Flask: Getting Started
Resources for getting started with Django and Flask for developing front ends for physical computing, IoT and Raspberry Pi projects. Assumes you like (or respect) python. 

## Front End Dev: Django and Flask

Some resources/tutorials and thoughts on them. One issue I noted is that there are very few examples that incorporate IoT and/or Raspberry pi into the workflow. Especially input/output. This is my main interest and has meant that a lot of diverse projects needed to be pulled together. Some day I will write my own tutorial on IoT + Django! 

## Summary: Flask is easier to get started with and make basic functionality but might not be the best in the long run. Django is much harder to get to grips with but has features built in that you may require, like logging in as user/admin and is used for  serious apps. Dropbox, Instagram, spotify are all made in Django! 


## Django Tutorials/Projects(in order of helpfulness)

* https://tutorial.djangogirls.org/
This is the best resource I found. Full journey from cmd line, python, Django, css and html. You can pick any up without reading the others making it very modular. The tutorials are still a bit “do this, look what happens!” rather than stepwise, which I prefer. However, the combination of form+function is still outstanding. Very good explanation of how to develop static pages with css and html but if you are seeking js or ajax that is the only thing I could say is missing.. 

* https://dev.to/omenapps/modern-django-project-examples-58mm
Outstanding list of GitHub hosted Django apps and projects. Good resource to see applications and find already made solutions!

* https://scotch.io/tutorials/build-your-first-python-and-django-application
Good (code was all correct and executable)  but I hate this style of tutorial, e.g., “Do this, now update the page”… “it isn’t working!” … “That’s because I haven’t told you the next bit!” .. Ugh. Just give me a step 1,2,3 and 4. Boring and quick is better than exciting and long. Some basic webdev and showed how to make two basic pages but no backend script execution etc.

* https://medium.com/@johngrant/raspberry-pi-and-django-channels-8d5cddb36226#.vooyyl50t
In principle this is the most relevant tutorial for me. Spent a day on it and close to giving up.. Lots of dependency issues and a huge amount of debug. Not a good starter project.

* https://medium.com/ristek-fasilkom/controlling-raspberry-pi-with-django-a91940fc3f4d
This was OK and very neat and simple. Turn a light on/off by going to a webpage. Unfortunately littered with code errors and missing explanation meaning. No webDev whatsoever!

* https://medium.com/quick-code/crud-app-using-vue-js-and-django-516edf4e4217
Really not great for me. Poor explanation of why the framework was chosen (still none the wiser as to what a CRUD app is..). I think Vue.js could be useful but for what I am after (plus my lack of front end experience) but static pages are a better start. I think if you are comfortable with front end development then this might actually be a good option for you. 

* https://medium.com/@arthurgomesfaria/simple-home-automation-python-relay-module-c0e088e05a2b
No teaching component at all. Maybe it works? But I just could get the concept. How could I extend this project? What are the front end opportunities?

* https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django
Thorough overview (11parts) but it is toooo in detail. It explains the entire hierarchy etc and you don’t need all that. Also the project that you develop: A functional library where you can check out (or update available) books is not a use case that I am interested in. 

* https://docs.djangoproject.com/
I usually never go to the actual documentation page since often the language is very esoteric and robotic. I prefer applications that give me an idea of stuff something can be used for and then build out my knowledge from there. But in fairness the Django docs are application intensive and that is super helpful. 

* http://oliverelliott.org/article/computing/script_airapp/
OK tutorial on how to build a an app that takes an input and does some processing and then spits something back out with quite a few nifty features you could imagine expanding. Unfortunately the code is in an outdated format and the description of how to implement is a bit poor. The issues mainly resides in the urls.py file but the template pages are also an issue since if you just copy+paste it won’t work directly. 

## Flask Tutorial Projects:

* https://www.fullstackpython.com/flask.html
Django kind of makes me very angry… I found a god review of Flask development frameworks and it is a LOT easier than django for getting started but not forever… 

* https://randomnerdtutorials.com/raspberry-pi-web-server-using-flask-to-control-gpios/
The unthinkable! A script for turning on/off gpio pins on a raspy using Flask

* https://towardsdatascience.com/python-webserver-with-flask-and-raspberry-pi-398423cc6f5d?gi=fb007e05b9a3
Did not try yet. 

## General Overview:

* https://hackernoon.com/top-python-web-development-frameworks-to-learn-in-2019-21c646a09a9a
This is the overview of python webdev frameworks that originally led me to Django. Useful enough resource to get an overview of python web frameworks. 

* http://bettermotherfuckingwebsite.com/
No harm to give this  read when you are making your website.. Keep it simple, short and easy to read. 

* https://www.codementor.io/@kaushikpal/user-defined-functions-in-python-8s7wyc8k2
Helpful refresher on user defined functions python

* https://realpython.com/python-f-strings/
Helpful guide on f-strings in python.

