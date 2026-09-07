Arduino Libraries Required for Compiling the MQTT Codes

    ArduinoHttpClient by Arduino. Version: 0.6.1
    Arduino_DebugUtils by Arduino. Version: 1.50
    Arduino_ESP32_OTA by Arduino. Version: 0.3.1
    ArduinoJson by Benoit Blanchon. Version: 7.4.3
    LiquidCrystal I2C by Frank de Brabander. Version: 1.1.2
    PubSubClient by Nick O'Leary. Version: 2.8

If these libraries are not installed in Arduino IDE, the Codigos_ino_mqtt codes cannot be executed.

MQTT
"giirob/pr2/station/mesa/status" // read
"giirob/pr2/station/mesa/commands/TEMP" // write

Wi-Fi:

Modify the following variables according to the Wi-Fi network being used:

#define NET_SSID    "UPV-PSK"          // Wi-Fi network name
#define NET_PASSWD  "giirob-pr2-2023"  // Wi-Fi network password


Temperature video:
https://upvedues-my.sharepoint.com/:v:/g/personal/allom14a_upv_edu_es/IQCf9RYgmYk_Q5Y-2YDL6bIvAYvTHe1x_SPTmzSEY7mGqEE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=HFD9Ch
