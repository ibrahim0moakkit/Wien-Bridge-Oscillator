# Wien-Bridge-Oscillator

Wien bridge oscillator consists of amplifier circuit and feedback circuit

The amplifier circuit consists of LM741 OP-AMP, 2100ohm resistor, and 1kohm resistor.

The feedback circuit consists of parallel RC and series RC components R=1kohm and C=0.1uF.

And R2 should be slightly bigger than R1

![wein-bridge-formula](https://user-images.githubusercontent.com/108411357/198380865-4a84cdd8-2c2a-499d-b858-fedbf84cffd3.png)



plugging the values to the above equation we get around

fo=1591.5 Hz

Gain for the feedback circuit (B) circuit is always equal to B=1/3.

Gain for the inverting amplifier (A) circuit is equal to A=1+R5/R3.

Wien Bridge Oscillator circuit

![Capture](https://user-images.githubusercontent.com/108411357/198381957-079ecd65-4bc2-4231-bb3a-d0a1afe40294.PNG)


![sso](https://user-images.githubusercontent.com/108411357/198382598-5f7bdf37-ada1-4374-abd4-f655a21f7217.PNG)


# Kicad pcb design

![bn](https://user-images.githubusercontent.com/108411357/198382957-20daf183-ed38-4832-85a1-1c1dd2cb401e.PNG)

![ckt](https://user-images.githubusercontent.com/108411357/198382988-bb679a71-ae13-458f-a3d9-daa641377476.PNG)
