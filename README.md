# ServerSetup
OTR Chat Server with Bittorrent sync for file sharing
Make your own secure instant messaging service for you and your friends for $35 (the cost of a raspberry pi). You could  take it further and setup your own secure file syncing/sharing service where your data is only on your devices. You could use a usb drive for extra storage or buy a hard drive dock for $50 and a 2TB 3.5inch hard drive for $90. 
Total cost $175. 
Securing your shit yourself: priceless

1. Dynamic DNS with noip
	http://raspberrypihelp.net/tutorials/29-raspberry-pi-no-ip-tutorial

2. Secure IM with ejabberd (XMPP) with use of an OTR chat client.
	http://thenewtech.info/2013/08/11/install-an-otr-chat-server-on-the-raspberry-pi/
	http://en.wikipedia.org/wiki/Off-the-Record_Messaging#Client_support

3. Adding USB storage
	http://elinux.org/RPi_Adding_USB_Drives#USB_Flash_and_Hard_Drives

4. Secure file syncing/transfer with bittorrent sync
	http://jack.minardi.org/raspberry_pi/replace-dropbox-with-bittorrent-sync-and-a-raspberry-pi/

5. Install Truecrypt (optional)
  http://www.carrier-lost.org/raspberry-pi-truecrypt-on-raspbian/

6. Rpimonitor to record performance (optional)
  http://rpi-experiences.blogspot.fr/

If you really wanted to go all out you can setup this server to be a tor hidden service
http://kendildonic.wordpress.com/2011/08/03/build-a-tor-hidden-service-onion-web-site-with-a-cheap-vps/
just ignore the lighthttp setup and configure your tor hidden service with the appropriate ports
