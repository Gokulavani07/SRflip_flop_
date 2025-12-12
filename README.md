AIM:

To implement SR flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.


<img width="748" height="445" alt="Screenshot 2025-12-11 190414" src="https://github.com/user-attachments/assets/d748f5ae-9562-4bc2-9c86-d925aa2bb0dc" />


This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

<img width="810" height="427" alt="Screenshot 2025-12-11 190436" src="https://github.com/user-attachments/assets/516ff1c1-5081-4d09-8a84-7fb4229f5071" />


Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

<img width="683" height="565" alt="Screenshot 2025-12-11 190454" src="https://github.com/user-attachments/assets/ac3d279b-8d16-4ee6-a59a-3dd319379f10" />


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.


<img width="413" height="274" alt="Screenshot 2025-12-11 190509" src="https://github.com/user-attachments/assets/9834ec9d-9edf-4f53-8ed0-aa4d37ab43d7" />

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

Procedure
1. Select Two Logic Gates

2. Cross-Couple the Gates

3. Assign Set and Reset Inputs

4. Understand Output Behavior

5. Power and Test the Circuit


PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:GOKULAVANI.R

RegisterNumber:25017080 */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS
