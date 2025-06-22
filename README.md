# AC-to-DC-solar-power-generation-for-home-appliances

#  Solar Power Generation System for Home Appliances using MATLAB/Simulink

This project models a **solar power generation system** in **MATLAB/Simulink** that simulates the conversion of solar energy (DC) to usable AC power for home appliances. It demonstrates how renewable energy systems can be designed, tested, and optimized using simulation tools before physical implementation.

##  Features

- Simulates photovoltaic (PV) panel behavior using MATLAB's Renewable Energy toolbox
- Models MPPT control and DC-DC converter
- Simulates battery charging, storage, and discharging
- Inverter circuit converts DC to AC for residential use
- Load flow and energy analysis under varying sunlight conditions

##  Software Requirements

- MATLAB R2021b or later (preferred)
- Simulink
- Simscape Electrical (formerly SimPowerSystems)
- Simscape
- Optional: Simulink Dashboard (for live control)

## Simulation Parameters

- Irradiance: Variable (200–1000 W/m²)
- Temperature: 25–45°C
- Battery: 12V, 100Ah
- Inverter output: 230V AC, 50Hz
- Load: Constant resistive (or time-varying)

## Working Principle

PV panels convert sunlight into DC electricity.
MPPT ensures the system operates at maximum efficiency.
A boost converter adjusts voltage for charging the battery.
Stored energy powers DC and AC loads through the inverter.

## Applications

 - Design of home solar power systems
 - Performance analysis under different sun conditions
 - Integration into smart grid simulation
 - Educational use for renewable energy system modeling
 - Battery optimization and inverter testing

##  How to Run the Simulation

- Open solar_pv_model.slx in MATLAB.
- Run pv_parameters.m to load system parameters.
- Start the simulation (Run button in Simulink).
- Observe real-time scope results and data logging.
