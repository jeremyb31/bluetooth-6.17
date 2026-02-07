Install from terminal for Ubuntu 6.17 kernel

sudo apt install dkms git

git clone https://github.com/jeremyb31/bluetooth-6.17.git

sudo dkms add ./bluetooth-6.17
sudo dkms install btusb/6.17

Secure Boot should be disabled, reboot
