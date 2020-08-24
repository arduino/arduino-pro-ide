# Arduino Pro IDE 
The Arduino Pro IDE brings features that address the needs of advanced users whilst retaining continuity with the simple "classic" [Arduino IDE](https://github.com/arduino/Arduino).

*This repo is a preview of the final product and has to be considered as an unstable alpha version.*

## Idea
The Arduino Pro IDE is a completely new Development Environment for Arduino Programming based on more modern technologies. 

## Getting Started

### Download

You can download this alpha preview for testing and feedback from the [Releases Section](https://github.com/arduino/arduino-pro-ide/releases) of this repo.
*<b>Note</b>: This is not a production release!*

#### Nightly builds

These builds are generated every day at 03:00 GMT from the `master` branch of the (currently private) source repository and
should be considered unstable. In order to get the latest nightly build
available for the supported platform, use the following links:

Platform  | 32 bit                   | 64 bit                   |
--------- | ------------------------ | ------------------------ |
Linux     |                          | [Nightly Linux 64 bit]   |
Windows   |                          | [Nightly Windows 64 bit] |
macOS     |                          | [Nightly macOS 64 bit]   |

[Nightly Linux 64 bit]: https://downloads.arduino.cc/arduino-pro-ide/nightly/arduino-pro-ide_nightly-latest_Linux_64bit.zip
[Nightly Windows 64 bit]: https://downloads.arduino.cc/arduino-pro-ide/nightly/arduino-pro-ide_nightly-latest_Windows_64bit.zip
[Nightly macOS 64 bit]: https://downloads.arduino.cc/arduino-pro-ide/nightly/arduino-pro-ide_nightly-latest_macOS_64bit.dmg

> These links return an HTTP `302: Found` response, redirecting to latest
  generated builds by replacing `latest` with the latest available build
  date, using the format YYYYMMDD (i.e for 2019/Aug/06 `latest` is
  replaced with `20190806` )

### Arduino CLI 

The Arduino Pro IDE uses the `arduino-cli` binary found in the system's PATH or its own embedded one if the `arduino-cli` is not found.
So please make sure you have the latest version of the [Arduino CLI](https://github.com/arduino/arduino-cli) as described in the [How to Install the Arduino CLI](https://github.com/arduino/arduino-cli#how-to-install) doc,
or remove your `arduino-cli` from the system PATH.

You can check your `arduino-cli` version with

```
$ arduino-cli version
```

### Install a core to support your board 
The Arduino Pro IDE does not provide pre-installed cores, so, to have board support, you have to install a core by using the menu

    Tools -> Board Manager...

## User Feedback and Issue Report
Before releasing the source code we want to move out of the alpha and we want your feedback to do this! Please test the Arduino Pro IDE and report bugs or feature requests at: https://github.com/arduino/arduino-pro-ide/issues.

## Technology
The Arduino Pro IDE is based on the following technologies:

* [Arduino CLI](https://github.com/arduino/arduino-cli):
 Running in daemon mode, it provides all the main Arduino features
* [Eclipse Theia](https://github.com/eclipse-theia/theia):
The frontend of the application is based on this [Open Source IDE](https://theia-ide.org/) 
* [Electron](https://github.com/electron/electron):
The framework behind [Eclipse Theia](https://theia-ide.org/), allows users to use web technologies on desktop environments

If you want to know more about the people involved please look at the [Contribution list](CONTRIBUTIONS.md).

## Releases
This Repository doesn't hold source code yet. Its main use is to collect issues and keep track of them.
We regularly release new versions of the compiled tool. You can find them under "Releases"

Releases available at https://github.com/arduino/arduino-pro-ide/releases/
