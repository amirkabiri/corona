# Introduction
This is a php virus written by me that I named it Corona because it tries not to slow down the site as much as possible and not cause any error and tries to stay hidden.

I wrote this for fun and new experience :)

**Please don't harm websites using this virus**


# Features of this virus
* copies itself to every php file in subfolders and current folder
* this virus does not damage the php files in parent folders
* opening infected website with **http://infected-website.com?corona** querystring, gives you a php shell that you can run any php code 
* If it infects a site, it notifies you via telegram by sending infected website url to a channel you specified in its source
* if you are a php developer, you can bind any functionality to this virus, to do it on infected website (by default, I put a php shell on it)
* This virus tries not to slow down the infected site significantly
* This virus tries does not cause any php error on the infected site
* This virus signs any infected php files to increase performance
* on every execution, it runs and only multiples itself in other php files for 10 seconds (you can change this time)
* After duplicating itself on all php files, the speed of the site increases
* when it duplicates itself to other file, it also encrypts itself to base64

# Looking for a Challenge?
If you are looking for a challenge, create a antivirus with php that scans the infected website and repairs damaged files.
I will link your antivirus repository here.
thanks for attention.

# Shell Screenshot
![Shell ScreenShot](https://raw.githubusercontent.com/amirkabiri/corona/master/shell-screen.png "Shell ScreenShot")