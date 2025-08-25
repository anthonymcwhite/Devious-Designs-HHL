# The Wifi Dev Board for Flipper Zero <br>
<tt>Here you can find notes that I have taken while experimenting with the FZ + Wifi Dev Board and any usable modules or techniques.</tt></br>

---

### Marauder Firmware
<tt>The Marauder Firmware has become relatively popular with hardware hackers, and professional red teamers alike. The particular Wifi Dev board that I purchased, fortunately came with the ESP32 Marauder Firmware pre installed/flashed. So I was able to avoid the somewhat tricky manual set up.</tt>

Common Terms & Definitions related to the Marauder features </br>
- Probe Request Sniff: probe requests are a type of WiFi management frame. They are not encrypted, since they contain no user data. They are used simply for network discovery.
- SSID: server side identifier.
- Beacon Sniff: sniffs active access points, lists by SSID.
- Scan AP's: looks for access points and then lists them.
