# lgpio-SPI
This program uses SPI with a MCP3008 chip to convert Analog to Digital (ADC) (MISO/MOSI)

![](https://github.com/eugenedakin/lgpio-SPI/blob/main/ScreenGrab.png)

The MCP3008 chip converts analog signal to digital signals by using the SPI protocol on the Raspberry Pi 4 with Xojo.

Install instructions are:
1) sudo apt install swig python-dev python3-dev
2) sudo apt install python-setuptools python3-setuptools
3) wget http://abyz.me.uk/lg/lg.zip
4) unzip lg.zip
5) cd lg
6) make
7) sudo make install
8) create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
9) give the executable permission to run with something like: 'sudo chmod +x HelloWorldBlink'
10) run the program with something like: 'sudo ./libGPIODSPI'
