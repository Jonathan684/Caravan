# Caravel Analog User

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![CI](https://github.com/efabless/caravel_user_project_analog/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_user_project_analog/actions/workflows/user_project_ci.yml) [![Caravan Build](https://github.com/efabless/caravel_user_project_analog/actions/workflows/caravan_build.yml/badge.svg)](https://github.com/efabless/caravel_user_project_analog/actions/workflows/caravan_build.yml)

---

| :exclamation: Important Note            |
|-----------------------------------------|

## Analog Chip

The following project implements an analog circuit from which we want to extract samples with digital circuits, for example, schim triger, and then a counter so that they are later analyzed in the riscV. The riscV can then send the data to the outside of the chip by using the UART.

## Run magic

    export PDK_ROOT=/usr/local/share/pdk/
    sudo magic -T XR -rcfile $PDK_ROOT/sky130A/libs.tech/magic/sky130A.magicrc

## Run xschem

    cp /usr/local/share/pdk/sky130B/libs.tech/xschem/xschemrc .
    xterm &
    xschem


Refer to [README](docs/source/index.rst) for this sample project documentation. 
