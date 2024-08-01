# Technical Overview: 02MPV

This document provides detailed technical specifications of the components within 02MPV system in Pforzheim, including:

1. **Solar Module**: DHM-54X10/FS Full Black PV Module ![Solar Module](img/01SolarModule_icon.svg)
2. **Microinverter**: Hoymiles HMS-600-2T Microinverter ![MicroInverter](img/02MicroInverter_icon.svg)
3. **Power Meter**: myStrom WiFi Switch ![PowerMeter](img/04PowerMeter_type_02_icon.svg)

Each component follows this structure:
1. **General Specifications**: 
   - Description and overview of the respective product.
2. **Mechanical Specifications**: 
   - Information regarding size, weight, materials, and other physical aspects.
3. **Operating Parameters**: 
   - Conditions such as temperature ranges, humidity, and other operational environments.
4. **Electrical Characteristics**: 
   - Voltage, current, power, and other electrical data.
5. **Resources**: 
   - Links or references to user manuals, data sheets, and other useful materials.
6. **Additional Specifications**: 
   - Further specific information or notes relevant to this component.
---
### Solar Module: DHM-54X10/FS Full Black PV Module ![Solar Module](img/01SolarModule_icon.svg)

1. **General Specifications**:
  - **Manufacturer**: DAH Solar Co., Ltd.
  - **Description**: A solar module provided by DAH Solar Co., Ltd., used as a sub-component in mini PV systems. Typically, a mini PV system incorporates two of these modules.
  - **Type**: Solar Module (PV Module)
  - **Model Type**: DHM-54X10/FS
  - **Product Name**: DHM-54X10/FS Full Black PV Module
  - **Number of Solar Modules**: 2
  - **Warranty**: 12-year
  - **Certifications**: TÜV, CE, INMETRO, PV CYCLE 
  - **Country of Origin**: China
2. **Mechanical Specifications**:
  - **Cells Type**: Monocrystalline
  - **Number of Cells**: 108 
  - **Glass Type**: 3.2mm High Transmission, Antireflection Coating
  - **Dimensions (mm)**: 1722 × 1134 × 32
  - **Weight (kg)**: 22
3. **Operating Parameters**:
  - **Maximum DC System Voltage (V)**: 1500 
  - **Operating Temperature Range (°C)**: -40 to +85
  - **Nominal Operating Cell Temperature (°C)**: 45±2
4. **Electrical Characteristics (STC)**:
   - ```Standard Test Environment (STC): Irradiance (W/m^2): 1000, Cell temperature (°C): 25```
   - **Maximum Power (W)**: 405
   - **Module Efficiency (%)**: 20.74
   - **Protection Class**: Class A
5. **Resources**:
  - **[Link to Datasheet](https://cdn.shopify.com/s/files/1/0740/0554/5265/files/DHM-54X10-FS-400-410W.pdf?v=1686821644)**
6. **Additional Specifications - Alignment**:
  - **Orientation (°)**: Southeast (Azimuth angle SE -58°)
    - > _Note:_ -90° is East, 0° is South, 90° is West, 180° is North
  - **Tilt Angle**: 35°
  - **Yield Optimization**: These settings do not provide the absolute highest yield.
---
### Microinverter: Hoymiles HMS-600-2T Microinverter ![MicroInverter](img/02MicroInverter_icon.svg)
 
1. **General Specifications**:
  - **Manufacturer**: Hoymiles Power Electronics Inc.
  - **Description**: A microinverter designed by Hoymiles Power Electronics Inc. It converts direct current (DC) into alternating current (AC) for grid supply. Supports a 2-in-1 configuration, allowing one unit to connect with two PV modules.
  - **Type**: Microinverter
  - **Model Type**: HMS-600-2T
  - **Product Name**: Hoymiles HMS-600-2T Microinverter
  - **Warranty**: 25 Years
  - **Certifications**: VDE-AR-N 4105: 2018, EN 50549-1: 2019, VFR2019, IEC/EN 62109-1/-2, IEC/EN 61000-6-1/-2/-3/-4, IEC/EN 61000-3
  - **Country of Origin**: China
2. **Mechanical Specifications**:
  - **Protection Class**: Outdoor-IP67 (NEMA 6)
  - **Cooling**: Natural convection-No fans
  - **Dimensions (mm)**: 261 × 180 × 31
  - **Weight (kg)**: 3.1
3. **Operating Parameters**:
  - **Maximum System Voltage (V)**: 60
  - **MPPT Voltage Range (V)**: 16-60
  - **Nominal Operating Cell Temperature (°C)**: -40 to +65
4. **Electrical Characteristics (AC)**:
  - **Rated Output Power (W)**: 600
  - **Nominal Output Voltage/Range (V)**: 230/ (180–275)
  - **Nominal Frequency/Range (Hz)**: 50 / (45-55)
  - **Power Factor (%)**: > 0.99 default 
    - > _Note:_ Power Factor is adjustable Range: 0.8 leading, ..., 0.8 lagging
  - **CEC Peak Efficiency (%)**: 96.7
  - **Nominal MPPT Efficiency (%)**: 99.8
  - **Communication Features**: 2.4G RF
5. **Resources**:
  - **[Link to Datasheet](https://www.hoymiles.com/wp-content/uploads/downloadupload/Datasheet_HMS-600-700-800-900-1000_EU_EN_V202201.pdf)**
  - **[Link to User Manual](https://www.hoymiles.com/wp-content/uploads/downloadupload/User%20manual_HMS-600-700-800-900-1000-2T_EU_EN_V202204.pdf)**
---
### Power Meter: myStrom WiFi Switch Socket ![PowerMeter](img/04PowerMeter_type_02_icon.svg)

1. **General Specifications**:
  - **Manufacturer**: myStrom AG
  - **Description**: Produced by myStrom AG, this socket offers power metering capabilities, turning connected devices into smart devices. It also monitors room temperature.
  - **Type**: Power Meter
  - **Interface**: Schuko Plug in
  - **Model Type**: WSE1/WSE2 (Models identical)
  - **Product Name**: myStrom WiFi Switch Socket with Power Meter
  - **Warranty**: 2-year
  - **Certifications**: CE
  - **Country of Origin**: Switzerland
2. **Mechanical Specifications**:
  - **Dimensions (mm)**: 87 × 150 × 87
  - **Weight (kg)**: 0.120
3. **Operating Parameters**:
    - **Environment Temperature Range (°C)**: 10 – 60
    - **Environment Humidity Range (%)**: 5 – 90
4. **Electrical Characteristics**:
  - **Measurement Spectrum (W)**: 2 — 3680
  - **Measurement Accuracy (%)**: +/- <1 
  - **Max Switching AC Current (A)**: 16 A 
  - **Nominal Output Voltage Range (V)**: (100 – 240)
  - **Nominal Frequency (Hz)**: 50/60 Hz
  - **Power Consumption (W)**: 1.4 (on) • 0.9 (off)
  - **WiFi**: IEEE 802.11n
  - **Communication Features**: 2.4 GHz
5. **Resources**:
  - **[Link for Product](https://mystrom.com/de/wifi-switch/)**
  - **[Link to Datasheet](https://mystrom.ch/wp-content/uploads/2017/01/myStrom_WiFi_Switch_CH_DE.pdf)**
6. **Additional Specifications - Compatibility/Requirements**:
  - **Internal-Temperature Sensor**: Available
  - **Connection**: WiFi Router
  - **Mobile App**: Available for iOS and Android (myStrom Account and App)
  - **Smart Home**: Supported