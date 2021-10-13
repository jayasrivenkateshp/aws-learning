# 01-Physical layer

* physical shared medium

* standards for transmitting onto the medium

* standards for receibing from the medium 

* no access control

* no unique identified devices

* no device => device communication

## there are two cases how a physical layer works ?

### case 1 :-

* you have 2 devices in your home 

* two players are playing in 2 devices

* the 2 laptops with **network cards** communicating with each other

* binary `0` and `1` are trnsmitted onto shared medium 

 - physical medium can be copper(electrical), fiber(light), wifi(RF)

* the devices can use point to point layer wall(fancy way of talking)

### case 1 :-

* in this we are adding another 2 devices (total 4)

* 4 devices cannot communicate with each other directly

* we are using `4 port hobe`

* 4 devices are connecting with 4 port hobe with each network card

* 4 transmits to physical media

* only 1 device can transmit in shared media

* if multiple devices transmit at` once - a collison occurs`

**physical layer has no media access control and no collision detection**

## Disadvantages :-

> layer 1 can`t able to detect when collison occurs

> layer 1 doesn`t have any intelligence

> in layer 1 there is high chances of data corruption