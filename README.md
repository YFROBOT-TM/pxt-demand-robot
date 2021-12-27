 
# Demand Robot
DEMAND ROBOT

## Basic usage

* Set the direction and speed of demandRobot motor

```blocks
 demandRobot.motorRun(demandRobot.Motors.ML, demandRobot.Dir.CW, 120)
 demandRobot.motorRun(demandRobot.Motors.MR, demandRobot.Dir.CCW, 120)
```

* Read ultrasonic sensor

```blocks
basic.showNumber(demandRobot.Ultrasonic(PingUnit.Centimeters))
```

* Stop the demandRobot motor 

```blocks
demandRobot.motorStop(demandRobot.Motors.ML)
```

* Read line tracking sensor

```blocks
demandRobot.enablePatrol(demandRobot.PatrolEnable.PatrolOff)
serial.writeNumber(demandRobot.readPatrol(demandRobot.Patrol.PatrolLeft))
```

* Turn on/off the LEDs

```blocks
demandRobot.writeLED(demandRobot.LED.LEDLeft, demandRobot.LEDswitch.turnOn)
```

* Read IR sensor value

```blocks
basic.showNumber(demandRobot.irButtonCode())
```


## License

MIT


## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)
