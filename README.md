# modular-processing-board-fw
Firmware for the board in the Modular-Processing-Board repo


## Build commands
```
mkdir build
cd build
cmake .. -DCMAKE_TOOLCHAIN_FILE = cmake/gcc-arm-none-eabi.cmake
make
```


## Flash command
```
st-flash --reset --connect-under-reset write mcu.bin 0x08000000

```