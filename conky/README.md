conkyrc [for UNIX systems]

This is my custom configuration file for Conky, a system monitoring tool. 
This should be placed in your home directory as ~/.conkyrc. Putting a copy into
your /root/.conkyrc, or into other users' ~/.conkyrc is acceptable, but, if you 
are looking for consistency across users, be sure that all copies mirror each 
other.

My version creates a simple top-horizontal status bar (with a transparent
background, so be sure that you have a neutral/dark solid color wallpaper for
your desktop, or at least one with low contrast, so you can view the stats 
clearly). 

The stats shown are: {CPU usage, RAM usage, Disk I/O, Network Upstream Usage, 
Network Downstream Usage}.

You will need to change the network card listed in the config file to the one in
your system - you can find your card's name with 'ifconfig' (if you use 
net-tools), or 'ip link show' (if you use iproute2).

Happy hacking!
