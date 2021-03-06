# Changed Launch Parameter to x64 bit Version of Arma3
If you want to change it to perfomance branch edit the following line to the correct .exe:

https://github.com/MildlyInterested/WindowsGSM.ARMA3/blob/master/ARMA3.cs/ARMA3_x64.cs#L36

# FASTER support
Master branch is setup to be basically take the [FASTER](https://github.com/Foxlider/FASTER) launch parameters (or just any other complete launch argument) as server config input and launch that.
Therefore the port selection in the GSM GUI doesn't work. Only the -port= parameter in the server config counts. 


# WindowsGSM.ARMA3
🧩 WindowsGSM plugin for supporting Arma 3 Dedicated Server 

## Requirements
[WindowsGSM](https://github.com/WindowsGSM/WindowsGSM) >= 1.21.0

## Installation
1. Download the [latest](https://github.com/BattlefieldDuck/WindowsGSM.ARMA3/releases/latest) release
1. Move **ARMA3.cs** folder to **plugins** folder
1. Click **[RELOAD PLUGINS]** button or restart WindowsGSM

### License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/BattlefieldDuck/WindowsGSM.ARMA3/blob/master/LICENSE) file for details
