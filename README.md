
### Configuring Hardware Version
This branch uses a super basic HAL and as a result must be told what version of hardware it is running on. [Edit the config here](https://github.com/slapplebags/Tracksoar-Firmware/blob/BME280-support/Tracksoar/Firmware/tracksoar/config.h#L30) to have the corect version uncommented. Everything before V1.2 should work as it normally did on the old set of sensors.


# Tracksoar Firmware

This is a modified version of the [trackduino](https://github.com/trackuino/trackuino) firmware for the [Tracksoar](www.tracksoar.com) hardware.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to build and flash the project onto Tracksoar hardware.

### Prerequisites

Arduino 1.5 or greater
or 
Platform.io core

#### Platform.io

```
pip install -U platformio
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Arduino](https://arduino.org/) - Embedded libraries
* [Platform.io](http://platformio.org/) - Embedded systems framework

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/mkapuscik/habner-g12/tags). 

## Authors

* **Javi Martin** - *Initial work* - [trackuino](https://github.com/trackuino)
* **Mike Bales** - *Tracksoar porting* - [slapplebags](https://github.com/slapplebags)

See also the list of [contributors](https://github.com/slapplebags/Tracksoar-Firmware/contributors) who participated in this project.

## License

This project is licensed under the GPL v2 - see the [LICENSE.md](LICENSE.md) file for details
