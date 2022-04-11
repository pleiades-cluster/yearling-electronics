# yearling-electronics
PROVES-Yearling Project files for CD&amp;H and EPS boards

C&DH Board Design Requirements: 
The Command and Data Handling (C&DH) Board is the link between our satellite and the rest of the world. The C&DH board will also handle the broad level scheduling of satellite activities. 

Key Requirements: 

- Facilitate Radio Receive and Transmit 
- Collect Satellite State of Health Data 
- Process Satellite Data into Packets for Transmission 
- Schedule High Level Satellite Activities 

Would be nice: 
- Facilitate a live engineering data link with other processors onboard the satellite 
- EPS Board Design Requirements: 

Non-Optional:
- Overcharge Protection
- Overdischarge Protection
- Solar Charging Circuit 
- 3.3V Regulator
- 5V Regulator 
- Inhibit Scheme 
- Battery Monitor

Very Preferred:
- Direct RP2040 Control On-Board 
- Battery Fuel Gauge 
- Power Path Circuit
- Battery Thermal Management 

Would be Nice:
- Circuit Breaker System 
- Resettable Fuses 

The EPS board will be a hybrid of the PyCubed and OreSat architectures.
