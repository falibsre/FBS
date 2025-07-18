# This is a fork from original BSDS by [Crazor](https://github.com/CrazorTheCat)  with a lot less features, it is meant for developement, do not use for production and hosting for others.

## How to play FBS: ##

### Server ###
1: Download the server and extract it.

2: Open terminal on your computer and go to FBS directory.

3: Now you need to install crypto module.

3.1: type cd Crypto

3.2: now type python setup.py install --user

4: Type python Core.py and it's done, follow client instructions.

### Android client ###
1: Download the [apk](https://t.me/BrawlStars_Archives/3111)

2: Download an apk editor of your choice

3: Decompile the apk with the apk editor and go to lib/armeabi-v7a/libprojectfbs.config.so and open the file with a text editor.

4: Edit "redirectHost": "192.168.18.102" to your ipv4 address, if your self hosting.

5: How to find ipv4 address?, if your running the server on your phone, you can change that "192.168.18.102" to "127.0.0.1", otherwise if your running the server on pc, open command prompt and type ipconfig and you'll see your ipv4 address down below which will start like "192.168.xx.xx"

6: Compile the apk with the changes and install it, and enjoy playing fbs brawl!

## Optional Steps [Android] ##
1: If you want to change port you could change redirectPort to whatever port you want, keep in mind you have to change port in server too.

WARNING: DATABASE IS NOT WORKING

![IMG_1310](https://github.com/falibsre/FBS/blob/47/menu.png)

## credits ##

[risporce](https://github.com/risporce) for his README.md
