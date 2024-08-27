# Buck-Boost Converter

A Buck-Boost Converter provides an output voltage that may be either lower or higher than the input voltage, with the output voltage polarity being opposite to that of the input.

## Circuit Diagram

![Buck-Boost Converter Circuit Diagram](https://github.com/user-attachments/assets/de471d28-d0e6-4af4-a84d-4ec817d2bb6a)

## Modes of Operation

### Mode I: Switch ON, Diode OFF

When the switch is ON, it acts as a short circuit, ideally offering zero resistance. During this time, all the current flows through the switch and the inductor, returning to the DC input source. The inductor stores energy while the switch is ON.

### Mode II: Switch OFF, Diode ON

When the switch is OFF, the polarity of the inductor reverses, and the stored energy is released through the load and the diode, back to the inductor. This action maintains the current flow direction through the load and boosts the output voltage. The inductor, along with the input source, helps in stepping up the output voltage.

## Buck-Boost Converter Formula

The output voltage \( Vo \) in relation to the input voltage \( Vin \) is given by:

Vo/Vin = -D/(1-D)

where \( D \) is the duty cycle. 
- If \( D > 0.5 \), the output voltage is greater than the input voltage.
- If \( D < 0.5 \), the output voltage is less than the input voltage.
- If \( D = 0.5 \), the output voltage is equal to the input voltage.

## Results

- **Inductance (L):** 32 mH  
- **Capacitance (C):** 32 µF  
- **Resistive Load:** 100 Ω  
- **Switching Frequency:** 5 kHz  
- **Input Voltage:** 20 V DC

### Output Voltage for Different Duty Cycles

1. **Duty Cycle (D) = 20%**  
   - Output Voltage (\( Vo \)) = -4.793 V  
   ![D = 20%](https://github.com/user-attachments/assets/112d2a10-6101-4729-9c7f-5f8372b88073)

2. **Duty Cycle (D) = 50%**  
   - Output Voltage (\( Vo \)) = -19.95 V  
   ![D = 50%](https://github.com/user-attachments/assets/d1a9ea89-ef27-4e5c-ab3f-e7341d7f82b1)

3. **Duty Cycle (D) = 80%**  
   - Output Voltage (\( Vo \)) = -81.05 V  
   ![D = 80%](https://github.com/user-attachments/assets/93962263-39d4-4bb4-bf89-574c4649ffbc)
