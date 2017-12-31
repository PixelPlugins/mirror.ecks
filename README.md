# The EPM Mirror
This repository is the mirror for EPM, the apt-get-style package manager for windows.

## Download EPM
Just click this...

[![EPM Download](https://github.com/PixelPlugins/mirror.ecks/blob/master/EPM.png?raw=true)](https://github.com/PixelPlugins/mirror.ecks/blob/master/EPM.exe?raw=true)
### IMPORTANT: EPM needs Jint, so be sure to click [here](https://github.com/PixelPlugins/mirror.ecks/blob/master/Jint.dll?raw=true) to download Jint.dll and put it in the same folder as EPM.exe!

## Usage
To use EPM, you must interface it with the command line. (However, a GUI is comming out soon). Open the folder that has EPM.exe and Jint.dll in it, and then hold shift and right-click in the white space to the side.(So your mouse isn't touching a file.) Then click "open command window/powershell here". Now you can use EPM commands.

Installing a package is easy: EPM \<package name\>

Every EPM package is stored on this repo. To do a quick test, try EPM example

When you install a package, it goes in C:\Ecks\Packages. After installing the example package, look in that folder and you will see example.txt.

## Packaging Software
If you want to package your software for EPM, first figure out if your software is a single file or a multi-file aplication.

### If it is a single file, follow these steps:

1. Create a new issue in this repository
2. In your issue, add your file
3. Also add the name of your package
4. If your package requires any other EPM packages to be installed, make sure to put the names of those packages in your issue
5. Wait for a response, either saying your package was uploaded or that it failed
6. Test your package. Do EPM \<your package name\>

### If it is multiple files:

1. Create a zip file containing all the required files
2. Make sure the main file is named <your package name>.exe
3. Create a new issue in this repository
4. In your issue, add the zip file
5. Also add the name of your package
6. If your package requires any other EPM packages to be installed, make sure to put the names of those packages in your issue
7. Wait for a response, either saying your package was uploaded or that it failed
8. Test your package. Do EPM \<your package name\>
