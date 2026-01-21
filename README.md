# Streamlined Flow
For this project I worked with A planar complex potential, transforming it into flow around a cylinder using the Milne-Thompson circle theorem. I added optional circulation to simulate lift on the body of the cylinder/ airfoil. Circulation can be turned off by setting "Gamma = 0" and the kutta condition satisfied by "Gamma = Kutta". Gamma is the circulation (how much the fluid wants to circle the body of the object) and the kutta condition forces the flow to leave the body at the trailing edge.

## Cylindrical Flow
<img width="730" height="598" alt="Cyliner_Flow" src="https://github.com/user-attachments/assets/f3dc5797-1c02-46c2-a661-fdfe99fe6eb4" />  

This is the standard Milne-Thompson flow with circulation at the kutta condition.  

## Airfoil Flow
<img width="730" height="598" alt="Airfoil_Flow" src="https://github.com/user-attachments/assets/ff548d79-d57a-49ad-917c-b3caa3ea27d4" />  

By appling The Joukowski transformation around x = 1 this aorfoil is produced, notice how the jutta condition forces the flow to leave the body from the trailing edge

## Cambered Airfoil Flow

<img width="730" height="598" alt="CamberedAirfoil_Flow" src="https://github.com/user-attachments/assets/5db0c396-32f0-4321-af21-6ef732f40829" />

Reapplying the Joukowski transformation, but this time at (1,1) or (1 + i) in imaginary unints, produces this cambered airfoil.

