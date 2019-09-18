# CODY - TextBot
A simple NLTK Text Chatbot for the "Tag der Talente" workshop 2019 
based on an example script from Parul Pandey.

## Usage
``` 
python3 chatbot.py
```

# Setup

## Windows

1. Install WSL. Open PowerShell as Administrator and run: 
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
2. Restart Computer

3. Download and install [Visual Studio Code](https://code.visualstudio.com/Download)

4. Go to Windows Store: Download an install at least Ubuntu 18.04

5. Start Ubuntu and chose username and password (type password twice), hit enter to confirm

6. Type in the following into the command line interface:
```
sudo apt update && sudo apt dist-upgrade -y
sudo apt install python3 python3-pip -y
pip3 install nltk sklearn termcolor stop_words
```
Wait for every command to finish before typing the next.

7. Type
```
code .
```
This starts Visual Studio Code. It recommend some modules to install, install them all (at least the plugin to work with WSL and python3).

8. Download this archive as zip, unzip it and simply drag and drop it into the left hand side, where the other directorys are.

9. Start working in the directory called "CODY".

## Linux (Debian, Ubuntu, Mint, ...)

1. Fire up a Terminal, type in:
```
sudo apt update && sudo apt dist-upgrade -y
sudo apt install python3 python3-pip -y
pip3 install nltk sklearn termcolor stop_words
```
2. Download and install [Visual Studio Code](https://code.visualstudio.com/Download) (Or choose to install from perfered store).

3. Download this archive as zip, unzip it and simply drag and drop it into the right hand side, where the other directorys are.

4. Drag the file CODY into the left hand side and start working.

## MacOS

1. Install homebrew (package manager for Mac):
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

2. Type in an Terminal (/Applications/Utilities/Terminal.app):
```
brew install python3
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
pip3 install nltk sklearn termcolor stop_words
```

3. Download and install [Visual Studio Code](https://code.visualstudio.com/Download) (Or choose to install from perfered store).

4. Download this archive as zip, unzip it and simply drag and drop it into the right hand side, where the other directorys are.

5. Drag the file CODY into the left hand side and start working (VSC may ask to install some packages - do it :).
