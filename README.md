# buildJetsonTK1Kernel
Scripts to help build the kernel and modules on the Jetson TK1

These scripts are for building starting from a fresh flash of L4T 21.4 on a NVIDIA Jetson TK1. 

<strong>getKernelSources.sh</strong>

Downloads the kernel sources for L4T 21.4 from the NVIDIA website, decompresses them and opens a graphical editor on the .config file. 

<strong>buildKernel.sh</strong>

Compiles the kernel and modules using make.

<strong>copyzImage.sh</strong>

Copies the zImage file created by compiling the kernel to the /boot directory


<strong>Note:</strong> that you may want to save the newly built zImage and modules to external media so that can be used to flash a Jetson image.

For more information on building a kernel for the Jetson TK1:

https://devtalk.nvidia.com/default/topic/762653/-howto-build-own-kernel-for-jetson-tk1/
