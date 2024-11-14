To find Class 
Class A 
0   0   0   0   0   0   0   0 = Min = 0
128 64  32  16   8   4   2   1 = 0 

0   1   1   1   1   1   1   1 = Max = 1
0   64  32  16  8   4   2   1= 127

Class B 
1   0   0   0   0   0   0   0 = Min 0 
128 64  32  16   8   4   2   1 = 128

1   0   1   1   1   1   1   1 = Max 1 
128 0   32  16  8   4   2   1 = 191


Class C 

1   1   0   0   0   0   0   0 = Min 0
128 64  32  16   8   4   2   1 = 192

1   1   0   1   1   1   1   1 = Max 1 
128  64 32  16  8   4   2   1 = 223


Class D
1   1   1   0   0   0   0   0 = Min 0
128 64  32  16   8   4   2   1 = 224

1   1   1   0   1   1   1   1 = Max 1 
128  64 32  16  8   4   2   1 = 239

Class E

1   1   1   1   0   0   0   0 = Min 0
128 64  32  16  8   4   2   1 = 240

1   1   1   1   1   1   1   1 = Max 1 
128  64 32  16  8   4   2   1 = 255


Private IP Addresses
Class       Network         Start IP        End/Last Ip
A           10.X.X.X/8      10.0.0.0        10.255.255.255
B           172.16.X.X/16   172.16.0.0      172.31.255.255
C           192.168.X.X/16  192.168.0.0     192.168.255.255

Reserved IP Address 
Class           Network Range           Purpose 
A               0.0.0.0/8               
B               127.0.0.0/8             Loopback address for testing H/W
C               169.254.0.0/16          APIPA if DHCP Failed (Automatic Private IP Addressing)