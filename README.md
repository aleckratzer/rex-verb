# rex-verb
Characterization and oscilloscope analysis of a Belton Brick reverb pedal

# Belton Brick Reverb Pedal Analysis

## 🎯 Objective
To analyze and characterize an analog/digital Belton reverb circuit using oscilloscope measurements and LTspice simulation.

## ⚙️ Tools & Methods
- Rigol DS1054Z oscilloscope
- Signal generator (1 kHz sine)
- LTspice for simulation
- 9 V Class II isolated power supply
- Belton BTDR-2 reverb module circuit

## 🧩 Procedure
1. Measured input and output waveforms at multiple Depth and Level settings.
2. Observed biasing and clipping behavior at 9 V single supply.
3. Compared measured gain and waveform shape with LTspice simulation.
4. Analyzed pot functions: Level (attenuator), Depth (gain), Shade (tone filter).

## 📈 Results
| Control | Behavior | Observation |
|----------|-----------|--------------|
| Depth | Controls preamp gain | Clipping at high settings |
| Level | Passive attenuator | Decreases output amplitude |
| Shade | RC tone filter | Alters high-frequency response |

![Scope Screenshot](Measurements/reverb_waveform.png)

## 💡 Insights
- Verified op-amp clipping limits under single-supply operation.
- Confirmed reverb interference patterns and reflections.
- Demonstrated how analog and digital domains interact in a hybrid circuit.

## 🔗 Files
- `/LTspice/` – simulation schematics  
- `/Measurements/` – scope captures  
- `/Schematics/` – circuit diagram  
- `/Report/` – PDF write-up
