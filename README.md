ReddWall
================

ReddWall sets your wallpaper to a random image from one of the many Reddit wallpaper subreddits.

What it Does
------------

On the first run, ReddWall will find a random wallpaper from /r/wallpapers and minimize to the status bar. By default, it will select a new wallpaper every 1 hour. This behavior can be changed in the preferences window that can be opened by clicking the ReddWall icon in the status bar.

Running from Source
-------------------
To run from source, first make sure you have Git, Python 2.7, setuptools, and wxPython 2.7 installed. Then, clone the repo:

``git clone https://github.com/lightstalker/reddwall.git``

and install it using the setup.py script:

``python2 setup.py install``

Installation instructions
-------------------
After running from source, locate the file praw.ini and fill in:
client_id=
client_secret=
username=
password=
from reddit (add a new application on https://www.reddit.com/prefs/apps/ when signed in, use http://127.0.0.1:8080 for loopback (or any address)
