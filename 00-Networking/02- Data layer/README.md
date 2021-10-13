# Data link layer

* Data link layer is the most `critical layer` in OSI model

* data link layer is divice to divice link

* for sending or receiving data to or from the internet data link layer is supporting the transfer of that data

## key points in data link table

* identifiable devices

* media access control (sharing)

* collision detection

* unicast 1:1

* broadcast 1:all

* switches - like hubswith super powers (layer-2)

## Data link frame

* layer-2 runs over layer-1

* layer-2 network needs functional layer-1 network to operate

* higher layers build on lower layers for adding features and capabulities

* layer-2 network also runs as layer-1 network(copper, fibre, wifi)

```
    Ethernet 

    * Ethernet is a way of connecting computers and other network devices in a physical space.

    * This is referred to as a local area network (LAN)

```

* layer-2 uses frame work for sending or receiving data

* layer-2 also have unique `hardware address` or (MAC address) for every device on a network

- mac address is a hexadecimel address (48 bits)

* layer-2 or ethernet frame is shared through shared medium trasmiteed to layer-1

```
    layer-2 provides frame and layer-1 handles physical transmission onto and from the physical shared medium

```

## how data link layer works ?

* data link layer uses `switces` instead of hobe

* every device on this has unique IP address 

```
   Switches

   * switces are very intelligent 
   * switces maintain `mac address table`
   * switces update mac address table when it any device reaches to it
   * switches store and forward to destnation address

```

* each port has separate collison domain 

* if any collision occurs (it will occur to certain port only) not to every device


