# RaspberryUtils

## Notes
Only tested on DHT22

## AdaFruit_DHT
### How to compile

* First, compile BCM2835 library, [see this gist](https://gist.github.com/kevin39/9776185974578438cf7e).
* Then, compile the module : 

```
gcc -o Adafruit_DHT_InternalPull Adafruit_DHT_InternalPull.c -lbcm2835 -std=gnu99 -lrt
```

### How to use
```
$ sudo ./Adafruit_DHT_InternalPull 22 19
Using pin #19
Data (40): 0x2 0x34 0x0 0xfd 0x33
Temp =  25.3 *C, Hum = 56.4 %
```
