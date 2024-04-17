# Private Projects:

## [Monitoring Füllstand Zisterne](https://github.com/BernH4/zisterne_fuellstand/tree/master)
Kurzbeschreibung: Energiesparende HW und Software (Barebone ESP12 in Verbindung DeepSleep + trennen von Spannungsversorgung Sensorik während dieser Zeit)  misst mithilfe von Ultraschallsensor Füllstand einer Zisterne.
Daten werden per MQTT an NodeRed zur Datenaufbereitung gesendet. Die in InfluxDB gespeicherte Daten werden in Grafana visualisiert.
Bei einer Übertragung der Daten alle 30 Minuten per WiFi hält ein 3000mAh 18650 Lithium Ionen Akku etwa ein halbes Jahr.

![cistern_front](https://github.com/BernH4/BernH4/assets/62931413/2a126f26-6f6a-4fc9-baca-ba43090b1766)
![cistern_back](https://github.com/BernH4/BernH4/assets/62931413/2d62dbe9-ac4e-4a2a-a791-7e6c0dc6853b)


## Energiebedarf Monitoring
Shelly 3EM sendet Messwerte per MQTT an NodeRed zur Datenaufbereitung.  Die in InfluxDB gespeicherten Daten werden in Grafana visualisiert.

![Monitoring_Energiebedarf_Grafana](https://github.com/BernH4/BernH4/assets/62931413/d8489623-af4a-4144-a2ee-1d88653e28a1)


## Visualisierung ESP + E-Ink Display

Anzeige von Daten eines ESP32 mit integriertem, energiesparendem E-Ink Display.
Der ESP holt sich die Daten direkt aus der Datenbank (InfluxDB).

![esp_eink](https://github.com/BernH4/BernH4/assets/62931413/f439a9e5-fc76-42bc-863d-aa01ddf12cc5)
