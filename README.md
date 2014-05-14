#bii-IDE

**Bii-IDE** is an **ide for Arduino** that integrates all the functionality of [biicode](http://biicode.com/).

With [biicode](http://biicode.com/) you can:

1. **Save your project in different folders** for a better organization.

2. **Reuse yours and other users'code.** Reusing made easy: just **#include** the file you need and you get it. No more copy and paste files from project to project or dowloading zip files from tutorials.

3. This is a **simple** and **fast** way to **compile and upload** your code in your Arduino.

5. biicode are hosting adafruit, sparkfun and many other libraries, **you won’t need to download and install libraries in your SDK anymore**.

##User guide

###1. Select your workspace or create one

![](https://github.com/davidsanfal/bii-ide/raw/master/docs/images/select_workspace.png)

###2. Check out the interface

![](https://github.com/davidsanfal/bii-ide/raw/master/docs/images/ide.png)

####2.1 Menu and Tools bar

1. `File:` tools to create and manage files and projects.
2. `Workspace:` tools to create and manage workspace and update the information of it.
3. `Commands:` biicode command set.
4. `About:` information about bii-IDE, biicode, arduino and Qt.

####2.2 Workspace info

1. `Projects:` projectlist of the selected workspace.
2. `Blocks:` blocklist of the selected project.
3. `Blocks files tree:` filetree of the selected block.

####2.3 Edition site

####2.4 Biicode commands

1. `biicode command:` [biicode command info.](http://docs.biicode.com/arduino/reference/commands.html)
2. `monitor:` Open a serial terminal to communicate with your Arduino.
3. `terminal:` Open a OS Terminal to execute any command.

##Code dependencies

-   [biicode](https://www.biicode.com/downloads)
-   [Python 2.7](http://www.python.org/)
-   [PyQt4](http://www.riverbankcomputing.com/software/pyqt/intro)

##Cloning and Running

    git clone git://github.com/biicode/bii-ide.git
    cd bii-ide/bii-ide
    python bii_ide.py
