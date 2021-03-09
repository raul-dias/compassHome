# compassHome
An arduino based compass that will always point to 'home'

## Components List
1. Arduino NANO
2. Gps Module
3. Compass Module
4. Stepper Motor
5. Batter with 5v controller
       
## Connections  
GPS         Compass     Stepper
vcc - 5V    vcc - 5v    vcc - external 5v
GND - GND   gnd - GND   gnd - GND
RX - D3     SCL - A5    In1 - 8
tx - D4     SDA - A4    In2 - 9
                        In3 - 10
                        In4 - 11 
