# ssv6501
iComm / South Silicon Valley SSV6051 driver for Linux
In https://forum.libreelec.tv/thread/21117-unoffical-le-9-2-9-80-images-for-rk3229-rk3228/?postID=134198#post134198
Feb 3rd 2020
#59
chewitt said：
The reason the SSV6051P driver works on the RK BSP kernel (and current Amlogic BSP kernels) has nothing to do with RK having better open-source compatibility. It is simply due to RK using an old kernel. I forget the exact kernel version where things break, but once you move beyond Linux 4.11 or 4.12 there are major crypto API changes and the driver no longer compiles. If you're lucky RK might task one of their internal devs to rewrite it at some point, but IMHO that's a long shot.
