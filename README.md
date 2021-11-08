# armv7-torch-builds

There are no official armv7l builds for pytorch past version v1.0.0 and torchvision past v0.4.0, so here are some that I built. Tested and working on Raspbian 10 Buster on a Raspberry Pi 3 Model B v1.2.

The whl files were compiled from source in a Docker container emulating an armv7l architecture using qemu. Trying to build from source directly on a Pi would take several days. See https://ownyourbits.com/2018/06/27/running-and-building-arm-docker-containers-in-x86/ for more information on this process.
