MACADDRESS CHANGE IN LINUX,
step 1:- iftop 
step 2:- copy your macaddress 
step 3:- sudo ifconfig wlan0 down "down your internet service provider"
step 4:-  sudo macchanger -m 84:a9:3e:09:55:65 wlan0 "enter your mac adress and cange any number"
step 5:- sudo iftop wlan0 up  
