# icb_uboot_v2020_04
mx6q icb u-boot v2020.04 

# Download repository
    git clone https://github.com/kimhs000/icb-uboot-v2020.04.git
    cd icb-uboot-v2020.04

# Install cross compiler
    apt-get install gcc-arm-linux-gnueabihf

# Setup cross compiler
    export CROSS_COMPILE=arm-linux-gnueabihf-
    export ARCH=arm

# Build (imx6q)
    make distclean
    make mx6icb_config
    make
