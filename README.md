# jellyfinopenrc
Just a openrc service for jellyfin that works with the AUR version.

## Installation
1. Install the jellyfin-bin package from the AUR

2. Create the service file in /etc/init.d. You can call it whatever, but i chose to call it jellyfind.

3. sudo chmod u+x /etc/init.d/jellyfind

4. sudo rc-update add jellyfind default

5. sudo rc-service jellyfind start
