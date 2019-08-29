# DHT22 Sensor on Raspberry Pi 3 model B.

## Sensor Config.

#### Pin 1 is VCC (Power Supply)
#### Pin 2 is DATA (The data signal)
#### Pin 3 is NULL (Do not connect)
#### Pin 4 is GND (Ground)

## Raspberry -> DHT22 Circuit.


#### Place a 10k resistor between Pin 1 and Pin 2 of the DHT22
#### Wire Pin 1 of the DHT22 to Physical Pin 1 (3v3) on the Pi
#### Wire Pin 2 of the DHT22 to Physical Pin 7 (GPIO4) on the Pi
#### Wire Pin 4 of the DHT22 to Physical Pin 6 (GND) on the Pi

## Preparing the Raspberry

 `sudo apt update`

  `sudo apt upgrade`

  ### Python 3 and Pip

   `sudo apt-get install python3-dev python3-pip`

   ### Setuptools, Wheel and Pip

   `sudo python3 -m pip install --upgrade pip setuptools wheel`

   ### DHT python Library.

   `sudo pip3 install Adafruit_DHT`


