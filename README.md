# NBoard-ESP8266
![front](https://github.com/DaiveeCZ/NBoard-ESP8266/assets/83717170/eaa8809f-da7b-4ff7-b95a-0da88e4f31a0)

Control board for RGB LED strips, based on ESP8266 platform. Powered by DC jack and controlled by Wi-Fi. Option to connect an external IR receiver for additional IR remote control support. Unfinished project at the stage of finished design which should work. However, the board was never manufactured.
### Its based and supossed to be a more compact version of [Matchbox-RGB-V2](https://github.com/DaiveeCZ/Matchbox-RGB-V2) which I also designed.

### Programming:
For this board the ESP8266 was already pre-flashed, so there is no header for external programmer. Hovewer board can be flashed using the testpoints on the bottom. You can also use the [F_Board](https://github.com/DaiveeCZ/F_Board-V1.1) programmer I designed, which is compatible with this board. (You have to solder thin wires to the testpoints).


![back](https://github.com/DaiveeCZ/NBoard-ESP8266/assets/83717170/d11c656f-f5af-4a26-9809-8ec45991b682)

## CAUTION: Board can work with 5V or 12V RGB LED stripes. BUT if you connect to the 12V power input and connect a 5V LED strip you will blow it up!!


# Pin map:
- 1 - R
- 2 - G
- 3 - B
- 4 - IR (for external receiver)
- 5 - 5/12V
- 6 - GND
- H1 - Vcc
- H2 - GND

