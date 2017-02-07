# powerbutton
This is a remote power controller for Raspberry Pi 3 mode B.
# How to setup.
##apt-get install -y wiringPi
##cd ~
##git clone https://github.com/yoyojacky/powerbutton.git 
##sudo mv ~/powerbutton/gpioshutdown /etc/init.d/
##sudo chmod +x /etc/init.d/gpioshutdown
##sudo vim.tiny /etc/rc.local
add this two lines before exit 0
##gpio mode 25 out 
##gpio write 25 1 
### [optional]
You can modify your /boot/config.txt file as config.txt.
### have fun
