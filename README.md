# electrical-measuring-instrument-
# Electrical Measuring Instruments Program

print("ELECTRICAL MEASURING INSTRUMENTS")
print("--------------------------------")

print("1. Ammeter - Measures Current")
print("2. Voltmeter - Measures Voltage")
print("3. Ohmmeter - Measures Resistance")
print("4. Wattmeter - Measures Power")

choice = int(input("\nEnter your choice (1-4): "))

if choice == 1:
    voltage = float(input("Enter voltage (V): "))
    resistance = float(input("Enter resistance (Ohm): "))

    current = voltage / resistance

    print("\nCurrent =", round(current, 2), "A")
    print("Measured using: Ammeter")

elif choice == 2:
    current = float(input("Enter current (A): "))
    resistance = float(input("Enter resistance (Ohm): "))

    voltage = current * resistance

    print("\nVoltage =", round(voltage, 2), "V")
    print("Measured using: Voltmeter")

elif choice == 3:
    voltage = float(input("Enter voltage (V): "))
    current = float(input("Enter current (A): "