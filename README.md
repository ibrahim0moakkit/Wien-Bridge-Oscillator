# Wien-Bridge-Oscillator

Wien bridge oscillator consists of amplifier circuit and feedback circuit

The amplifier circuit consists of LM741 OP-AMP, 2100ohm resistor, and 1kohm resistor.

The feedback circuit consists of parallel RC and series RC components R=1kohm and C=0.1uF.

And R5 slightly larger than 2xR3

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

# Building the circuit 

![Capturew](https://user-images.githubusercontent.com/108411357/198387280-a48b5caa-6962-485c-b440-b46db3c372e2.PNG)

![Capeture](https://user-images.githubusercontent.com/108411357/198387409-c9b7a275-ef77-4216-aa36-d94e00c4cd81.PNG)


![f5775737-ea28-4542-8a59-435e46757899](https://user-images.githubusercontent.com/108411357/198386607-0053d917-74bd-47bc-a4b5-1e6f34e4ff5d.jpg)

![8030ebe3-4216-4692-8cb6-30966b90f6e2](https://user-images.githubusercontent.com/108411357/198386626-81e8e917-6085-46df-a5d6-29c4bcdf8dae.jpg)


