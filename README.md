# SteamOS W11

These are some scripts that convert a Windows 10/11 installation into something similar to Valve's operating system: SteamOS.
This project is still a work in progress and hasn't been tested on Windows 10 yet.

## Installation
~~This part of information is not completely written and needs to be worked on. Stay tuned!~~

1. Download this repository by using the green button or your preferred method.
2. Verify that the App Installer is updated trough the Microsoft Store.
3. Run PowerShell as an administrator and navigate to the extracted files using `cd path\to\files`
4. Run the following command in order to automatically install the dependencies if needed and apply the modifications on your computer: `Set-ExecutionPolicy -Scope Process Bypass; .\setup.ps1`
    - This will reboot your system automatically so be sure to save anything important!
5. As an optional step, exit Steam after your system fully rebooted so you can also add `-steamdeck -gamepadui` to the launch options of the Steam shortcut (in the "Start in:" field trough its properties) on your desktop so it launches it with an interface similar to the Steam Deck.
    - Confirm the prompt that this will need administrator rights to apply if needed.