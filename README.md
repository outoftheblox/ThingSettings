# ThingSettings
Settings for Things.

# Usage
Change the files in data.

Put mqtt settings in mqtt.txt
1st line: server
2nd line: port
3rd line: username
4th line: password
5th line: TLS enabled (true or false)

Put WiFi access point settings in wifi.txt
odd lines: ssid
even lines: password

# Run
```
pio run -e d1_mini --target uploadfs  --upload-port /dev/ttyUSB0
```
