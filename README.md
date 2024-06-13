# unraid_immich

This is the stack I'm using for Immich on Unraid

Notes:
- I added custom locations for Thumbnail & Encoded Video Locations, can comment out, if not desired.
- Custom Docker Networer Networks are used, best if you add Nginx Proxy Manager to the custom docker network, then connect using that.  If you do not want to use a proxy, then go to the "immich_server" and uncomment the "ports".  Then connect using the host and port.
- enabled for Nvidia
- permissions are container default, i.e. for unraid is not set to 99:100  You could modify with user=99:100, but I decided is not necessary as I don't access the files directly.
