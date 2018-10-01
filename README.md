# FPGA USB 1.1, Slow-Speed Implementation

This is simple Application, which emulates a mouse. The cursor will move in a continual octagon.
See the [application example](https://github.com/pbing/USB/tree/master/doc/Microchip).


## Status
- FPGA proven

## Installation
```shell
git clone https://github.com/pbing/USB.git
cd USB
git submodule update --init --recursive
```

## Used Parts
- [Cyclone V GX Starter Kit](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=167&No=830&PartNo=1)

- The USB D+ and D- pads were [configured](https://github.com/pbing/USB/blob/master/doc/USB%20Pad%20Configuration.pdf)
  for low-speed (1.5 Mbit/s).

## Other IP
- [J1 CPU with Wishbone interface](https://github.com/pbing/J1_WB)
