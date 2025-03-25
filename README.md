### VL53L1X SENSOR

The VL53L1X is a state-of-the-art, Time-of-Flight (ToF), laser-ranging sensor with accurate ranging up to 4m, fast ranging frequency up to 50 Hz and typical full field-of-view (FoV): 27 °, for more tecnical information see [Datasheet](VL53L1X_DataSheet.pdf)

### Installation and Usage

1. Clone this repository:
    ```sh
    git clone https://github.com/Joserivera-tech/VL53L1X_driver_to_ESP32.git
    ```
2. Include the driver files and main.c in your project.
3. Imclude file paths to  your "CMakeList.txt" file
5. Modify `platform_esp32s3.h` to match your hardware setup if necessary.
6. Compile and flash the firmware to your ESP32.
