# unraid_immich

This is the stack I'm using for Immich on Unraid

Notes:
- I added custom locations for Thumbnail & Encoded Video Locations
- Custom Docker Networer Networks are used, best if you add Nginx Proxy Manager to the custom docker network, then connect using that.  If you do not want to use a proxy, then go to the "immich_server" and uncomment the "ports".  Then connect using the host and port.
