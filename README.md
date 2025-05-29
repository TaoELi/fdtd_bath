# FDTD with Auxiliary Bath Fields (FDTD-Bath) for Condensed-Phase Polaritonics

This repo contains the input and post-processing files for the publications involving the FDTD-Bath approach developed in the [TEL research group](https://www.taoeli.org/).

## Install

The FDTD-Bath approach is implemented on top of the open-source FDTD package [MEEP](https://meep.readthedocs.io/en/master/). However, at this moment, this approach has not been merged into to the main version of MEEP. Users need to install [our modified MEEP code](https://github.com/TaoELi/meep) from source: https://github.com/TaoELi/meep. 

Because it is very tedious to install the MEEP package from source, a bash script is provided in [./install_guide/meep_install_CentOS9.sh](./install_guide/meep_install_CentOS9.sh) for smoothly installing the MEEP package in a clean CentOS 9 Linux system. The MEEP offical website also contains the discussion of [installing MEEP from source](https://meep.readthedocs.io/en/latest/Build_From_Source/).


## Data for FDTD-Bath publications

- [implementation_2025](./implementation_2025/)

This folder contains the input and postprocessing files for the initial implementation of the FDTD-Bath approach.