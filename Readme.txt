1. Copy files in the "var-lib-apt-lists" folder into /var/lib/apt/lists folder

2. Install required packages
   
    $ cd Packages
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
