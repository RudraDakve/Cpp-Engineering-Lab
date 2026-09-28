# Resistance Measurement Simulator

A C++ program that calculates a resistor's value from a voltage and current measurement using Ohm's Law (R = V / I).

## How it works
1. Enter the voltage across the resistor (volts) and the current through it (amperes).
2. The program computes R = V / I.
3. The result is printed in ohms, kilo-ohms or mega-ohms, whichever is most readable.

## Edge cases handled
- **I = 0**: rejected, because it would mean infinite resistance.
- **V = 0**: reported as a short circuit (0 ohms).
- **Negative result**: the magnitude is shown, with a warning to check the polarity of V and I.

## Sample run
    Enter the voltage applied across the resistor (in volts): 12
    Enter the current flowing through the resistor (in amperes): 0.004
    The resistance of the resistor is: 3 kilo-ohms

## Run
    g++ ResistanceMeasurement.cpp -o measure && ./measure