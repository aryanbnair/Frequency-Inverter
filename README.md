# Single Phase Frequency Converter for 48 Volts

## Project Description

This Project focuses on the construction and improvement of a Single Phase Frequency Converter for 48 volts. The goal is to optimize the cooling of the board and to allow higher currents through the switches.

## Project Objectives

1. **Research and Modification of the Reference Board**
   - Literature research on power switches, driver stages, brake choppers, and modifying the PCB design in KiCAD.
   
2. **Construction of a Test Bench**
   - Designing a test bench as a brake chopper to test the cooling of the board.
   - Designing the driver stage and ordering mechanical parts.
   
3. **Commissioning and Measurements**
   - Conducting test measurements with a PWM signal generator.
   - Further development of the converter in KiCAD.

## Technical Details

### Power Converter
- **Model**: Infineon EVAL_TOLT_DC48V_3kW V 3.0
- **Goal**: Improve the cooling of the power switches

### Cooling Methods
1. **Cooling through the PCB**: 
   - Using VIAS (through-holes) and thick copper layers in the PCB.
   
2. **Separate Heat Sinks**:
   - Electrically isolated heat sinks.
   
3. **Water Cooling**:
   - Using a heat exchanger or CPU cooler.

### Software and Tools
- **PCB Design**: KiCAD
- **Controller**: STM Controller with associated software

## Literature and Resources

- Infineon Evaluation Board: [EVAL_TOLT_DC48V_3KW-UserManual-v03_00-EN](https://www.cfdyna.com/Home/electronicsCooling.html)
- MOSFET and IGBT Cooling: [Toshiba Article](https://toshiba.semicon-storage.com/us/semiconductor/product/mosfets/12v-300v-mosfets/articles/dsop-advance.html)
- Fundamentals of MOSFET Driver Circuits: [TI Application Report](https://www.elektormagazine.de/news/warum-brauchen-mosfets-einen-treiber-26132)
