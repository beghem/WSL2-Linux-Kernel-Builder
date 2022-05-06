# WSL2-Linux-Kernel-Builder

![kernel-build](https://github.com/beghem/WSL2-Linux-Kernel-Builder/actions/workflows/build.yml/badge.svg)

+ Download one of the [Kernels](https://github.com/beghem/WSL2-Linux-Kernel-Builder/actions) (click the latest workflow run)
+ Create a `.wslconfig` file on `/mnt/c/Users/<user>/` and add a reference to the created image with the following.
    ```ini
    [wsl2]
    kernel=c:\\users\\<user>\\linux-msft-wsl-5.10.y-usbip-can
    ```

https://github.com/dorssel/usbipd-win
