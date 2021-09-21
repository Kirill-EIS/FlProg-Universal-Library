# FlProg Library

This is a FLProg library with auto-selection and configuration for a connected controller (Arduino, ESP, STM, ANON). An additional advantage is the automatic detection of the loading environment of the finished program.
The library is optimized to minimize delays when executing the program on the controller, which allows you to avoid controller freezes.

The library has many blocks for working with various sensors, matrices and other devices. There are also blocks for working with data that have many settings for specific user tasks.

RT_00_HW_BASE_v.*** file for Arduino

EIS.01.SYSTEM ver.*** file for FlProg

_Unfortunately, at the moment the blocks are only available in Russian, but work is underway on other translation._

## List of available blocks

1. [Processes and tasks](#Processes-and-tasks)

    a. [Task manager](https://github.com/Kirill-EIS/FlProg-Universal-Library/wiki/Task-manager)

    b. [Multifunctional generator](#Multifunctional-generator)
    
    c. [Counters](#Counters)

    d. [Decoder](#Decoder)

    e. [Pulse fronts](#Pulse-fronts)

    f. [Float Conversion](#Float-Conversion)

    g. [Bitwise conversions](#Bitwise-conversions)

2. [Pins](#Pins)

    a. [Discrete output](#Discrete-output)

    b. [PMW output](#PMW-output)

    c. [Analog output](#Analog-output)

    d. [Discrete input](#Discrete-input)

    e. [Analog input](#Analog-input)

    f. [??? Touch input (Сенсорный ввод)](#Touch-input)

    g. [Hall sensor](#Hall-sensor)
    
3. [Console](#Console)

    a. [Output of variables](#Output-of-variables)
    
    b. [i2c scanning](#i2c-scanning)
    
   + [Additional console functions](#Additional-console-functions)
    
        c. [Pin output](#Pin-output)
        
        d. [Output of i2c addresses](#Output-of-i2c-addresses)
        
        e. [Output of line](#Output-of-line)
        
        f. [Text output](#Text-output)
        
        g. [Output of controller options](#Output-of-controller-options)
        
        h. [Output of console settings](#Output-of-console-settings)

4. [HD44780 display](#HD44780-display)

    a. [Setting up HD44780](#Setting-up-HD44780)
    
    b. [Output to HD44780](#Output-to-HD44780)
    
5. [Sensors](#Sensors)

    a. [DHT22](#DHT22)
    
    b. [DS1820](#DS1820)
    
    c. [HC-SR04](#HC-SR04)
    
    d. [HTU21](#HTU21)
    
    e. [BME280](#BME280)
    
    f. [MAX6675](#MAX6675)
    
6. [Extension registers](#Extension-registers)

    a. [74HC595](#74HC595)
    
    b. [MCP23x17](#MCP23x17)
    
    c. [PCA9685](#PCA9685)
    
    d. [TLC594](#TLC594)
    
7. [Debug options](#Debug-options)

    a. [Debug  pins](#Debug-pins)
    
    b. [Debug i2c addresses](#Debug-i2c-addresses)
    
    c. [Debug settings](#Debug-settings)
    
8. [User options](#User-options)

    a. [Custom pins](#Custom-pins)
    
    b. [Terminal options](#Terminal-options)
    
    c. [Choosing an architecture](#Choosing-an-architecture)
    
    d. [Selection of boards and devices](#Selection-of-boards-and-devices)
    
9. [Settings of parameters and devices](#Settings-of-parameters-and-devices)

    a. [Configuring i2c](#Configuring-i2c)
    
    b. [configuring SPI](#Configuring-SPI)
    
10. [Nextion display](#Nextion-display)

    a. [Initialization](#)
    
    b. [Otput of a variable](#)
    
    c. [Getting variables](#)

