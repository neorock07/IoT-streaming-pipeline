# IoT Streaming Data Pipeline : From DHT11 to Power BI

## Setup ESP8266

Menggunakan kode pada file `dht.ino` dan `iot_configs.h`.

### Wiring 

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/139e538e-7678-4971-8365-aedba9c381d5" />

| NAME | PIN |
| :------ | :---------- |
| GND | GND    |
| VCC | 3V3   |
| DATA | D5  |

## Architecture System

<img width="1401" height="452" alt="DHT_PRJ drawio" src="https://github.com/user-attachments/assets/71aa4841-c51a-4fbc-a303-1ef6454a3c69" />

Developed an end-to-end IoT data pipeline using ESP8266 and DHT11 sensor to monitor temperature and humidity. The device sends data to Azure IoT Hub, 
which is then stored in Azure Blob Storage and processed in real-time with Azure Stream Analytics. Processed data is saved into Azure SQL Database and visualized
through an interactive Power BI dashboard for real-time and historical monitoring.

## Result (Power BI Dashboard)

![Screenshot 2025-08-14 222643](https://github.com/user-attachments/assets/dd17d2b5-2c90-4683-b190-6e351676bc90)
