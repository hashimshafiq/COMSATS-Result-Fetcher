# COMSATS Result Fetcher

At my university, we are eagerly waiting for the result of the final semester. But we dont know what the schedule for the result. We have to enter our
roll number , password, enter some captcha (dont know whats the need of the captcha on a student portal) and then login into the system, navigates
to some directories to see the result and mostly disappoint beecause result not announced yet.

So as a computer science student its my duty to solve that issue. Here I wrote a python script that will autmatically puts the login information
, solve the captcha and then navigates to a result directory and checks whether result is announced or not in a fraction of a second.

### Requirements

* python 3.x
* BeautifulSoup
* Request
* [2Captcha Account](https://2captcha.com/)

__Note: You can install above libs using pip__

### Login Screen
Here is the login screen looks like:
![alt text](http://i63.tinypic.com/1taate.jpg "CMS Login Screen")

### How it works

Go to the [2Captcha](https://2captcha.com/) and create account.The 2Captcha is giving services which solves the captcha. And also it is not free but it is very very cheap. I am not going to write my own captcha solver because it takes time and it is just a pet project and it needs to be complete before the result came :) So create account on 2Captcha and from there you just need the __API KEY__

![alt text](http://i65.tinypic.com/2ioqjo.png "API Key")






