**Traffic_Light_Controller_Verilog**

This project is a Verilog-based traffic light controller simulation. It controls traffic lights for multiple roads based on a predefined sequence and timing.

**Features**

1. Implements a finite state machine (FSM) for traffic light control.
2. Controls four sets of traffic lights: light_M1, light_M2, light_MT, and light_S.
3. Uses state transitions to switch lights based on predefined time durations.
4. Reset functionality to initialize the system.
5. Clock-based timing mechanism for state transitions.

**How to Run the Simulation Using Icarus Verilog (iverilog)**

1. Compile the Verilog files: iverilog -o trafficlight_tb.vvp trafficlight.v trafficlight_tb.v
2. Run the simulation: vvp trafficlight_tb.vvp
3. View the waveform (optional) using GTKWave: gtkwave

**Project Workflow**

1. Reset is activated to initialize the system.
2. Clock cycles drive the FSM, changing the traffic light states based on timers.
3. Traffic lights transition through predefined states: Green, Yellow, and Red.
4. Simulation verifies the correct behavior of the state transitions.
