# awesome-embedded-libraries
A curated list of awesome embedded libraries for sensors, peripherals, protocols, ML, etc.

Table of Contents:

- [Drivers](#drivers)
    - [Sensors](#sensors)
        - [Temperature/Humidity](#temperaturehumidity)
        - [Envrironmental](#envrironmental)
        - [Proximity](#proximity)
            - [Ultrasonic](#ultrasonic)
            - [Lidar](#lidar)
            - [Radar](#radar)
        - Pressure
        - Light
        - Vibration
        - Color
        - Level
        - Position
        - Accelerometer
        - Flame
        - Leak
        - Tilt
        - Mark
        - Flow/Float
        - Sound/Noise
        - Moisture
        - Viscosity
        - Gas/Chemical
        - Current/Voltage
        - Seismograph
        - Biometrics
        - Capacitive
            - Touch
            - Fingerprint
        - Flex/Force
        - Imaging
        - Infrared
        - Movement/Motion
        - Linear Displacement
        - NFC
        - Radiation
        - Magnetic
        - RFID
        - Water physical state
    - Communication Modules
        - GPRS
        - NB-IoT
        - Bluetooth
        - LoRa
        - SigFox
        - ZigBee
        - WiFi
    - Fuel Gauges
    - RTC
    - Memories
        - Flash
        - EEPROM
    - Displays
        - OLED
        - LCD
    - LED
    - Load Cell Amplifiers
    - Energy Harvesters
    - Encoders
        - Magnetic
        - Light
    - Motors
    - ADC/DAC
- Protocols
    - Application Layer
        - MQTT
        - MQTT-SN
        - CoAP
        - AMQP
        - XMPP
        - DDS (Data Distribution Service)
        - HTTP
        - M2M
        - LwM2M
        - 6LowPAN
    - Datalink Layer
        - LoRaWAN
        - Z-Wave
        - CAN
        - Ethernet
        - WiFi
    - Buses
        - UART
        - SPI
        - I2C
        - USB
- Machine Learning
    - TinyML
    - TensorFlow Lite
- Features
    - Button
    - Debouncing

---
## Drivers

### Sensors

#### Temperature/Humidity

| Sensor Model |   Connectivity   |      Range      | Accuracy | Resolution  | Power Supply | Operating Current | Standby Current |
|--------------|------------------|-----------------|----------|-------------|--------------|-------------------|-----------------|
|[DHT11](https://components101.com/sites/default/files/component_datasheet/DHT11-Temperature-Sensor.pdf)| 1-wire exclusive | T: 0°C to 50°C  |   ±1°C   |   16 bits   |   3.5-5.0V   |       0.3mA       |       60uA      |
|              |                  | H: 20% to 90%   |   ±1%    |             |              |                   |                 |
|[DHT22](https://components101.com/sites/default/files/component_datasheet/DHT22%20Sensor%20Datasheet.pdf)| 1-wire exclusive | T: -40°C to 80°C|  ±0.5°C  |   16 bits   |   3.5-5.5V   |       0.3mA       |       60uA      |
|              |                  | H: 0% to 100%   |    ±1%   |             |              |                   |                 |

Adafruit's Arduino DHT family low-cost sensors library ([DHT11](https://components101.com/sensors/dht11-temperature-sensor), [DHT22](https://components101.com/sensors/dht22-pinout-specs-datasheet)) [[link]](https://github.com/adafruit/DHT-sensor-library) 

| Sensor Model |   Connectivity   |      Range      | Accuracy | Resolution  | Power Supply | Operating Current | Standby Current |
|--------------|------------------|-----------------|----------|-------------|--------------|-------------------|-----------------|
|[AHT20](https://cdn-learn.adafruit.com/assets/assets/000/091/676/original/AHT20-datasheet-2020-4-16.pdf?1591047915)| I2C | T: -40°C to 85°C  |   ±0.3°C   |   20 bits   |   2-5.5V   |       23uA       |       0.25uA      |
|              |                  | H: 0% to 100%   |   ±2%    |             |              |                   |                 |

Adafruit [AHT10](https://www.electroschematics.com/temperature-sensor/)+[AHT20](https://learn.adafruit.com/adafruit-aht20) Humidity and Temperature Sensor library for Arduino [[link]](https://github.com/adafruit/Adafruit_AHTX0)

enjoyneering [[link]](https://github.com/enjoyneering/AHTxx)

Seeed-Studio Arduino [[link]](https://github.com/Seeed-Studio/Seeed_Arduino_AHT20)

BMP180 Temperature and Barometric

BMP280 Temperature and Barometric

BME280 Temperature, Humidity, and Air Pressure

DS18B20 One Wire Temperature Sensor

AF5485

AM2311A

LM35DZ (calibrated in Celsius), LM335 (calibrated in Kelvin), LM34 (calibrated in Fahrenheit)

TMP36

LM75

TH02



#### Envrironmental

#### Proximity

##### Ultrasonic

##### Lidar

##### Radar

