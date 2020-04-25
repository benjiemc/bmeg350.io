# Renal Physiology - Engineering

[Biology](Renal_Physiology.md) | [Engineering](Renal_Physiology_Eng.md) | [Home]

## Hemodialysis
> __Learning Objectives__
> * Define hemodialysis structure/components
> * Dialyzer function - Hollow fiber dialyser
> * Pumps function

### Dialysis
* Removing excess water, solutes, and toxins from blood when kidney's fail
* _Hemodialysis_: Blood filtered outside body (dialysis machine)
* _Peritoneal dialysis_: Dialysis fluid introduced in abdominal cavity
  * Peritoneum serves as filtering membranse

### Hemodialysis Machine
<img src="./Figures/hemodialysis%20machine.png">

* Electo-mechanical hydraulics device
* FDA-Regulated medical equipment
  * Electrical leakage to patient is a significant concern
  * __IEC 60601-1__ - product safety standard for electrical medical equipment
    * IEC 60601-2-16 - hemodialysis equipment
    * IEC 60601-2-39 - peritoneal dialysis equipment

### Working Principles
* __Dialyzer-artificial kidney:__ semi-permeable membrane placed between blood and dialysate, solute moves across membrane
* __Dialysate:__ fluid used in dialysis to adjust extracellular fluid composition


#### Diffusion
* Fick's Law:
  
    $J_{Ax} = -D_{Ax}\frac{\partial C_A}{\partial x}$

* C<sub>A0</sub> and C<sub>AL</sub> are boundary conditions

    $J_{Ax} = \frac{D_{Ax}}{L}(C_{A0} - C_{AL} \approx k_M \cdot (C_{A0} - C_{AL})$
    * K<sub>M</sub> membrane permeability (m/s)
* Hollow Fiber - increase SA
    
    <img src="./Figures/Hollow%20fibre.png">

    * Fibres, baths outside
    * ~ 10,000 to 15,000 fibres, bundled in plastic jacket
    * Diameter = 200 to 300 $\mu m$
* Parallel Plate Dialyzer - early methods

#### Ultrafiltration
* __Membrane Ultrafiltration Coefficient__: water permeability of membrane per unit of pressure and surface area
    $K_{UF}=\frac{Q_{UF}}{TMP} \cdot \frac{1}{A}$
    * TMP: Transmembrane pressure
* __Filter Ultrafiltration Coefficient__:

    $DK_{UF} = K_{UF} \cdot A$


### Blood Pump

#### Mechanism - Peristaltic Pump
* Blood, dialysate, water, and saline
* No direct contact with fluid
* DC or AC motor with Variable speed

<img src="./Figures/peristaltic%20pump.png">

* rotating contact elements
* Alternate compression and relaxation of tube

#### Mechanism - Heparin Pump
* Syringe pump mechanism: lower volume fluids such as heparin
* Plastic
* Driven by stepper motor

#### Air Bubble Detection
* Can cause embolism
* Sensor: Ultrasonic transducers, light beam
  * Stop blood flow pump, clamp venous


[Biology](Renal_Physiology.md) | [Engineering](Renal_Physiology_Eng.md) | [Home]

[Home]:../../index.md