---
layout: post
title:  "9. B-H curve, Hysteresis loss, B-H curve, eddy-current loss, and K-factor transformers"
categories: Electrical_engineering
tags: Electromagnetism
comments: true
---

- Contents
  - [Can magnetic field exist without current or vice-versa?](#relationship-between-electricity-and-magnetism)
  - [Magnetic domain](#magnetic-domain)
  - [B-H curve](#b-h-curve)
  - [Iron loss in a transformer](#iron-loss-in-a-transformer)
  - [K-factor transformers](#k-factor-transformers)

<br/>

## <span style="color:red">Can magnetic field exist without current or vice-versa?</span>		
---
No. The spin motion of electrons can be considered as current. Current and magnetic field exists together.
![9-1](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-1.jpg)
<br/>
<br/>
<br/>

## <span style="color:red">Magnetic domain</span>		
---
A magnetic domain is a magnetized area within a magnetic material, which has a uniform direction. <br/>
Think about the magnetic domain when there is no external magnetic field, and when there is an external magnetic field. <br/>
Even if external magnetic field gets stronger, internal magnetic flux intensity does not change after it reaches to the max value. -> B-H curve
![9-2](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-2.jpg)
<br/>
<br/>
<br/>

## <span style="color:red">B-H curve</span>		
---
The B-H curve shows how the material responds to an external magnetic field. <br/>
Saturation shows the limit of the material to have a maximum magnetic field inside of it. As the magnetic cores get larger, they can have larger amounts of magnetic flux, which will help to produce higher power.     
Things to consider: Residual magnetic flux, saturation, B, H, Theta-I curve, I at saturation,
![9-3](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-3.jpg)
<br/>
<br/>
<br/>

## <span style="color:red">Iron loss in a transformer</span>		
---    
Losses in transformer
1. Iron loss (= core loss = no-load loss)
1. Copper loss <br/>

Iron loss = Hysteresis loss + Eddy-current loss <br/> <br/>
![9-4](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-4.jpg)

<span style="color:red">Hysteresis loss</span> <br/>
https://www.motioncontroltips.com/hysteresis-loss/ <br/>
https://circuitglobe.com/what-is-hysteresis-loss.html <br/> <br/>
As the current flows in the forward and reverse directions, the magnetization and demagnetization of the core occur. The magnetic flux of the material decreases slower than the magnetizing force(current) does. When the magnetizing force is applied in the magnetic material, the molecules of the magnetic material are settled to one particular direction. When the magnetizing force is reversed in the opposite direction, the internal friction of the molecular magnets opposes the reversal of magnetism. The wasted energy in the form of heat is called hysteresis loss.  <br/> <br/>

To decrease hysteresis loss, use a material having least hysteresis loop area like a silicon steel.
![9-5](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-5.jpg)

<span style="color:red">Eddy-current loss</span> <br/>
https://en.wikipedia.org/wiki/Eddy_current <br/>
https://www.quora.com/What-is-the-difference-between-induced-current-and-eddy-current  <br/>
https://www.differencebetween.com/difference-between-eddy-current-and-vs-induced-current/ <br/> <br/>
If the closed path is a loop on a plane, the rate of change of the magnetic flux over the area of a loop is proportional to the EMF generated in the loop. The loop is not a conservative field, which does not follow common circuit likes like Kirchhoff's law. The conservative field laws are not valid in an induced field, and therefore a single point can have two different potential values. <span style="color:red">Induced current</span> is the current that results in a conductor because of a time changing magnetic field. The output stator coils generate electrical energy as the changing magnetic field from a moving magnetized rotor passes through a coil. <br/> <br/>

EMFs which is produced by alternating magnetic field circulate current within the body of the material. When the induced electrical current generates their magnetic moments in that conducting core, we call it <span style="color:red">Eddy current</span>. By Lenz's law, these magnetic moments oppose the source magnetic field. (Think these magnetic moments as an opposing force) The circulating current causes resistive losses that transform some form of energy, like kinetic energy, into heat, which increases the temperature of the coil, and reduces the efficiency of devices using magnetic fields. The eddy current losses are independent of load, and are considered as the constant losses. <br/> <br/>

To reduce the eddy current loss,
1. Split the solid core into thin sheets called laminations, in the plane parallel to the magnetic field. Laminating the core reduces the area of each section and the induced EMF of it.
1. Use materials with lower conductivity to make a magnetic core. Power loss = I^2 * R. As resistance gets higher, the current gets lower.
![9-6](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-6.jpg)
![9-7](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-7.jpg)
<br/>
<br/>
<br/>

## <span style="color:red">K-factor transformers</span>		
---  
Harmonics is a distortion of the normal current waveform that are usually transmitted by non-linear loads. As loads are becoming non-linear, more and more harmonics generate additional heat in the transformer. A K-factor transformer is designed not to remove harmonics, but to withstand negative effects by harmonics such as the eddy-current loss.
![9-8](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/9-8.jpg)

### Reference
> - https://www.youtube.com/watch?v=W6-J6ZEsTSQ
> - https://www.youtube.com/watch?v=ETu2BAL8VMw
> - https://www.youtube.com/watch?v=XvFSPbUMAb8&list=PLIieCbnTDrMh5D1h5gXcAl5Dp8IBXatcX&index=14
