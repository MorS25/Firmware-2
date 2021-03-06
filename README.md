OpenUAV flight controller and simulation stack, powered by http://px4.io, http://www.ros.org/, and http://gazebosim.org

See http://openuav.us for miscellaneous information on the project. 

To install the software stack on a fresh Ubuntu 14.04 machine, follow the instructions at http://openuav.us/wiki/index.php/Software_Stack#INSTALLATION


[![UPenn/NSF PX4 Simulation Stack](https://www.dropbox.com/s/y6fetkbs5utv9kc/px4-sim-splash.jpg?dl=1)](https://www.youtube.com/watch?v=JhK4x5JImLA)

[![UPenn/NSF Pixhawk/PX4-based UAV](https://www.dropbox.com/s/xf39b8pcml4bh8z/upenn-f450-mocap-trial.jpg?dl=1)](https://www.youtube.com/watch?v=b0AhAHZMD1w)

FROM UPSTREAM
## PX4 Pro Drone Autopilot ##

[![Releases](https://img.shields.io/github/release/PX4/Firmware.svg)](https://github.com/PX4/Firmware/releases) [![DOI](https://zenodo.org/badge/22634/PX4/Firmware.svg)](https://zenodo.org/badge/latestdoi/22634/PX4/Firmware) [![Build Status](https://travis-ci.org/PX4/Firmware.svg?branch=master)](https://travis-ci.org/PX4/Firmware) [![Coverity Scan](https://scan.coverity.com/projects/3966/badge.svg?flat=1)](https://scan.coverity.com/projects/3966?tab=overview)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/PX4/Firmware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repository holds the [PX4 Pro](http://px4.io) flight control solution for drones, with the main applications located in the src/modules directory. It also contains the PX4 Drone Middleware Platform, which provides drivers and middleware to run drones.

*   Official Website: http://px4.io
*   License: BSD 3-clause (see [LICENSE.md](https://github.com/PX4/Firmware/blob/master/LICENSE.md))
*   Supported airframes (more experimental are supported):
  * [Multicopters](http://px4.io/portfolio_category/multicopter/)
  * [Fixed wing](http://px4.io/portfolio_category/plane/)
  * [VTOL](http://px4.io/portfolio_category/vtol/)
*   Releases
  * [Downloads](https://github.com/PX4/Firmware/releases)

### Users ###

Please refer to the [user documentation](http://px4.io) and [user forum](http://discuss.px4.io) for flying drones with the PX4 flight stack.

### Developers ###

  * [Developer Forum / Mailing list](http://groups.google.com/group/px4users)
  * [Guide for Contributions](https://github.com/PX4/Firmware/blob/master/CONTRIBUTING.md)
  * [Developer guide](http://dev.px4.io)


This repository contains code supporting these boards:
  * [Snapdragon Flight](http://dev.px4.io/hardware-snapdragon.html)
  * FMUv1.x
  * FMUv2.x ([Pixhawk](http://dev.px4.io/hardware-pixhawk.html), Pixhawk 2 and [Pixfalcon](http://dev.px4.io/hardware-pixfalcon.html))
  * FMUv4.x (Pixhawk X and [Pixracer](http://dev.px4.io/hardware-pixracer.html))
  * AeroCore (v1 and v2)
  * STM32F4Discovery (basic support) [Tutorial](https://pixhawk.org/modules/stm32f4discovery)

