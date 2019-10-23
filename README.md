# Arduino Pro IDE 
The Arduino Pro IDE bring features that address the needs of advanced users whilst retaining continuity with the simple "classic" Arduino IDE.

*This repo is an a preview of the final product and has to be considered as an unstable *alpha* version.*

## Idea
The Arduino Pro IDE is a completely new Development Environment for Arduino Programming based on more modern technologies. 

## Getting Started

### Download

You can download this alpha preview for testing and feedback from the [Releases Section](https://github.com/arduino/arduino-pro-ide/releases) of this repo. *Note this is not a production release!*

### Arduino CLI 

The Arduino Pro IDE uses the `arduino-cli` binary found in the system's PATH or its own embedded one if the `arduino-cli` is not found.
So please be sure you have the latest version of the CLI as described in the [How to Install the Arduino CLI](https://github.com/arduino/arduino-cli#how-to-install) doc,
or remove your `arduino-cli` from the system PATH

You can check your `arduino-cli` version with

```
$ arduino-cli version
```

### Install a core to support your board 
The Arduino Pro IDE does not provide pre-installed cores, to have board support you have to install a core by using the menu

    Tools -> Board Manager...

## User Feedback and Issue Report
Before releasing the source code we want to move out of the alpha and we want your feedback to do this! Please test the Arduino Pro IDE and report bugs or feature requests at: https://github.com/arduino/arduino-pro-ide/issues

## Technology
The Arduino Pro IDE is based on the following technologies:

* [Arduino CLI](https://github.com/arduino/arduino-cli)
 running in daemon mode provides all the main Arduino features
* [Eclipse Theia](https://github.com/eclipse-theia/theia)
The frontend of the application is based on this [Open Source IDE](https://theia-ide.org/) 
* [Electron](https://github.com/electron/electron)
The framework behind [Eclipse Theia](https://theia-ide.org/), allows to use web technologies on desktop environments

If you want to know more about the people involved please look at the [Contribution list](CONTRIBUTIONS.md)
