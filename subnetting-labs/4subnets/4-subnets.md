network address = 192.168.40.0
no.of subnet=4
2^n=no. of subnet=2^2=4
N=2
11111111.11111111.11111111.11000000
255.255.255.192= subnet mask /26
no of block size=256-192=64
Usable hosts=64-2=62

1st subnet
subnetmask=255.255.255.192
Network ID=192.168.40.0
Range of Valid Host =  192.168.40.1-192.168.40.62
Gateway ip = 192.168.40.1
Broadcast address=192.168.40.63

2nd subnet
subnet mask = 255.255.255.192
Network ID= 192.168.40.64
Range of Valid Host = 192.168.40.65-192.168.40.126
Gateway ip=192.168.40.65
Broadcast address=192.168.40.127

3rd subnet
subnet mask = 255.255.255.192
Network ID= 192.168.40.128
Range of Valid Host = 192.168.40.129-192.168.40.190
Gateway ip=192.168.40.129
Broadcast address=192.168.40.191

4th subnet
subnet mask = 255.255.255.192
Network ID= 192.168.40.192
Range of Valid Host = 192.168.40.193-192.168.40.254
Gateway ip=192.168.40.193
Broadcast address=192.168.40.255

