## Transfer big data to iPad

For transfer data to iPad device, I done some research/reading on two different approach: WIFI and USB cable. I concentrate on the data transfer speed via WIFI and USB. I do not talk about time to package data or extra data. Here is my findings.

## WIFI

Tech Specs from Apple:
iPad Pro
* Wi-Fi (802.11a/b/g/n/ac); dual band (2.4GHz and 5GHz); HT80 with MIMO
iPad
* Wi‑Fi (802.11a/b/g/n/ac); dual band (2.4GHz and 5GHz); HT80 with MIMO


Technical Information:

|-----------|------------|------------|------------|------------|
| Name | Speed | Indoor Range | Frequency | Released|
| Wireless AC | 1 Gbps | 115 Feet | 5 GHz | 2013 | 
| Wireless N | 300 Mbps | 230 Feet | 2.4 GHz, 5 GHz | 2009 |
| Wireless G | 54 Mbps | 125 Feet | 2.4 GHz | 2003 | 
| Wireless B | 11 Mbps | 115 Feet | 2.4 GHz | 1999 |

In reality, for Wireless N, typical speeds are more accurately around 130mbps or less without certain configurations and conditions being met.

References: 
* https://www.apple.com/ipad-9.7/specs/
* http://homenetworkadmin.com/wireless-b-vs-g-vs-n-vs-ac-difference/

## USB

User can connect the iPad to a computer via USB cable and transfer data to the device via iTunes (Apple provided software, not easy to use). 

The theoretical maximums are as follows:
In *bits* per second, that is:
* USB 1.1 = 12 Mbit/s
* USB 2.0 = 480 Mbit/s
* USB 3.0 = 5 Gbit/s
* USB 3.1 = 10 Gbit/s
In *Bytes* per second, that is:
* USB 1.1 = 1.5 MB/s
* USB 2.0 = 60 MB/s
* USB 3.0 = 625 MB/s
* USB 3.1 = 1.21 GB/s

iPad support USB 3.1

The real power comes from the USB 3.1 technology it uses, which is capable of the SuperSpeed 10Gbps data transfer rate.

Apple hasn't released the full specifications of Lightning as such, but tests on the standard cables show that the speeds are that of USB 2.0. This equates to 480mbps, which is a long way short of USB 3.1.

References:
* https://superuser.com/questions/138845/speed-comparison-between-usb-2-0-usb-3-0-esata-firewire-and-thunderbolt
* https://www.macworld.com/article/2039427/how-fast-is-usb-3-0-really-.html
* https://www.macworld.co.uk/feature/mac/usb-c-vs-lightning-3666439/

My Summary
* Apple’s strategy is to make mobile device wireless and they put big effort to improve it. 
* USB 3.1 is much faster than WIFI. WIFI is more convenient than USB, People can get it anywhere. 
* If transfer big amount of data to iPad via WIFI, try to use Wireless AC. If transfer data via USB, try to use USB 3.1. 
* Transfer data to iPad via iTunes and USB cable to iPad is inconvenience. I never get a good experience with iTunes software. We may check if apple provide API to access data on iPad from a computer program. 
* Beside technology, the company may setup certain rule/procedure to update iPad. Example:
    *  Centralize the update action. Assign a dedicate administrators and dedicate WIFI or USB environment to update the manuals on the device. The user gets the device from administrator.
    *  It is hard for normal user to use USB cable to update data. (I did not see anyone use USB cable to transfer data to iPad or install app on iPad in real life). If we design to have normal user to update the manual, it will be via WIFI. The key is to make sure user get high speed WIFI when they update.

Thanks
Jingjun
