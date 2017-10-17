# sandbox

## Introduction

## What you’ll learn
In this tutorial, you’ll learn how to:
  1.	Setup OpenCV 3.3 on Ubuntu 16.04 LTS -- target hardware (UP2)
  2.	Build a people counter application in Arduino Create IDE -- compile the code here
  3.	Run the people from the command prompt on your Ubuntu desktop

## Gather your materials
You’ll need the following to complete this tutorial:
  *	[UP Squared board](http://www.up-board.org/upsquared/)
  *	[Ubuntu 16.04](https://)
  * [OpenCV version 3.3]
  *	A UVC webcam

## Setup OpenCV 3.3.0

This sections contains the instructions to download, build and install the OpenCV 3.3.0 libraries on the Ubuntu desktop.

### Download
Open a command prompt from the desktop and type:

git clone https://github.com/...

Navigate to the folder **opencv-3.3.0**

### Build
Next, cd into the **build** folder contained in the **opencv-3.3.0** folder download:

```
cd opencv-3.3.0
cd build

```

### Install
To run as root type `su` and when prompted enter your password.

Note: a hastag '#' should appear at the end of the command promopt if you are logged in as root. 
To find the folder where you installed OpenCV version 3.3.0 on your desktop, type:

```
find -name opencv2
```

For installation, from the <name> directory (what folder do I need to be in?) type:
```
make
sudo make install
ldconfig
```

optional:
``` 
make examples
```
#### opencv_contrib-3.3.0 (optional)
Contributions from the open-source community??
<step by step>

## Compile the code sample in the Arduino Create IDE

In the Arduino Create IDE, verify and then upload the code sample to the UP2 board (or similar hardware). 

After uploading the sketch to the target hardware (default naming?), find a **sketches** folder created in the Home directory.

## How it works
Place commented code snippets here.

## Run the Application
cd into the **sketches** directory: cd sketches
Run as root user: su

