# building-opencv-ubuntu-cmake
A repo containing guidlines for building opencv in a Linux environment

# Downloading sources
* Clone both opencv and opencv_contrib 
```
git clone https://github.com/opencv/opencv.git
git clone https://github.com/opencv/opencv_contrib.git
```
* Extract both the files in usr/local for the build process via cmake
```
sudo mv ~/opencv_source/opencv /usr/local
sudo mv ~/opencv_source/opencv_contrib/ /usr/local
```
# Go to OpenCV directory and create a build folder
```
cd opencv
mkdir build
```
# Install the cmake-gui tool
```
sudo apt  install cmake-qt-gui
```
# Install Qt5 dependencies
```
sudo apt-get install qtbase5-dev
sudo apt-get install qtdeclarative5-dev
```
# Run the following cmake command to build opencv 
* Press configure and then generate

# Make and install
* Now go to your build folder and run the following commands (the make command will take a considerable amount of time)
```
make
install
```
