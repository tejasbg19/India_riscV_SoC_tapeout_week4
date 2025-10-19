# RISC-V Reference SoC Tapeout Program – Week 4

This repository contains the CMOS circuit design and SPICE simulation activities for Week 4 of the RISC-V Reference SoC Tapeout Program. The tasks focus on understanding transistor-level circuit properties and their impact on timing behavior analyzed in STA.

## Table of Contents

| SI No. | Tasks | Description |
|--------|-------|-------------|
| **[Task-1:](Task-1/Task-1.md)** | MOSFET Behavior & I<sub>d</sub> vs. V<sub>ds</sub> | Simulate NMOS, sweep V<sub>ds</sub> for different V<sub>gs</sub>, plot I<sub>d</sub> vs. V<sub>ds</sub> curves, and observe regions. |
| **[Task-2:](Task-2/Task-2.md)** | Threshold Voltage & Velocity Saturation | Sweep V<sub>gs</sub> vs. I<sub>d</sub>, extract V<sub>t</sub>, and analyze velocity saturation effects. |
| **[Task-3:](Task-3/Task-3.md)** | CMOS Inverter VTC | Build inverter, sweep input, plot V<sub>out</sub> vs. V<sub>in</sub>, and identify switching threshold (V<sub>m</sub>). |
| **[Task-4:](Task-4/Task-4.md)** | Transient Behavior & Delays | Apply pulse input, extract rise/fall delays from waveforms. |
| **[Task-5:](Task-5/Task-5.md)** | Noise Margin Analysis | From VTC, determine V<sub>IL</sub>/V<sub>IH</sub>/V<sub>OL</sub>/V<sub>OH</sub>, compute NM<sub>L</sub>/NM<sub>H</sub>. |
| **[Task-6:](Task-6/Task-6.md)** | Variation Studies | Vary V<sub>dd</sub> and transistor sizing, re-plot VTCs/delays, observe shifts in thresholds, margins, and delays. |


