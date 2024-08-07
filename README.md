# CMSIS-DSP-MSPM0
New versions of CMSIS-DSP for Ti's MSPM0 MCUs.

## Usage
### From Source
Down load xmake at [xmake.io](https://xmake.io/#/), then edit the xmake.lua to match your toolchain paths.
Gcc and tiarmclang is supported, do as follows:
```
$  xmake f --toolchain=tiarmclang
$  xmake build cmsis-dsp-mspm0-ticlang
```
Tested under arm-none-eabi-gcc 13.1 and ticlang 3.43 LTS.

### From my precompiled binary
Download the library from this reps's release, add Include to ur IDE's include path or use -IInclude then
add the .a filed to linker's path to ur IDE or use in build command like -llibcmsis-dsp-mspm0-gcc.a.

Build screenshot under Ti's CCS Theia.
![Pic](https://raw.githubusercontent.com/DCZYewen/CMSIS-DSP-MSPM0/master/running.png)
