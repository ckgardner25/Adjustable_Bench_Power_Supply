# Adjustable_Bench_Power_Supply

Currently designing and building a custom STM32-based bench power supply and electronic load with adjustable voltage and current control, thermal protection, and real-time monitoring. The project combines custom KiCad schematic and PCB design, LTspice simulation, embedded firmware development, and a USB-connected PC application written in C for control, presets, and data logging.

### Version 1.0
- Initial LM5176 power-stage design completed.
- PSpice simulation identified an error in the original buck-boost power-stage implementation, prompting a full redesign before fabrication.

### Version 1.1 (Current)
- Redesigning the LM5176 power stage using Texas Instruments reference designs and transient simulation results.
- Validating switching behavior, startup characteristics, and control-loop operation through PSpice prior to PCB fabrication.
- PCB layout and design verification currently in progress.
