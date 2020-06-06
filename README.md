# DI3TextureExtractor
Tool for extracting character textures from the DI3 game


## DISCLAIMER
Backup all your files before executing this program. This software is provided without any kind of warranty. You have been warned

## How to install
Download all the files and put them on a folder in the same directory that DisneyInfinity3.exe exists.
If you dont put it on that place it will not work. 

![alt text](doc/installation.jpg)

## How to use
Open a command prompt on the directory that extract.exe resides.
The program expects a single parameter that will be the name of the file of the character that we want to find and extract the textures.
If we use a partial name, it will list all the filenames that contain it.
If there is only one match, it will start extracting the model files and also will try to find the textures.

The files will be extracted on a folder with the character name.
![alt text](doc/usage.jpg)

## Known bugs
If we want to extract a character that has variations like avg_captainamerica or avg_falcon, it will always return more than one matches and it will not work. This will be fixed in the future.

There are some model files that already have some textures embeded. The tool will fail extracting the textures from the textures folder because it cannot find them... Just check the folder and subfolders of the extracted files and you will find them.

