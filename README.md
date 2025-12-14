AIM:

To implement SR flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY


SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.
<img width="641" height="413" alt="image" src="https://github.com/user-attachments/assets/c5058d7d-fdad-44c4-b469-b85d90ea51dd" />


image
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.
<img width="613" height="321" alt="image" src="https://github.com/user-attachments/assets/a5c402c4-d320-4a61-8f84-363021662e9b" />


image

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State
<img width="521" height="442" alt="image" src="https://github.com/user-attachments/assets/05cfd4dc-16ec-4f2e-95db-00545c7e8d46" />


image

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
<img width="600" height="212" alt="image" src="https://github.com/user-attachments/assets/4af996b8-528f-4453-8dfa-fb669fcd0dd4" />


image

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. 
Developed by:R.AISHWARYA
RegisterNumber: 25017062

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS
