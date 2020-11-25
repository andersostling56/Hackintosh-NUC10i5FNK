# Hackintosh NUC10i5FNK2
How I made the NUC10 to successfully run macOS Catalina and Big Sur

I started out a couple of weeks ago in order to learn more on Hackintosh and OpenCore. After much struggle and expermenting, and support from friendly Redditors, I finally got the NUC up and running on Catalina.
After a couple of days I decided to go for the Big Sur upgrade. I did not alter anything at all, just ran the MacOS updater from within Catalina. Everything worked just fine, with one little glitch. Sometimes the system does not wake up after resume (happens sporadically). The symptom is that mouse and keyboard are frozen, while the display shows the login screen.

My system is the NUC10i5FNK2 with an Intel i5 8625 CPU.
BENQ 4K screen with max resolution
Apple Magic keyboard and mouse
Ethernet and Wifi works. Ethernet is full speed, I have not measured Wifi.
All USB ports works nicely (3 USB-A and 2 USB-C). The screen is connected to the USB-C port on the backside, and I have an USB 3 hub connected to the front C-port. All pheripials that I have connected to the A-ports work as the should.

The config.plist file is complete with exception for the SystemUID which you need to create yourself. 
The machine model is specified as MacMini8,2

There are 2 images provided, one of the model label of the NUC and one screenshot

Happy Hackintoshing!
