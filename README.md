# Fandom-image-downloader
A pair of python scripts that create a PowerShell script that will download all the images in original uncompressed state from a fandom webpage
# Usage
## Preparation:
* Install latest version of python 3
* Enable PowerShell script execution (Run "set-executionpolicy remotesigned" as an administrator)
* Download the webpage you want to extract the files from, open it in an editor and remove the unecessary parts on the top and bottom of the webpage body as they cause errors with python's character map
## Use
* Launch a command prompt in the folder you have the scripts at
* Type "split.py file.html" where file.html is the name of the downloaded webpage
* Type "download.py links.txt"
* Type "powershell"
* Type ".\downloader.ps1"
* Your images will now download 
