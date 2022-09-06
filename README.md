# CEITEC-MOTES-VLTP
This is repository for a Very Low Temperature Probe made by CEITEC MOTES group.


## Description
The probe was designed to be compatible with a Cryogen free magnet (CFM) system, located in laboratory of Electron paramagnetic resonance (EPR) at CEITEC VUT. The magnet contains a variable temperature insertion (VTI) system, which is adjustable cryostat that allows to control temperature in rage from 2 K to 325 K.
 
The probe is assembled of an aluminium probe head on top, body made of three hollow stainless-steel tubes, copper radiation shields placed along the body, an outer tube and a bronze bayonet socket attached to a coupler made of PEEK. Probe head has four ports on sides, and one port at the top. Two ports on sides are occupied by a 11 and 16-pin hermetically sealed connectors. Other ports are sealed by a blank-off covers. Body is made of three hollow stainless-steel tubes which has a low thermal conductivity. One side is attached to probe head and at the other side is attached a radiation shield with a PEEK coupler that reduce a heat transfer. In the middle of the body are radiation shields that reflects IR radiation and keeps the tubes set up in a triangle. This causes that average thermal gradient about 3 K/cm along the body is achievable. The outer tube coders the body when probe is loaded via airlock into the cryostat and provide a hermetical sealing up to a bottom of the probe head. A PEEK coupler is equipped by three 8-pin connectors, and a bayonet socket that is compatible with a sample holders used for EPR measurements. Two connectors are connected via phosphor-bronze wires to the hermetic 16-pin connector dedicated for electronic measurements, and the last one is connected to the 11-pin connector usually used for a temperature sensor, field sensor and a heater. Therefore, already made Chip Sample Holder (CHSH) with 16 contacts can be simply used for electronic measurements that require cryogenic temperatures and/or a high magnetic field.

The probe was already tested by measuring of calibration curves of uncalibrated temperature sensors. For this purpose, a special holder with a high thermal conductivity was made. It can hold up to six temperature sensors, however only three were placed at once so far, because in the EPR laboratory are only three suitable instruments. One of the sensors is used as a calibrated standard, and others are uncalibrated. To monitor temperature of a calibrated standard, a temperature controller model 350 from Lake Shore Cryotronics was used. Resistance of other two sensors was measured by a four-wire method source at two source meter units Keithley 2450 from Tektronix. Total uncertainty of measurement at 4.2 K was calculated as 13.2 mK, and at 77 K it was 194.5 mK. In addition, a single purpose software that controls all three instruments and collects a calibration data was made in LabVIEW and is uploaded to a public repository (CEITEC-MOTES-VLTP) on GitHub. Expenses on the probe were already covered by creating of six calibration curves for uncalibrated sensors, because difference in cost of a single calibrated and uncalibrated sensor is about 550 USD.

## Technical aspects

Total length:	106 cm
Active length:	94 cm
Probe head flange:	7.5 cm / 5 cm (outer / inner diameter)
Used ports:	2 (11-pin DBEE-104A056 + 16-pin SFE-104A086)
Blank ports:	2 on sides of probe head + 1 on top of probe head
Maximum temperature:	325 K (approx. 52 °C)
Achieved temperature:	< 2 K (sample holder)

## Economical aspects
Total cost construction material: 31 000 CZK
Total cost of workload: 18 500 CZK
Difference of a single calibrated and uncalibarated sensor: 13 500 CZK