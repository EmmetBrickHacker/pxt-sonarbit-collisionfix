# Name collison resolving alternative extension for ELECFREAKS sonar:bit
based on [sonarbit Package](https://github.com/elecfreaks/pxt-sonarbit) by [ElecFreaks](https://www.elecfreaks.com/) with minor assistance from [Tinkercademy](https://tinkercademy.com/).
This alternative extension for ELECFREAKS sonar:bit package was developed by [Emmet BrickHacker](https://github.com/EmmetBrickHacker) because someone thought it was a good idea to assign the same blockId to the controls of two different ultrasonic sensors (specifically sensors [ELECFREAKS Octopus Sonar:bit](https://wiki.elecfreaks.com/en/microbit/sensor/octopus-sensors/sensor/octopus_ef04089/) and [ELECFREAKS PlanetX Ultrasonic Sensor](https://wiki.elecfreaks.com/en/microbit/sensor/planet-x-sensors/Plant_X_EF05007/))


## Code Example
```JavaScript
basic.forever(() => {
    basic.showNumber(sonarbit.sonarbit_distance(DigitalPin.P16))
    basic.pause(100)
})

```

## License
MIT

## Supported targets
for PXT/microbit (The metadata above is needed for package search.)

