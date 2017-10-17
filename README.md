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
  * [OpenCV version 3.3.0]
  *	A UVC webcam

## Setup OpenCV 3.3.0

This sections contains the instructions to download, compile and install the OpenCV 3.3.0 libraries on the Ubuntu desktop.

### Download
Open a command prompt from the desktop and type:

```
cd ~
mkdir opencv
cd opencv
wget -O opencv-3.3.0.zip https://github.com/Itseez/opencv/archive/3.3.0.zip
wget -O opencv_contrib-3.3.0.zip https://github.com/Itseez/opencv_contrib/archive/3.3.0.zip 
```

Now, unzip the archives you downloaded:

```
unzip opencv-3.3.0.zip
unzip opencv_contrib-3.3.0.zip
```

After unzipping the archives, you will have two OpenCV directories.

Navigate to the folder **opencv-3.3.0**

### Compile
In the compile step you'll build the OpenCV libraries. 

cd into the **opencv-3.3.0** folder download:

```
cd opencv-3.3.0
mkdir build
cd build
```
Create the make files:

Approximate compile time: 55m 56s

```
cmake ../
make
```

*Specifying the number of threads/cores to utilize*
Approximate compile time:
```
make -j3
```

**Note:** The `cmake` and `make` commands must complete successfully for you to continue with the installation below.

### Install
From the  `~/opencv/opencv-3.3.0/build ` directory, type:
```
sudo make install
sudo ldconfig
```

`ldconfig` it tells the operating system that the OpenCV libraries are available.

## Compile the code sample in the Arduino Create IDE

In the Arduino Create IDE, verify and then upload the code sample to the UP2 board (or similar hardware). 

The Arduino Create IDE will compile/build the code into an executable. 

```
su
cd sketches
```
```
./people-detect
```

After uploading the sketch to the target hardware (default naming?), find a **sketches** folder created in the Home directory. You will need be logged in as root to run 

## How it works
Place commented code snippets here.

## Run the Application
cd into the **sketches** directory: cd sketches
Run as root user: su

