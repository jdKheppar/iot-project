# ESP8266 MQTT LED Control

This project demonstrates how to control an LED connected to an ESP8266 microcontroller using MQTT. The ESP8266 connects to a WiFi network, subscribes to an MQTT topic, and reacts to incoming messages to turn the LED on or off.

## Requirements

- ESP8266 microcontroller
- Arduino IDE with ESP8266 support
- Libraries:
  - ESP8266WiFi
  - PubSubClient

## Configuration

Update the following constants in the code to match your network and MQTT broker settings:

```cpp
const char* ssid = "YourWiFiSSID";
const char* password = "YourWiFiPassword";
const char* mqtt_server = "your_mqtt_broker";
const char* mqtt_topic = "esp/led";
```
