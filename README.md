# dumbrss
A bullshit-free, web-based RSS reader  

## Features
TODO  

## Setup
dumbrss uses [Flask](http://flask.pocoo.org/). To install, simply set up your favority WSGI
server and create a virtualenv to run dumbrss into:  
```
virtualenv3 venv
pip install -r requirements.txt
source venv/bin/activate
```
Finally, initialize the database with `./dumbrss.py initdb`.  
You need to set up a cronjob to run `./dumbrss.py fetch` from within the virtualenv
as often as you want.  

