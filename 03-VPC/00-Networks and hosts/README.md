# Structure of an IPV4 address 

* basically ip addresses are written in dotted decimal notation

* but computer only understands is binary notation `(0, 1)`

* example - 192.168.0.1
      - each part of the address is a binary octect 

# Networks and hosts

* every network has a `Network ID` and `Host ID`

* for example 

    - 192 . 168 . 0 . 1 - network id and host id
       |     |    |   |
    - 255 . 255 .255. 0 - subnet mask

* in these example `first three` are representing the `network id` and `last one` represents       
  the `host id`= `0`

* Every bit in the subnet mask `0` thats where the value can be assigned to `hosts`

* subnet mask is the easy way to look which portion is the network id and which portion is host id

* example  
   * network - 192-168.0.0
   * subnet mask - 255.255.255.0 - 24 bits

* the network and the subnet mask can be written in `192.168.0.0./24`

# classes of IPV4 address

there are 3 types of classes in IP address

| classes | starting address | ending address | total networks | usable addreses per network
| ------ | --------- | -------- | ------- | -------
| Class A 10.0.0.0  |10.0.0.1 | 10.255.255.254 | 126 | 16,777,214
|         255.0.0.0 |
| Class B 172.16.0.0  |172.16.0.1 | 172.16.255.254 | 16,382 | 65,534
|         255.255.0.0 |
| Class C 192.168.0.0  |192.168.0.1 | 192.168.0.254 | 2,097,150 | 254
|         255.255.255.0 |

