# Baking Pi - Operating Systems Development

This repository contains code for the online course **Baking Pi - Operating Systems Development**. Please note that the original course is targeted at **Raspberry Pi 1** and is not compatible with Raspberry Pi 2/3/4. However, the code in this repository has been modified to work on a **Raspberry Pi 3 Model B**.

The purpose of modifying the code is to enable running the course material on a Raspberry Pi 3 Model B since the repository owner does not have access to a Raspberry Pi 1 for testing. These modifications were necessary to ensure compatibility with the newer hardware.

## Requirements

To work with this code, you'll need a **Raspberry Pi 3** for testing purposes. However, the compilation process can be carried out without a Raspberry Pi 3 by using the **gcc arm eabi toolchain**.

You can install the ARM gcc toolchain using the following commands:

For Arch Linux:
```bash
yaourt -S gcc-arm-none-eabi-bin
```

For Debian-based systems:
```bash
apt-get install gcc-arm-none-eabi
```

## Compiling and Running on Raspberry Pi 3

To compile and run the code on a Raspberry Pi 3, follow these steps:

1. Navigate to the appropriate lesson's subfolder in the `src/` directory:
   ```bash
   cd src/lesson_folder
   ```

2. Compile and run the code for the chosen lesson using the following command:
   ```bash
   LESSON=ok01 make
   ```

Please note that the code in this repository has been adapted to run on Raspberry Pi 3 Model B, and there might be differences from the original course content that was designed for Raspberry Pi 1. You can find more information about the course on the [Cambridge University website](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/).
