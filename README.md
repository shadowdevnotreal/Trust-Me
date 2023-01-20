<p align="center">
Trust-Me
</p>
<p align="center">
Trusted Installer Monitor for Malware
</p>

<p align="center">
  <img width="400" src="https://github.com/shadowdevnotreal/Trust-Me/blob/main/Images/trust%20me.png">
</p>

<p align="center">
  <img width="180" src="https://github.com/shadowdevnotreal/Trust-Me/blob/main/Images/chat%20GPT3.png">
</p>

<a href="https://www.buymeacoffee.com/notarealdev" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>

## CODE has not been compiled yet = LOOKING FOR TESTERS when I am done. Videos coming. ##


## Basic Description
Trusted Installer is a vital part of Windows. This will create a new service that will monitor if this service gets stopped, started, or paused.
The code creates a new class called "TrustedInstallerWatcherService" that derives from the System.ServiceProcess.ServiceBase class. This class contains the code for the Windows service.

This script should help remediate this problem for you!

## Features
* The first line of code gets the path to the user's desktop.
* The second line combines the desktop path with the name of the log file ("trustedinstaller.log").
* The third line uses the File.AppendAllText method to append a string to the log file.
** The string contains the current date and time, followed by a message indicating that a trusted installer was detected.
* Trusted installer gets turned off = notified.
* Trusted installer gets turned on = notified.
* Trusted installer gets put to sleep = notified.
* Just updated it to an automated install, and this will DL the newest sigverif from Microsoft and compare the log from this app with the log generated from sigverif!


## Installation

```sh
1. Download repository.
2. Move to your desired location.
3. Make sure to check the script and edit the folder names and locations. By default it wants to install on your desktop.
```

### Menu
```sh
1. Install Trusted Installer Watcher
2. Uninstall Trusted Installer Watcher
3. Run sigverif and save output to desktop
4. Compare sigverif output to Trusted Installer Watcher log
5. Play game while installer does its thing.
6. Quit
```

## License
GNU Affero General Public License v3.0


Check out his git, he is considered a contributor to this project
https://github.com/tahkisis

Donations to my broke a$$:
* Bitcoin (BTC) Address: bc1qa27kjjqacshg3szwvr5rr48dfwfdfrtyu8agd4
