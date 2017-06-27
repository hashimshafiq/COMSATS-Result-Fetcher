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

Now just open __comsats.py__ script file and put the __API key__ there

![alt text](http://i63.tinypic.com/2rfsutz.png "API Key")

Now you have to add your roll number and password in the file.

![alt text](http://i64.tinypic.com/2v0e3cn.png "RollNumber and Password")

Now add the last thing i.e the session for which you want to chck the result.

![alt text](http://i67.tinypic.com/16j4wp3.png"Session")

Now all set. All this is only 1 time setting. I wrote the whole thing is just few hours or in so hurry so It might be horrifying at first sight. May be If I found time I will add some other things in it and make it user friendly.

Now just run the file to check for the result and look what I got.

![alt text](http://i63.tinypic.com/2qvyxsk.png "Result Output")

So now just run it when you want ot check for the result.

### Future Development

* Make it more user friendly
* Convert into Android App
         
         OR
* Integret Twillio SMS API (So when result announced a message is delivered to your number. I am trying hard on this but actually Twillio api is expensive so cannot afford for now. And international message cost alot.)

__Anyone trying to improve it, feel free to fork, makes changes and then send pull request__













