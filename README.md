This repository contains scripts for creating boot images used for debug boards based on <a href="https://macrogroup.ru/">MacroGroup</a> <a href="https://diasom.ru/">modules</a>.<br>
The build system includes the following components (<b>Versions may differ for different boards</b>):
<li><a href="https://barebox.org/">barebox</a> 2024.09.0</li>
<li><a href="https://buildroot.org/">buildroot</a> 2023.11.2</li>
<li><a href="https://kernel.org/">kernel</a> 6.10</li>

##
To build a <b>DS-IMX8M-EVB</b> image get started with:
```bash
git clone https://github.com/MacroGroup/bsp.git
cd bsp
./ds-imx8m-evb.sh
```
After the script completes, the finished SD-card image will be located in the output/ds-imx8m-evb/images directory.

##
To build a <b>DS-RK3568-EVB</b> image get started with:
```bash
git clone https://github.com/MacroGroup/bsp.git
cd bsp
./ds-rk3568-evb.sh
```
After the script completes, the finished SD-card image will be located in the output/ds-rk3568-evb/images directory.

##
