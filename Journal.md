#Optimus 

I'm building Optimus (Touch pad blinky PCB) because of the fact that a lot of TTL circuits are VERY similar so I decided to change it up and make it more fun and original.

## Date - March, 21st 2026

Today I worked on the Falstad Simulation and did a LOT of research. I was very stuck on what to do and I tried to make a ring oscillator: 

I didnt like it at all, it didnt seem original and I saw insane amounts of the same circuit online so I wanted something different. I decided to use the human finger
as a sort of resistor to provide current from a 9v pad to another pad connected to the base of the transistor. I also added 2 LED's and a 100nf capacitor to create a dimming effect. Also I was worried the current would be to small for the transistor base to detect it so I researched transistor gain and then found out that a single NPN transistor wont have enough sensitivity for high resistance skin(10MOhms) so I landed on the darlington pair as the best way to solve this problem: This took a lot of reconfigurations but finally landed on this!

![image](https://cdn.hackclub.com/019d12bc-8b63-74f6-b691-f9575e519884/circuit-20260321-2248.png)

I ran into this issue that the current would be to low to trigger the base for the transistor, so I researched it and found that the darlington pair would be the best method to tackle this challenge.

### Time Spent: 5 Hours

