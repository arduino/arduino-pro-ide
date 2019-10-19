# Arduino Pro IDE
The Arduino IDE for advanced users and developers.

## Idea
The new Arduino IDE is a completely new Development Environment for Arduino Programming based on more modern technologies.
This repo is a preview of the final product and has to be considered as an unstable *alpha* version.

## Getting Started

### Download
You can find the last published version in the [Releases Section](https://github.com/arduino/arduino-pro-ide/releases) of this repo

### Install a core to support your board 
The Arduino Pro IDE does not provide pre-installed cores, to have board support you have to install a core by using the menu

    Tools -> Board Manager...

Then search for your board and install the proper core.

## User Feedback and Issue Report
We need your help in improving the product, before releasing the source code we want to move out of the alpha and we need your help.
Please test the Arduino Pro IDE and report us bugs or feature requests at: https://github.com/arduino/arduino-pro-ide/issues

## Technology
The Arduino Pro IDE is based on the following technologies:

* [Arduino CLI](https://github.com/arduino/arduino-cli)
 Used in daemon mode is providing all the main Arduino features
* [Eclipse Theia](https://github.com/eclipse-theia/theia)
The frontend of the application is based on this [Open Source IDE](https://theia-ide.org/) 
* [Electron](https://github.com/electron/electron)
The framework behind [Eclipse Theia](https://theia-ide.org/), allows to use web technologies on desktop environments

If you want to know more about the people involved please look at the [Contribution list](CONTRIBUTIONS.md)