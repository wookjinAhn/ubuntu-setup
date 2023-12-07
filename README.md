# How to use  

Shell script for initial setting for Ubuntu 20.04.  
There are **Essential + Raisim** setup file & realsense setup file.  
You have to reboot your system after run "initial_setup.sh"

## Contains
- initial_setup.sh 
  + Graphic Card Driver
  + Essential Package (GNU, git, wget, curl, make, CMake ...)
  + Docker
  + CLion 
  + VSCode
  + Slack  
  + Google Chrome  
  + Python3  
  + terminator  
  + simplescreenrecorder  
  + **Raisim** (with Eigen, RBDL, Qt5)

- upboard_initial_setup.sh 
  + Essential Package (GNU, git, wget, curl, make, CMake ...)
  + CLion  
  + VSCode
  + Slack  
  + Google Chrome  
  + Python3  
  + terminator  
  + simplescreenrecorder  
  + Eigen
  + RBDL
  
  
- realsense_setup.sh  
  + realsense sdk  
  + realsense-ros  
  + d435 post processing  

## How to get  
if you have git package already.  

```bash
cd <YOUR_PATH>
git clone https://github.com/wookjinahn/ubuntu-initial-setup.git
```

else.  
Click Code button and Download ZIP file and decompress. 
then access the file by termianl  


## How to run  

```bash
cd <YOUR_PATH>
cd ubuntu-initial-setup
./initial_setup.sh
```

**There are a few things you need to enter during processing.**

### Package install directory
- This directory is used when you git clone.      
  _ex) /home/wj or /home/wj/Library_
### Raisim install directory
- This directory is not a git repository, but a place where raisim is built and installed.   
  _ex) /home/wj/raisimLib/install or /home/wj/Library/raisimLib/build/install_
### GPU driver
- You have to enter what is marked recommended. If you don't have an external graphics card, enter and move on.   
  _ex) nvidia-driver-470_ ( BEFORE - distro ... )   
