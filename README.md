Installing the latest kernel.

Install the shell script which automatically checks and install the latest kernel:

wget https://raw.githubusercontent.com/reaperofpower/ubuntu-kernal-upgrade/main/ubuntu-kernel.sh
sudo install ubuntu-kernel.sh /usr/local/bin/


Run the shell script:

Check for new kernal
sudo ubuntu-kernel.sh -c     

Install the latest stable kernel:
sudo ubuntu-kernel.sh -i

Reboot to boot into the latest kernel:
sudo reboot      

Verify Kernal Version
uname -r


