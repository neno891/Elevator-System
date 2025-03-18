# Elevator-System

Overview:
 This project simulates a dual-elevator system that intelligently responds to user inputs from different floors. The system decides which elevator should respond based on its current position and movement 
 direction. The logic is implemented using Logisim, incorporating both sequential and combinational circuits.
Features:
 Two Elevators: The system controls two lifts, deciding which one should respond to a call.
 Four-Floor Simulation: The system operates within a four-floor building.
 7-Segment Display: Each elevator displays its current floor and movement direction.
 Priority-Based Decision Making: A lift closest to the requested floor will move, while the other remains stationary.
 LED Indicators: LEDs indicate door status (open/closed) and movement direction (up/down).
 Combinational & Sequential Circuits: The system is built using priority encoders, multiplexers, and other logic circuits.
How It Works
 The priority encoder determines the current and requested floor.
 If a user presses a call button on a particular floor, the system selects the closest elevator.
 If both elevators are on the same floor, one is selected to move while the other remains stationary.
 The 7-segment display shows the current floor and direction of movement.
