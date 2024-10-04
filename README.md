# 3D Mapping System 🚀
[Link to LinkedIn post with the video](https://www.linkedin.com/posts/miguel-vega1_opensource-openaccess-robotics-activity-7244433883042115584-Edhx?utm_source=share&utm_medium=member_desktop)

Welcome to the **Open-Source 3D Mapping System** project! This repository contains everything you need to build your own 3D mapping system, including **3D-printable modular parts**, sensor initialization scripts, and code to start SLAM (Simultaneous Localization and Mapping) systems. You'll also find code for **data recording** from the sensors.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [3D Parts](#3d-parts)
- [SLAM System](#slam-system)
- [Citing](#citing)
- [Acknowledgements](#acknowledgements)
- [Resources](#resources)

## Overview

🤖 **Want to build your own 3D mapping system?** You're in the right place!

I've just open-sourced the **3D-printable modular parts** that allow you to build a versatile system for both **robots** and **handheld** applications. These components were originally designed for the **Go1-legged robot**, but can be adapted for use with any robot with a flat surface, or even used as a standalone handheld system.

You can explore and download the 3D-printable parts from the following link:

👉 **[Download 3D Parts](https://a360.co/46tjrIc)**

## Features

- **Modular Design**: Compatible with different configurations for robots or handheld systems.
- **Supports**: 
  - **Ouster 3D LiDAR**
  - **4 Intel D435i RealSense cameras**
  - **NUC mini PC**
  - **Two batteries**
- Automatic initialization of sensors and starting SLAM systems.
- Easy recording of data for research and analysis.

## Getting Started

To get up and running with the system:

1. **Download the 3D parts** and assemble the hardware components according to your use case (robot or handheld).
2. Clone this repository:
   ```bash
   git clone https://github.com/MigVeg/MappingSystem.git
   ```

3. Follow the setup guide to initialize the sensors and start the SLAM system, you can do that simply by runing the following command:
   ```bash
   bash auto_run
   ```
   
4. If you plan to use the data later, it’s advisable to focus on recording only and avoid running the SLAM system simultaneously. The SLAM system is resource-intensive and can quickly discharge the batteries.

## 3D Parts

The modular mounting system allows easy attachment of sensors to your robot or for handheld use. It's originally designed for the **Go1-legged robot**, but its flexibility makes it usable for any robotic platform with a flat surface.

👉 [Download 3D Parts](https://a360.co/46tjrIc)

For details on how the components fit together, check out our research paper:

👉 [Research Paper](https://lnkd.in/dm2inuBS)

## SLAM System

The code in this repository allows you to initialize the following sensors:

- **Ouster 3D LiDAR**
- **4 x Intel D435i RealSense cameras**

Once the sensors are initialized, you can start the SLAM system and capture live data. You can also record this data for further research and analysis.

## Citing

If you use this project or its 3D parts for academic research, please make sure to cite the following paper and resource:

- [Cite our paper](https://arxiv.org/abs/2409.15253)
- [Cite also this resource](https://mediatum.ub.tum.de/1459253?show_id=1750434)
  
```bibtext
@inbook{MountingSystem2024:vega:paper,
  doi = {10.13154/294-10094},
  url = {https://hss-opus.ub.ruhr-uni-bochum.de/opus4/10094},
  author = {Vega Torres, Miguel Arturo and Pfitzner, Fabian},
  language = {en},
  title = {Investigating robot dogs for construction monitoring},
  publisher = {Ruhr-Universität Bochum},
  year = {2023},
  copyright = {Creative Commons - CC BY 4.0 - Namensnennung 4.0 International}
}

@misc{MountingSystem2024:vega:data,
	author = {Vega-Torres, Miguel A. and  Borrmann, André},
	title = {{CMS Sensor Mounting System}},
	year = {2024},
	type = {Dataset},
	abstract = {The data provided here includes the mounting system, which enable the mounting of multiple sensors on a robot. Although it was specifically developed for the Go1-legged robot, it can be utilized on any robot with a flat surface or as a handheld system by detaching the sensors from the components that hold the PC and batteries.
The mounting system is designed to accommodate an Ouster 3D LiDAR and four D435i RealSense cameras. Additionally, it supports a NUC mini PC and two batteries. For detailed information about the connections and usage of the system, please refer to this https://mediatum.ub.tum.de/node?id=1720803
Also, you can see the model in 3D: https://a360.co/46tjrIc},
	keywords = {3D Mesh; Inventor; Mounting; LiDAR; Camera; Mapping; SLAM},
	doi = {10.14459/2024mp1750434}
}
```
## Acknowledgements

✨ Special thanks to **Felix Eickeler** for helping develop the first versions of this system. And to **Fabian Pfitzner** for the collaboration during the writing of the paper and recording of the sequences at the construction site! 👷‍♂️🏗

🌟 Also, thanks to:
- André Borrmann, Denis Wohlfeld, Alexander Braun, Martin Slepicka

## Resources

- 🎯 This project is a continuation of the system presented [here](https://lnkd.in/eMDWDJYK)
- 👀 Check out what's possible with this system [here](https://lnkd.in/dBX5q_-t)
