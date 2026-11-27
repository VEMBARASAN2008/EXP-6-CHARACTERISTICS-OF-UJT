# EXP-6-CHARACTERISTICS-OF-UJT
1. AIM
To plot the characteristics of UJT (2N2446) and to determine the intrinsic stand-off ratio from the graph.
2. APPARATUS REQUIRED
S. No.	Components	Specification	Qty.
1	UJT	2N2446	1
2	Resistor	1 kΩ	2
3	Regulated dual power supply	Dual (0–30) V	1
4	Voltmeter	0–30 V	2
5	Ammeter	0–30 mA	1
6	Connecting wires & Bread Board	As required	As required
3. THEORY
UJT is the Uni Junction Transistor. It is a three-terminal device. The three terminals are emitter, base 1 and base 2. The equivalent circuit consists of two resistors, one variable resistor and one fixed resistor. The ratio of internal resistance is referred to as intrinsic stand-off ratio (η). It is defined as the ratio of the variable resistance to the total resistance.
Due to the existing PN junction, there will be a voltage drop. If voltage is applied to the emitter, the device will not turn on until the input voltage is less than the drop across the diode plus the drop at the variable resistance R1.
When the device is turned on, holes move from emitter to base resulting in a current flow. Due to the sudden increase in charge concentration in the base region, conductivity increases. This causes a drop at base 1. If we further increase the emitter voltage, the device undergoes saturation. Hence UJT has three operating regions: (i) cut-off region, (ii) negative resistance region and (iii) saturation region.
4. CIRCUIT DIAGRAM
 <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/34b084a3-9d4f-4f2b-9408-49c97447f2cd" />

Reference circuit diagram reproduced from the supplied record.
5. UJT EQUIVALENT CIRCUIT
The UJT equivalent circuit consists of the inter-base resistance RBB divided into two portions, RB1 and RB2, with the emitter PN junction represented by a diode.
6. UJT CHARACTERISTIC CURVE
The emitter characteristic is plotted between emitter voltage VE and emitter current IE. The curve contains the cut-off region, peak point, negative resistance region, valley point and saturation region.
 <img width="1600" height="900" alt="WhatsApp Image 2026-11-27 at 9 17 29 AM" src="https://github.com/user-attachments/assets/191bfd87-dc52-4f47-aa76-b2caa47e3175" />
<img width="1600" height="900" alt="WhatsApp Image 2026-11-27 at 9 17 21 AM" src="https://github.com/user-attachments/assets/c436eba5-dac1-4da3-850c-cd0f7c67eff9" />


Reference model graph from the supplied record.
7. PROCEDURE
from the graph and calculate η. Similarly, determine the intrinsic stand-off ratio for all values of VBB.
9. OBSERVATION
1.Download two files and save in same folder 2.Open LT Spice 3.Go to file--->open UJT_oscillator.cir file 4.Run it 5.Output window will open.In output window go to plot settings---->Add trace--->choose v(e) ,click ok.This is input wave form  6.Now close output window,again run the file,in output window go to plot settings--->Add trace--->choose v(b1) ,this is output waveform.Take snap of both input and output wave form
Simulation Results:




For VBB = 5 V and VBB = 8 V
VBB = 5 V		VBB = 8 V	
VE (V)	IE (mA)	VE (V)	IE (mA)
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
10. CALCULATION



For VBB = 5 V:
Peak voltage, VP = 3.3 V
Diode voltage, VD = 3.3 − 2.8 = 0.5 V
η = (VP − VD) / VBB
η = (3.3 − 0.5) / 5 = 2.8 / 5 = 0.56
Therefore, η = 0.56
11. RESULT
The characteristics of UJT were plotted and the intrinsic stand-off ratio was found.
Intrinsic stand-off ratio, η = 0.56
Peak voltage, VP = 3.3 V
