# Optimus 

I'm building Optimus (Touch pad blinky PCB) because of the fact that a lot of TTL circuits are VERY similar so I decided to change it up and make it more fun and original.

## Date - March, 21st 2026

Today I worked on the Falstad Simulation and did a LOT of research. I was very stuck on what to do and I tried to make a ring oscillator: 

I didnt like it at all, it didnt seem original and I saw insane amounts of the same circuit online so I wanted something different. 

I decided to use the human finger
as a sort of resistor to provide current from a 9v pad to another pad connected to the base of the transistor. 

I also added 2 LED's and a 100nf capacitor to create a dimming effect. 

Also I was worried the current would be to small for the transistor base to detect it so I researched transistor gain and then found out that a single NPN transistor wont have enough sensitivity for high resistance skin(10MOhms) so I landed on the darlington pair as the best way to solve this problem: This took a lot of reconfigurations but finally landed on this!

Here are a few resources I read while researching:

  [Darlington Pair Overview](https://www.electronics-notes.com/articles/analogue_circuits/transistor/darlington-pair.php)
  
  [Darlington Transistor (Wikipedia)](https://en.wikipedia.org/wiki/Darlington_transistor)
  
  [Using Your Finger as a Switch](https://www.instructables.com/Using-Your-Finger-As-an-Electrical-Switch/)
  
  [Capacitive Touch Discussion (r/KiCad)](https://www.reddit.com/r/KiCad/comments/utwhah/capacitive_touch_circuit/)
  
  [Sziklai Pair (Complementary Darlington)](https://en.wikipedia.org/wiki/Sziklai_pair)
  
  [Cascode Circuits](https://en.wikipedia.org/wiki/Cascode)

These are just a few resources I read and researched there are many other resources I simply cant list because it would be to long, I also had many different prototypes and failures!

I learned a lot about:

Signal Amplifiers

The cascode configuration

Darlington Pair and Sziklai Pair 

Standard Cascaded stages

![image](https://cdn.hackclub.com/019d12bc-8b63-74f6-b691-f9575e519884/circuit-20260321-2248.png)

I ran into the issue that the current would be to low to trigger the base for the transistor, so I researched it and found that the darlington pair would be the best method to tackle this challenge.
[Click here to open the circuit simulation](https://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEBmAHAJmgdgGzoRmACzICcpkORICkNNdCApgLRhgBQALiKqTiCJFUIUuhFCRdCCxgIikYWATJ5kVERXIo0HAlKoEYHMtJEsySCvBwQAEyYAzAIYBXADZduILAnQo-Hw0A-2kQNmgwVBNDLHQsIjBSLGTkViloNSU-VSI9fggwWwcXDy8AYxAcOJCqmpJ-ajBYeFa2uDBWLF5ocj7yVFQwNGJtGA6oDgBzOsbkf2rGqihJgHcfQNUFmq212dqcdVrIDgAnKqPdvxFdunHOdevwQ9FxZ7uOACVXkWM6MV+YFCKwUohWd0yHHWWGCyGQAhh1HQoJO0OCyP+bwxewB7x+IGxqPx2NxDT2iJQOBEFMk5OCtL4AlpRNJyyKoLy1BO51Z1Fx+mBRTgZxsHLZikYYhWQpOxn8-KluL0An8JTcnhY7iYdnA4J0kE4ctFkv87LoyoJ9ic6q4mu1uru+s4MyVCAEuKwinB02NVTdvs9XL2Tyubz+kwA9uARMs6ApyPRxpR8CtTTcOEA)
Here's the link!
### Time Spent: 5 Hours

## Date - 24/3/26

Today I made the schematic and the pcb and exported the gerber files. I also decided on mr. egg he's the pcb. I dont really know where i got a egg character from but I have it now I guess.Also I tried adding copper pads and got fedup with it so I just used pin header's: 

Basically you just keep your finger ontop of the pin headers and they make a resistor which triggers the transistors and lights up the led's.

Also I did some of this in @shadow huddle which was fun!

![image](https://cdn.hackclub.com/019d22a0-ea06-735d-b5ec-4b44b277795f/20260325_01h25m02s_grim.png)

![image](https://cdn.hackclub.com/019d2141-e9e1-7147-9fdd-6008dcf0c876/20260324_18h54m05s_grim.png)

### Time Spent: 2 Hours

