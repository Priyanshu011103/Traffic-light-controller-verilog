# Traffic Light Controller using Verilog

A Finite State Machine (FSM) based Traffic Light Controller designed in Verilog HDL. The project simulates the operation of a four-road traffic intersection with configurable signal timings for each traffic phase.

---

## Features

- Finite State Machine (FSM) implementation
- Six traffic signal states
- Configurable timing for each traffic phase
- Asynchronous reset
- Verilog testbench for functional verification
- Waveform simulation using GTKWave/EPWave

---

## State Sequence

S1 → S2 → S3 → S4 → S5 → S6 → S1

Each state controls traffic signals for different roads while maintaining safe traffic flow.

---

## Traffic Signal Encoding

| Signal | Binary |
|---------|--------|
| Green   | 001 |
| Yellow  | 010 |
| Red     | 100 |


```

---

## Simulation

The design was verified using:

- Verilog HDL
- Icarus Verilog
- GTKWave / EPWave



## Future Improvements

- FPGA implementation
- Clock divider for real-time operation
- Pedestrian crossing support
- Emergency vehicle priority
- Seven-segment countdown timer
- Sensor-based adaptive traffic control

---

## Author

**Priyanshu Mamgain**
