# Series Linear Voltage Regulator
Designing a Robust Series Linear Voltage Regulator with Discrete Components.

The starting schematic is shown in Figure 1.

![ Figure 1 ](/Pictures/Figure1.png)

The design parameters are:
- Output voltage
- Maximum output current
- Short circuit current

The electronic components in the diagram have the following role:
- Transistor Q1 is the main element of the regulator and its role is to regulate the output voltage. It behaves in the circuit as a variable resistor,
- Zener diode DZ is the voltage regulator for the regulator and determines the output voltage,
- Resistor R1 provides the bias current for Zener diode DZ and the base current for transistor Q1,
- Capacitor C1 filters the input voltage of low-frequency parasitic signal,
- Capacitor C2 filters the input voltage of high-frequency parasitic signal,
- Resistor R2 has the role of current sensor for the short-circuit protection circuit,
- Transistor Q2 has the role of short-circuit protection and is active only if the output current exceeds the maximum value,
- Capacitor C3 filters the output voltage of low-frequency parasitic signal,
- Capacitor C4 filters the output voltage of high-frequency parasitic signal,
- Resistor RL simulates the consumer connected to the output of the regulator.

