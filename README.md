# PESMO: Poor Engineering Student's Modular Oscilloscope  
  
This is a homemade modular oscilloscope made using a single Arduino UNO development board and LM358, along with a few passive components (like resistors and capacitors). The signal to be analyzed passes through the analog circuit which shifts it above 0.7V (limit of ATmega328P ADC), and is read by the ADC of ATmega328P. The output is read via a simple serial plotter program written in Python and uses NumPy and Matplotlib libraries. The project was an exercise in Data Acquisition serially using Python and AVR microcontrollers. This project can be updated in the future by interested people.  
Updates in the future will include:  
&nbsp;1. ability to read both positive and negative volatges   
&nbsp;2. ability to read voltages upto at least 20 V  
&nbsp;3. better algos. to read ADC and transmit data serially  
&nbsp;4. Oscilloscope trigger facility  
&nbsp;5. A better plotter  
