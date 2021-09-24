# FlProg Library

This is a FLProg library with auto-selection and configuration for a connected controller (Arduino, ESP, STM, ANON). An additional advantage is the automatic detection of the loading environment of the finished program.
The library is optimized to minimize delays when executing the program on the controller, which allows you to avoid controller freezes.

The library has many blocks for working with various sensors, matrices and other devices. There are also blocks for working with data that have many settings for specific user tasks.

RT_00_HW_BASE_v.*** file for Arduino

EIS.01.SYSTEM ver.*** file for FlProg

_Unfortunately, at the moment the blocks are only available in Russian, but work is underway on other translation._

## List of available blocks

1. Processes and tasks

    a. [Task manager](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Task-manager)

    b. [Multifunctional generator](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Multifunctional-generator)
    
    c. [Counters](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Counters)

    d. [Decoder](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Decoder)

    e. [Pulse fronts](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Pulse-fronts)

    f. [Float Conversion](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Float-Conversion)

    g. [Bitwise conversions](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Bitwise-conversions)

2. Pins

    a. [Discrete output](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Discrete-output)

    b. [PMW output](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/PMW-output)

    c. [Analog output](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Analog-output)

    d. [Discrete input](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Discrete-input)

    e. [Analog input](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Analog-input)

    f. [??? Touch input (Сенсорный ввод)](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Touch-input)

    g. [Hall sensor](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Hall-sensor)
    
3. Console

    a. [Output of variables](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-of-variables)
    
    b. [i2c scanning](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/i2c-scanning)
    
   + Additional console functions
    
        c. [Pin output](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Pin-output)
        
        d. [Output of i2c addresses](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-of-i2c-addresses)
        
        e. [Output of line](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-of-line)
        
        f. [Text output](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Text-output)
        
        g. [Output of controller options](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-of-controller-options)
        
        h. [Output of console settings](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-of-console-settings)

4. HD44780 display

    a. [Setting up HD44780](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Setting-up-HD44780)
    
    b. [Output to HD44780](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Output-to-HD44780)
    
5. Sensors

    a. [DHT22](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/DHT22)
    
    b. [DS1820](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/DS1820)
    
    c. [HC-SR04](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/HC-SR04)
    
    d. [HTU21](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/HTU21)
    
    e. [BME280](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/BME280)
    
    f. [MAX6675](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/MAX6675)
    
6. Extension registers

    a. [74HC595](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/74HC595)
    
    b. [MCP23x17](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/MCP23x17)
    
    c. [PCA9685](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/IN-DEVELOPMENT)
    
    d. [TLC594](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/IN-DEVELOPMENT)
    
7. Debug options

    a. [Debug pins](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Debug-pins)
    
    b. [Debug i2c addresses](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Debug-i2c-addresses)
    
    c. [Debug settings](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Debug-settings)
    
8. User options

    a. [Custom pins](#Custom-pins)
    
    b. [Terminal options](#Terminal-options)
    
    c. [Choosing an architecture](#Choosing-an-architecture)
    
    d. [Selection of boards and devices](#Selection-of-boards-and-devices)
    
9. Settings of parameters and devices

    a. [Configuring i2c](#Configuring-i2c)
    
    b. [configuring SPI](#Configuring-SPI)
    
10. Nextion display

    a. [Initialization](#)
    
    b. [Otput of a variable](#)
    
    c. [Getting variables](#)

