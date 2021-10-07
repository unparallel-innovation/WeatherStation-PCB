# Unparallel Weather Station PCB

The Weather Station PCB is a board that together with, Software and 3D case allows anyone to build their low-cost weather station. The Weather Station PCB was made open source, so we are sharing in this repository the custom PCB design (Eagle and Gerbers files) and other information, as the BOM and item lists. The software for the weather station is also open-source and can be used as is, or freely customized to meet your own needs and requirements. A model for printing a 3D case for your weather station is also provided (both in other repositories).  
image  

The Weather Station PCB using low-cost hardware and a LoPy4 board. The LoPy4 board is equipped with several connectivity options (e.g. Sigfox, LoRa, Wi-Fi and Bluetooth). Currently, the weather station uses Sigfox and/or Wi-Fi to send the data to the cloud, however, the software can be extended to support other connectivity options. A Grafana dashboard is then used to display the historical weather data that is stored on the cloud.

The weather station uses an external sensor (AM2315) for reading temperature and relative humidity, a weather meter kit (SEN-15901) for wind speed, wind direction and precipitation. The weather station is powered from a Li-Ion battery that is charged with a photovoltaic panel which is also used to measure solar radiation. Due to the system’s low-power operation and solar energy harvesting features, it is energy autonomous and can be deployed in remote places.


## Measured parameters:
*	Temperature (ºC)
*	Relative Humidity (%)
*	Rain (mm/h)
*	Wind Speed (km/h)
*	Wind Gust Speed (km/h)
*	Wind Direction (degrees)
*	Wind Gust Direction (degrees)
*	Solar Radiation (W/m2)
*	Battery Voltage (V)

## Item list:
*	Unparallel Weather Station PCB
*	Unparallel Weather Station 3D printed case (optional)
*	AM2315 - Encased I2C Temperature/Humidity Sensor
*	Weather Meter Kit - SEN-15901
*	Li-Ion battery (recommended 3.65V; 8Ah)
*	2.5W Solar Panel (116x160mm)
*	Sigfox antenna (868MHz)
*	LoPy 4.0

This work was done in the context of SmartAgriHubs Research Project, which has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 818182

Note: the custom Weather Station PCB may be ordered via [PCBWAY](https://www.pcbway.com/project/shareproject/Unparallel_Weather_Station_PCB.html) web page.
