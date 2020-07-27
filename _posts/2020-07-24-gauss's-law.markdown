---
layout: post
title:  "3. Gauss's Law, Electric flux, Corona phenomenon, Electric potential gradient"
categories: Electrical_engineering
tags: Electromagnetism
comments: true
---

- Contents
	- [Gauss's Law, instead of Coulomb's Law, to calculate the Electric field](#gauss's-law,-instead-of-coulomb's-law,-to-calculate-the-electric-field)
	- [Sample problem, divergence theorem, and Maxwell's first equation](#sample-problem,-divergence-theorem,-and-maxwell's-first-equation)
<br/>

## <span style="color:red">Gauss's Law, instead of Coulomb's Law, to calculate the Electric field</span>		
---  
Instead of utilizing Coulomb's Law, which requires a lot of integrations, I focused on Gauss's Law to calculate the Electric field. To use Gauss's Law, the source that produces the electric field must have a high degree of symmetry.

<br/>
Gauss's Law:
<br/>
The total of the electric flux out of a closed surface is equal to the charge enclosed divided by the permittivity.
- Flux describes how much of things go through a certain area. Electric flux measures the number of electric field lines (electric lines of force) passing through an area.
![3-1](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-1.jpg)  

- Permittivity is a measure of the electric polarizability of a dielectric. Polarizability is the ability to form instantaneous dipoles. Materials with higher permittivity polarizes more, and, therefore, store more energy in the material, when external electric field applied.
![3-2](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-2.jpg)
- Noticeable terms: Polarization, Displacement current, conduction current and drift current
![3-3](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-3.jpg)  
<br/>
<br/>
<br/>

## <span style="color:red">Sample problem, divergence theorem, and Maxwell's first equation</span>
Noticeable terms: Spherical coordinates, Cylindrical coordinates, Divergence theorem, Maxwell's first equation, and Curl
---
![3-4](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-4.jpg)  
![3-5](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-5.jpg)  
![3-6](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-6.jpg)  
![3-7](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-7.jpg)
<br/>
<br/>

## <span style="color:red">Corona phenomenon, Critical disruptive voltage</span>
---
https://en.wikipedia.org/wiki/Corona_discharge
A corona discharge is an electrical discharge brought on by the ionization of a fluid such as air surrounding a conductor that is electrically charged. Spontaneous corona discharges occur naturally in high-voltage systems unless care is taken to limit the electric field strength. A corona will occur when the strength of the electric field (potential gradient) around a conductor is high enough to form a conductive region, but not high enough to cause electrical breakdown or arcing to nearby objects. It is often seen as a bluish glow in the air adjacent to pointed metal conductors carrying high voltages, and emits light by the same property as a gas discharge lamp.
- Simply, corona discharge is the current discharge in the air.

Critical Disruptive Voltage is the minimum phase to neutral voltage required for the Corona discharge, which is the breakdown of insulating properties of air.

![3-8](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-8.jpg)
![3-9](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-9.jpg)
![3-10](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-10.jpg) 
<br/>
<br/>

## <span style="color:red">Electric potential gradient</span>
---
Electric potential gradient is the rate of change of electric potential with respect to displacement, which can be the rate of change of voltage with respect to displacement. The concept of electric potential gradient allows us to get the magnitude of the electric field from the rate of change of voltage.  
-	When the magnitude of voltage is equal, the cable with the less magnitude of the electric potential gradient at the surface will have less possibility to cause a dielectric breakdown, which means losing the insulation property of surroundings like air.
![3-11](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-11.jpg)
![3-11](https://kohmbae.github.io/assets/img/Electrical_engineering/Electromagnetism/3-12.jpg)


### Reference  
> - https://en.wikipedia.org/wiki/Permittivity
> - https://en.wikipedia.org/wiki/Polarizability
> - https://www.youtube.com/watch?v=j-DYTwmdhgo&list=PLIieCbnTDrMhrN79sjFwlqUa--bUqeOP5&index=2
> - https://www.youtube.com/watch?v=eX9D_JClQTY&list=PLIieCbnTDrMhrN79sjFwlqUa--bUqeOP5&index=3
> - https://eng.libretexts.org/Bookshelves/Materials_Science/Supplemental_Modules_(Materials_Science)/Optical_Properties/Dielectric_Polarization
