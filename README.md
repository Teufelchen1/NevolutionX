# NevolutionX
Original Xbox dashboard created with nxdk.

![Screenshot](https://en.wikipedia.org/wiki/Hammer_and_sickle#/media/File:Hammer_and_sickle_red_on_transparent.svg "Screenshot")

## Motivation
As the XboxDev community grows, the need for an open-source, nxdk based dashboard arises. There are other dashboard alternatives i.e. XBMC but none of them are build using nxdk.

## Features
- [x] Basic Menu
- [x] Build-in FTP server
	- [x] IPv4 & IPv6
	- [ ] TLS
- [x] Application launcher
- [x] DVD launcher

### Projected
- [ ] World domination 
- [ ] Themes

## Build

In order to build NevolutionX you'll need to install [NXDK](https://github.com/XboxDev/nxdk) first.
To build NevolutionX you simply clone the repository and run `cmake` followed by `make`:
```sh
git clone https://github.com/dracc/NevolutionX.git
cd NevolutionX/
mkdir build
cd build
cmake ..
make
```
The xbox executable(`default.xbe`) will be inside the newly created `bin/`:
```sh
ls bin/
480.bmp 720.bmp default.xbe vegur.ttf
```
## Installation
Simply copy and run the `default.xbe` onto your xbox. 
Do not forget to copy the assets together with it.
There is no further configuration required. The FTP-server will start automatically with NevolutionX, you'll only need to provide a link and a DHCP-server. The username and password  is `xbox`.

## Credits

This software is build on top of other awesome projects:
- The new xbox development kit [NXDK](https://github.com/XboxDev/nxdk)
- Visit the lovely [XboxDev](https://github.com/XboxDev/XboxDev) community
## License
 NevolutionX is published under the MIT License. See [LICENSE](LICENSE) for more information.
 MIT © 2019 Lucas Eriksson

