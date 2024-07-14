# ETboard_Notice
## Arduino
### Version
- Arduino IDE: 2.0.
- Board : ESP32 2.0.14
- Library
 . WifiManager-2.0.14-beta
 . U8g2-2.33.15
 . EspMQTTClient-1.13.3 : Not compatabile with ESP32 V3
 . DHT_sensor_library-1.4.4
 . ArduinoJson-6.19.4
 . Adafruit_Unified_Sensor-1.1.6

## WiFi and Analog
-. WiFi 미사용시: 전 port analog 사용 가능
-. WiFi 사용시: ADC1(32~39) 채널만 사용가능, A0 ~ A5
