ping between computer an vm

windows: ipconfig // 192.168.10.105 
linux - ifconfig (old) // 
route -n

ping 192.168.10.0
192.168.10.105 

delete network-
ifconfig eth0 0.0.0.0. netmask 0.0.0.0
ok - all deleted - now add with route / ip ...
ifconfig eth0 192.168.10.0 netmask 255.255.255.0
allocate external ip?


reconnect + ip + ping personal computer:

