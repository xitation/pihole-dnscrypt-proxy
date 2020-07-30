# pihole-dnscrypt-proxy
Docker, PiHole and dnscrypt-proxy together at last!

You will need to create a LAN network that is bridged to your LAN, to allow direct access to the PiHole container.
On Ubuntu/Debian you can create these bridges using the config in - interfaces file.
Once br0 exists, you need a network called LAN in Docker, i've provided an export of what my one looks like see - docker network inspect lan.json
