# echo-pi
Controlling Raspberry Pi GPIO with Amazon Echo using fauxmo

#How to run 
1. Run gpio-control.py in terminal "python gpio-control.py"



#How to run @Startup
1. sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
2. Use the arrow keys to navigate to the end of the second line and press ↵ Enter. NOTE: This will created a new line above the @xscreensaver -no-splash entry. Many users have reported that commands added below this line do not run successfully so it's common practice to add your custom commands above the @xscreensaver entry.
3. Add a command to launch your script.
4. Sudo reboot
