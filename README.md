# Ada Xtensa ESP Light Runtime

Provides Ada light runtime support for the Xtensa ESP family of SOC devices.

## Project Status and Release Notes (alpha)
Project is in alpha stage
   - Runtime source files have been copied from **gnat_xtensa_esp32_elf** toolchain into new Alire crate
   - Alire has been properly configured for building
   - Successful crate build
   - Linker errors

## Requirements
- Alire 2.0.1 or higher 
- gnat_xtensa_esp32_elf 14.2.1 or higher

## Instructions
### Alire and toolchain installation
1. If not already installed, install Alire using one of the two methods below:

   - For quick installation visit https://www.getada.dev for further instructions.
   - For manual installation, visit https://alire.ada.dev and download Alire for your platform and follow installation instructions in https://alire.ada.dev/docs/ to install.

2. Issue the following commands in your terminal:
   ```
   git clone git@github.com:Joebeazelman/light_xtensa_esp.git
   cd light_xtensa_esp
   alr build
   ```

