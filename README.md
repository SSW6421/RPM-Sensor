# RPM Induction Sensor

An electromagnetic induction–based RPM sensor designed to measure rotating machinery speed using 8 stationary coils and 16 rotating neodymium magnets. Built as part of the EE251 Mini Project, this system measures rotational speed from 10–3500 RPM with a linear output and ±5.19 RPM accuracy.

## Key Specifications
- **Range:** 10–3500 RPM  
- **Accuracy:** ±5.195 RPM  
- **Dimensions:** 160 × 65 × 60 mm  
- **Weight:** 130 g  
- **Coils:** 8 coils, 20 turns each (30 SWG)  
- **Magnets:** 16 neodymium magnets  
- **Operating Temp:** 0–80°C  

## Working Principle
The sensor operates using **Faraday’s Law of Electromagnetic Induction**. Magnets attached to two rotating disks pass over stationary coils, inducing a voltage proportional to RPM. All coils are connected in series to maximize voltage output.

## Calibration Summary
Calibration was performed using a lathe machine across 20 measurement points. A linear model was selected due to its low RMSE (4.441) and minimal non-linearity.  

**Transfer Function:**  
y = 0.068x – 0.7976

## Project Structure
- `hardware/` → coil arrangement, magnet layout, casing  
- `calibration/` → calibration table, plots, transfer function  
- `docs/` → report, diagrams, notes  
- `images/` → photos, CAD renders  

## Future Improvements
- Add amplifier circuit for higher sensitivity  
- Increase coil count  
- Improve signal processing  
- Add wireless transmission  
- More calibration data  

## Contributors
- **E/21/016 — Adams S.L.**  
- **E/21/182 — Hettiarachchi H.A.O.I.A.**  
- **E/21/420 — Vitharana S.S.**

