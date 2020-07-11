# dofusfashionista
The Dofus Fashionista, an equipment advisor for Dofus

## Install Fashionista:

sudo apt-get update  
Install Git - sudo apt-get install git  
git clone https://github.com/PiwiSlayer/DofusFashionista.git fashionista  
Add “export PYTHONPATH=/home/<\<user\>>/fashionista/fashionistapulp” at the end of ~/.bashrc  
chmod 777 fashionista  
chmod 777 fashionista/fashionistapulp/fashionistapulp  
cd fashionista  
sudo ./configure_fashionista_root.py -i [-s -d]  
./configure_fashionista.py  
Opcional - Don't start Apache automatically - sudo update-rc.d -f apache2 disable  
Run server - sudo ./run_fashionista.sh  
