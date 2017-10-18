cd ~/Downloads
wget -O opencv.zip https://github.com/Itseez/opencv/archive/3.3.0.zip
wget -O opencv_contrib.zip https://github.com/Itseez/opencv_contrib/archive/3.3.0.zip
unzip opencv.zip
unzip opencv_contrib.zip
cd ~/Downloads/opencv-3.3.0
mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_INSTALL_PREFIX=/usr/local -DWITH_V4L=ON -DWITH_IPP=ON -DWITH_FFMPEG=ON -DOPENCV_EXTRA_MODULES_PATH=~/Downloads/opencv_contrib-3.3.0/modules/ ..
make -j8
sudo make install


