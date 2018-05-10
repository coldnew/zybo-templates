# zybo-templates
Basic project template for Xilinx zynq-7000 ZYBO board

This project is based on [Digilent/ZYBO](https://github.com/Digilent/ZYBO), I keep the board file I need for different Vivado SDK.

To use this template, you must switch to the dir contains `create_project.tcl`, take `2018.1/linux_bd` as example:

```sh
cd 2018.1/linux_bd/proj
/opt/Xilinx/Vivado/2018.1/bin/vivado -mode batch -source create_project.tcl
```

Then you will see following directories created by vivado

```sh
.
├── cleanup.cmd
├── cleanup.sh
├── create_project.tcl
├── linux_bd.cache
├── linux_bd.hw
├── linux_bd.ip_user_files
├── linux_bd.srcs
└── linux_bd.xpr

4 directories, 4 files

```
