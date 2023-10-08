# Exercise 10

## Task:

193.16.20.35/29

**What is the Network IP, number of hosts, range of IP addresses and broadcast IP from this subnet?**

**Instruction:** Submit all your answer as a markdown file in the folder for this exercise.

## Solution

### Subnet mask

Since 5bits was borrowed from the host network we have: 

> 255.255.255. 2^7 + 2^6 + 2^5 + 2^4 + 2^3
> 
> 255.255.255.248.

### Number of network

The formular to find the number of network is `2^n`; 

  n =>  Indicates the network that was borrowed

  2^5 = 32
  So there are **32 networks**.


### Number of Ip address on each Network
2^n 

n => represents the total number of host bits

2^3 = 8

So there will be **8 ips available per network.**



### Number of host on each network
This signifies the total number of ip addresses you can assign on a device on each network.

The formular for this is : 2^n - 2.

n => signifies the number of bits remaining on the host

The reason for subtracting 2 is because the first ip address is reserved for the network id and the last ip address is reserved for the broadcast id.

2^3 - 2 = 6.

So, there will be six ip address available to be allocated on a network.





### Network IP  | Range of Host IP Addresses        | Broadcast ID
193.16.20.35   |    193.16.29.36  - 193.16.20.41    | 193.16.20.42

193.16.20.43   |    193.16.29.44  - 193.16.20.49    | 193.16.20.50

193.16.20.51   |    193.16.29.50  - 193.16.20.57    | 193.16.20.58

193.16.20.59   |    193.16.29.60  - 193.16.20.65    | 193.16.20.66

193.16.20.67   |    193.16.29.68  - 193.16.20.73    | 193.16.20.74

193.16.20.75   |    193.16.29.76  - 193.16.20.82    | 193.16.20.83

193.16.20.83   |    193.16.29.84  - 193.16.20.89    | 193.16.20.90

193.16.20.91   |    193.16.29.92  - 193.16.20.97    | 193.16.20.98

193.16.20.99   |    193.16.29.100 - 193.16.20.105   | 193.16.20.106

193.16.20.107  |    193.16.29.108 - 193.16.20.113   | 193.16.20.114

193.16.20.115  |    193.16.29.116 - 193.16.20.121   | 193.16.20.122

193.16.20.123  |    193.16.29.124 - 193.16.20.130   | 193.16.20.131

193.16.20.131  |    193.16.29.132 - 193.16.20.137   | 193.16.20.138

193.16.20.139  |    193.16.29.140 - 193.16.20.145   | 193.16.20.146

193.16.20.147  |    193.16.29.148 - 193.16.20.153   | 193.16.20.154

193.16.20.155  |    193.16.29.156 - 193.16.20.161   | 193.16.20.162

193.16.20.163  |    193.16.29.164 - 193.16.20.169   | 193.16.20.170

193.16.20.171  |    193.16.29.172 - 193.16.20.177   | 193.16.20.178

193.16.20.179  |    193.16.29.180 - 193.16.20.185   | 193.16.20.186

193.16.20.187 |     193.16.29.188 - 193.16.20.193   | 193.16.20.194

193.16.20.195  |    193.16.29.196 - 193.16.20.201   | 193.16.20.202

193.16.20.203  |    193.16.29.204 - 193.16.20.209   | 193.16.20.210

193.16.20.211  |    193.16.29.212 - 193.16.20.217   | 193.16.20.218

193.16.20.219  |    193.16.29.220 - 193.16.20.225   | 193.16.20.226

193.16.20.227  |    193.16.29.228 - 193.16.20.233   | 193.16.20.234

193.16.20.235  |    193.16.29.236 - 193.16.20.241   | 193.16.20.242

193.16.20.243  |    193.16.29.242 - 193.16.20.251   | 193.16.20.252

193.16.20.251  |    193.16.29.252 - 193.16.20.257   | 193.16.20.258

193.16.20.259  |    193.16.29.260 - 193.16.20.265   | 193.16.20.266

193.16.20.267  |    193.16.29.268 - 193.16.20.273   | 193.16.20.274

193.16.20.275  |    193.16.29.276 - 193.16.20.282   | 193.16.20.283

193.16.20.283  |    193.16.29.148- 193.16.20.154   | 193.16.20.155






