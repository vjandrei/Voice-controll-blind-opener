# Voice controlled blinds opener

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/RTZhS4Dwv1M/0.jpg)](https://www.youtube.com/watch?v=RTZhS4Dwv1M)

I participated in a challenge by Alexa and LEGO MINDSTORMS where I designed and executed automated voice controll blind opener.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install ev3dev for programming your EV3 Brick
Instal Visual Studio Code for editing code
Install Alexa Gadgets Python Software on your EV3 Brick

[See more here ](https://www.hackster.io/alexagadgets/lego-mindstorms-voice-challenge-setup-17300f) -lego-mindstorms-voice-challenge-setup

### Installing

There is two folder 
* alexa-js -  all code needed to run on the Alexa skill environments
* ev3-python - main.py is the file run by EV3 you need to create main.ini file go but your Alexa product Amazon ID and Alexa Gadget Secret

Create in the ev3-python folder main.ini and copy the code from below.
```
[GadgetSettings]
amazonId = YOUR_GADGET_AMAZON_ID
alexaGadgetSecret = YOUR_GADGET_SECRET

[GadgetCapabilities]
Alexa.Gadget.StateListener = 1.0 - wakeword
```

## Authors

* **Andreas Koutsoukos** - *Initial work* - 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

