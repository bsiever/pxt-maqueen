 
# Maqueen

[Maqueen is an easy-to-use programming educational Robot](https://www.dfrobot.com.cn/goods-1802.html)
This is a minimal set of blocks for motors, LEDs, and distance sensor. 

## Basic usage

* Set the direction and speed of Maqueen motor

```blocks
 maqueen.motorRun(maqueen.Motors.M1, maqueen.Dir.CW, 120)
 maqueen.motorRun(maqueen.Motors.M2, maqueen.Dir.CCW, 120)
```

* Read ultrasonic sensor

```blocks
basic.showNumber(maqueen.Ultrasonic(PingUnit.Centimeters))
```

* Stop the Maqueen motor 

```blocks
maqueen.motorStop(maqueen.Motors.M1)
```


* Turn on/off the LEDs

```blocks
maqueen.writeLED(maqueen.LED.LEDLeft, maqueen.LEDswitch.turnOn)
```

## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  


## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)
