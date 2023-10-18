# Real Time Clock

### Introduction
This is a real time clock, an integrated circuit, provides time to the microcontroller.It consists of oscillatory circuit, counter, register. Oscillatory circuit made of quartz crystal generates clock signal with high level of stability. Prescaler also called as frequency divider scales the clock producing a clock of frequency 1Hz. Counter using generated 1Hz clock signal counts the seconds and apparently minutes, hours. The time values are stored in a register. Real-time circuit is interfaced with microcontroller by Advanced Peripheral Bus following Advanced Microcontroller Bus Architecture (AMBA) bus protocol there by communicating time with microcontroller.  Real-time clock provides accurate time track to the device so all the events take place at the right time. This system functions reliably with optimum CPU and memory space usage.

### Block diagram

![rtcbd](https://user-images.githubusercontent.com/62790565/184196172-5bb0eee9-9785-4821-b242-71568a29f803.PNG)

#### Simulation Waveforms

### Synthesis
Synthesis transforms the simple RTL design into a gate-level netlist with all the constraints as specified by the designer. In simple language, Synthesis is a process that converts the abstract form of design to a properly implemented chip in terms of logic gates. Yosys is a framework for Verilog RTL synthesis.

### Gate Level Simulation
GLS is generating the simulation output by running test bench with netlist file generated from synthesis as design under test. Netlist is logically same as RTL code, therefore, same test bench can be used for it.

#### Simulation Waveforms
Pre - synthesis simulation waveform:
![1](https://github.com/ramdev604/pes_rtc/assets/43489027/c648c358-1e77-4ee0-b30c-bf1a97550f2f)



Post - synthesis simulation waveform:

![2](https://github.com/ramdev604/pes_rtc/assets/43489027/f4bcfe9c-1dc6-4d23-b676-35a1c9e849a9)

