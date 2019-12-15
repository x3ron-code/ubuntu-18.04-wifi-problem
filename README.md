# ubuntu-18.04-wifi-problem
ubuntu 18.04 wifi problem
This video will show you how to install Realtek RTL8821CE WiFi Driver on Ubuntu 18.04(hp laptop)
P.S. Secure Boot must be disabled !
sudo apt update
sudo apt install -y dkms git
git clone https://github.com/tomaspinho/rtl8821ce.git
cd rtl8821ce
sudo ./dkms-install.sh
sudo modprobe 8821ce
