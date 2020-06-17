# The Reset Circuit
The Reset Circuit resets the system after a certain time after the button is pressed. When the signal applied to the reset pin of a microcontroller is ‘0’, the execution of the program returns to the start address. The program runs again when the signal is ‘1’. The simple calculator that made by Adafruit [1], tell how many milliseconds are required to reach the specific output voltage, based on the supply voltage, the resistor value and the capacitor value. The formula used to calculate the delay is given in Equation 1.

t = -log[(V-Vout)/V]R*C  (Equation 1)

According to Equation 1, the reset time not change if the value of the capacitor decreases by a rate of 'x' while the value of resistor increases by the rate of 'x' and output voltage changes by the same rate of 'x'. For this situation, an example given in below.


The input voltage (V): 10 V

The output voltage (Vout): 8 V

The value of resistor: 100 KOhm

The value of Capacitor: 10 uF


Calculated Delay: 1609.4379 ms

————————————

The input voltage (V): 5 V

The output voltage (Vout): 4 V

The value of resistor: 100 KOhm

The value of Capacitor: 10 uF


Calculated Delay: 1609.4379 ms


The reset time is equal for both example.



Result of Application:


The input voltage (V): 1.8 V

The output voltage (Vout): 1.52 V

The value of resistor: 10 KOhm

The value of Capacitor: 10 uF

Calculated Delay: 1.8 s
Measured Delay: 1.97 s

——————————————————

The input voltage (V): 3.3 V

The output voltage (Vout): 2.4 V

The value of resistor: 10 KOhm

The value of Capacitor: 100 uF

Calculated Delay: 2.01 s
Measured Delay: 2.1 s

——————————————————

The input voltage (V): 5 V

The output voltage (Vout): 4.4 V

The value of resistor: 10 KOhm

The value of Capacitor: 100 uF

Calculated Delay: 2.12 s
Measured Delay: 1.9 s


