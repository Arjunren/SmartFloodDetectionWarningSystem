# Troubleshooting — SmartFloodDetectionWarningSystem

| Symptom | Check |
|---|---|
| No water probe signal | Verify sensor power, grounds, pin table, voltage limits, and module orientation. |
| Invalid sample | Check 0–4095 ADC counts range and sensor calibration. |
| Wi-Fi disconnected | Check SSID, 2.4 GHz coverage, and local network policy. |
| MQTT disconnected | Check broker DNS, port 8883, CA PEM, device credentials, and publish ACL. |
| Unexpected alert | Inspect raw water probe signal and reserved; calibrate the threshold in `logic.h`. |
| Build failure | Confirm PlatformIO is installed and dependency downloads are permitted. |

This prototype is not a certified life-safety or property-protection system.
