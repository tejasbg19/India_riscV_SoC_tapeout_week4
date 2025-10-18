# RISC-V Reference SoC Tapeout Program – Week 4

## CMOS Circuit Design (sky130-style)

This repository contains the CMOS circuit design and SPICE simulation activities for Week 4 of the RISC-V Reference SoC Tapeout Program. The tasks focus on understanding transistor-level circuit properties and their impact on timing behavior analyzed in STA.

## Table of Contents

| Task | Description | Link |
|------|-------------|------|
| **[Task-1: MOSFET Behavior & Id vs. Vds](Task-1/Task-1.md)** | Simulate NMOS, sweep Vds for different Vgs, plot Id vs. Vds curves, and observe regions. Includes SPICE netlist, plots, and observations. | [View Task-1](Task-1/Task-1.md) |
| **[Task-2: Threshold Voltage & Velocity Saturation](Task-2/Task-2.md)** | Sweep Vgs vs. Id, extract Vt, and analyze velocity saturation effects. Includes netlists, plots, and tabulated results. | [View Task-2](Task-2/Task-2.md) |
| **[Task-3: CMOS Inverter VTC](Task-3/Task-3.md)** | Build inverter, sweep input, plot Vout vs. Vin, and identify switching threshold (Vm). Includes netlist, annotated plots, and analysis. | [View Task-3](Task-3/Task-3.md) |
| **[Task-4: Transient Behavior & Delays](Task-4/Task-4.md)** | Apply pulse input, extract rise/fall delays from waveforms. Includes transient simulation netlist, plots, and tabulated delays. | [View Task-4](Task-4/Task-4.md) |
| **[Task-5: Noise Margin Analysis](Task-5/Task-5.md)** | From VTC, determine VIL/VIH/VOL/VOH, compute NML/NMH. Includes calculations, tables, and discussion on robustness. | [View Task-5](Task-5/Task-5.md) |
| **[Task-6: Variation Studies](Task-6/Task-6.md)** | Vary Vdd and transistor sizing, re-plot VTCs/delays, observe shifts in thresholds, margins, and delays. Includes netlists, comparative plots, and STA ties. | [View Task-6](Task-6/Task-6.md) |

## Setup & Prerequisites

- **Tools**: Ngspice (for SPICE simulations), Magic VLSI (optional for layout views), and a text editor for netlists.
- **Collaterals**: Download the Sky130 workshop files from [kunalg123/sky130CircuitDesignWorkshop](https://github.com/kunalg123/sky130CircuitDesignWorkshop/).
- **Workshop Access**: Enabled on the VSDIAT platform—follow the repo's instructions for setup.
- **Prerequisites**: Knowledge from previous weeks (Verilog basics from Week 1-2, STA from Week 3) is assumed. Refer to [Week 3 repo](https://github.com/tejasbg19/India_riscV_SoC_tapeout_week3) for continuity.
