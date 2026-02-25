# Low-cost-modular-monitoring-system-for-indoor-lighting-assessment
It presents ecoDAQ, a low-cost and modular monitoring system developed for multi-domain assessment of indoor lighting performance &amp; visual comfort in real-world settings. The system integrates a light toolkit for spatial and spectral lighting measurements and a survey toolkit for simultaneous environmental monitoring and user feedback collection. 
The system integrates:
- A Light Toolkit for spatially resolved illuminance and spectral measurements
- A Survey Toolkit for synchronized environmental monitoring and subjective comfort assessment
-------------------------------------------------------------------------
# System Overview
ecoDAQ supports:
- Multi-point illuminance mapping
- CCT-augmented lux calibration
- Spectral Power Distribution (SPD) monitoring
- Real-time PMV and PPD calculation (ISO 7730 compliant)
- Synchronized subjective questionnaire collection
- Long-term time-series data logging
- Low-cost design with total hardware cost < 350 €
-------------------------------------------------------------------------
# Hardware Components
## Light Toolkit:
- Raspberry Pi
- 9 × TSL2591 light sensors
- 1 × AS7341 spectral sensor
- TCA9548A I2C multiplexer
- 3D-printed enclosure

## Survey Toolkit:
- Raspberry Pi
- 10-inch touchscreen
- SHTC1 (Temperature & RH)
- MD0550 airflow sensor
- MCP3008 ADC
-------------------------------------------------------------------------
# Software Architecture
- Python
- Docker
- InfluxDB (time-series database)
- Grafana (real-time dashboard visualization)
-------------------------------------------------------------------------
# License
MIT License
