# lorawan_bike_gps
This project aims to implement a GPS tracker with the capability to send data with LoRaWAN (e.g. [TheThingsNetwork](https://www.thethingsnetwork.org/). 
It could work like this: 
- [ESP32](https://www.espressif.com/en/products/socs/esp32/overview) for computing and even providing Bluetooth for smartphone-connections 
- [Semtech SX1262](https://www.semtech.com/products/wireless-rf/lora-transceivers/sx1262) for LoRa 
- [Beitian BN220](http://files.banggood.com/2016/11/BN-220%20GPS+Antenna%20datasheet.pdf) (GPS,GLONASS,Galileo,BeiDou,QZSS and SBAS)  

All of that could get combined with the [forumslader](http://www.forumslader.de/automatiklader/) for charging with a dynamo.
