# HBL-autoinstall
Auto Installation script for HBlink3 and HBMonitor


cd /opt

sudo apt-get install git

sudo git clone https://github.com/wiblingen1/HBlink3-debian11-12.git

sudo git clone https://github.com/wiblingen1/HBL-autoinstall.git

cd HBL-autoinstall

sudo chmod +x autoinstall.sh

sudo ./autoinstall.sh

If you want to reinstall the system use:

cd

sudo ./autoinstall.sh


