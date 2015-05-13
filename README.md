##openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own [VPN](http://en.wikipedia.org/wiki/Virtual_private_network) server in no more than a minute, even if you haven't used OpenVPN before. It isn't bulletproof but has been designed to be as unobtrusive and universal as possible.

###Installation
Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/drdada/openvpn-install/master/openvpn-install.sh --no-check-certificate -O openvpn-install.sh; bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

###Features
In addition to the original code
- Password for client cert
- Expires days for client cert
- List client cert before revoking them

###TODO
- Send ovpn file by mail (cert password mandatory?)

###I want to run my own VPN but don't have a server for that
You can get a little VPS for few $$

###Tanks to Nyr & Bouroo for original code
