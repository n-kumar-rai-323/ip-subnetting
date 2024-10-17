Bit (s) => a bit has 2 possible values, 1 or 0 (On or Off)

Byte => a byte is 8 bits

Octet => An octet is just like a byte 8 bits, you often see byte or octet both being used.

Nibble => A nibble is 4 bits, used to represent Hexadecimal.

Network Address => In case of routing, the network address is provide path to transmit packets. We send IP packets to the right destination. 192.168.1.0 with subnet mask 255.255.255.0 is an example of a network address. 

subnet => A subnet is a network that you split up in multiple smaller subnetwroks. 

Broadcast address => the broadcast address is being used by applications and computers to send inforamtion to all devices within a subnet, 192.168.1.255 with subnet mask 255.255.255.0 is an example of a broadcast address.


Class of IP Address 

Class A => 2^24 = 16,777,214 connection 
N  (0-127)    H (0-255) change      H (0-255) change        H(0-255) change 
Bits        128     64      32      16      8       4       2       1
0           0       0       0       0       0       0       0       0
127         0       1   	1       1       1       1       1       1


Class B => 2^16 = 65234 connection 
N  (128-191)    H (0-255)     H (0-255) change        H(0-255) change 
Bits        128       64      32      16      8       4       2       1
128           0       0       0       0       0       0       0       0
191           1       0   	  1       1       1       1       1       1

Class C => 2^8= 254 connection 
N  (192-223)    H (0-255)     H (0-255)       H(0-255) Only change 
Bits        128       64      32      16      8       4       2       1
192           0       0       0       0       0       0       0       0
223           1       1   	  0       1       1       1       1       1

Class D	224 to 239	n/a	n/a	Multicasting.

Class E	240 to 254	n/a	n/a	Experimental.

Note : 0 is Main place who define city name
        255 is provider its provide all message to all ip adderess 