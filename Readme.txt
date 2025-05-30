1. Copy files in the "var-lib-apt-lists" folder into /var/lib/apt/lists folder
	download https://github.com/baosheng0304/PointCloudLib/tree/main/var-lib-apt-lists
2. Install required packages
  download https://github.com/baosheng0304/PointCloudLib/tree/main/var-cache-apt-archives
    $ cd var-cache-apt-archives
    $ sudo dpkg -i *.deb

3. Install Pangolin

    $ cd Pangolin
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make -j
    $ sudo make install

4. Copy and Merge folders in the "usr-local" folder into "/usr/local" folder

5. Build ORB_SLAM3_RGBL-rgbl

    $ cd ORB_SLAM3_RGBL-rgbl
    $ sudo ./scripts/build.sh
