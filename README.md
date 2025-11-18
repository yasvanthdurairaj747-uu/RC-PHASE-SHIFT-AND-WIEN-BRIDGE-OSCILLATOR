# RC-PHASE-SHIFT-AND-WIEN-BRIDGE-OSCILLATOR

## AIM:
	To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-amp.

## APPARATUS REQUIRED:
<img width="666" height="194" alt="image" src="https://github.com/user-attachments/assets/b2082e32-68fa-42ae-9d19-a8763286d047" />

## THEORY:
## RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo   = 1  /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .

## WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo   = 1/2πRC

## CIRCUIT DIAGRAM:
## RC PHASE SHIFT OSCILLATOR
<img width="931" height="467" alt="image" src="https://github.com/user-attachments/assets/4ed531d6-d70c-49dc-8763-be078466bd8f" />

## MODEL GRAPH:
<img width="417" height="324" alt="image" src="https://github.com/user-attachments/assets/53ef7b91-7bd4-4e06-b98c-d80970261018" />

## TABULATION:
![WhatsApp Image 2025-11-18 at 18 35 01_fdfa4131](https://github.com/user-attachments/assets/84449c27-5e58-4934-89a6-8dd59ba994f7)

## GRAPH:
![WhatsApp Image 2025-11-18 at 18 34 59_306220bb](https://github.com/user-attachments/assets/2aa0728c-f6a2-4eb1-98f5-3096e94ed630)

## CIRCUIT DIAGRAM:
## WIEN BRIDGE OSCILLATOR
<img width="570" height="480" alt="image" src="https://github.com/user-attachments/assets/6e20065c-00b5-48e1-88a2-35ae390025bd" />

## MODEL GRAPH:
<img width="417" height="324" alt="image" src="https://github.com/user-attachments/assets/95210d90-f00a-426b-bd1a-54a3a536b2c3" />

## TABULATION:
![WhatsApp Image 2025-11-18 at 18 35 01_a39411c6](https://github.com/user-attachments/assets/20b57711-5862-4f47-bdee-046084c0c4fb)

## DESIGN:
## RC PHASE SHIFT OSCILLATOR
    		fo   = 1  /  6 (2RC)
Rf   29 R1
 		C = 0.01F, fo = 200 Hz.
		R   = 1  /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
		R1     10 R
		R1 =10 R = 33 k.
		Rf  = 29R1=1MΩ

## WIEN BRIDGE OSCILLATOR
        Select frequency f0 = 1KHz
	                                     fo   = 1/2πRC
                                                A = 1+(Rf / R1) = 3.
                                                   To find R & Rf.
                     Therefore Rf = 2R1 & assume C = 0.1μf & find R from
                                                   R=1/2πfC
     =1/2*3.14*1*103*0.1*10-6   
     = 1.59KΩ.
                    Assume R1 = 10R & find Rf from Rf = 2R1
                    Therefore R1 = 1.5K *10=15KΩ
                                     Rf = 15K *2=30KΩ

## PROCEDURE:	
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.

## RESULT:
![WhatsApp Image 2025-11-18 at 18 35 00_36446c68](https://github.com/user-attachments/assets/49cfcc34-262e-4d25-b1cc-be65370257ce)


