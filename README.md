Download Link: https://assignmentchef.com/product/solved-uwee572-lab5-2-5-ghz-lpf-design
<br>
To design, construct, and test low-pass filters. In this HW, simulations will be done with ED using the ideal TL model, physical TL model, and layout with EM simulations.  You will see substantial differences between the ideal TL simulations and other cases.  Microwave devices designed for above 2 GHz range should be simulated with the full EM simulation tools.

<strong>Introduction:</strong>

Different types of filters (LPF, HPF, and BPF) can be designed by changing the size and shape of TL at the microwave frequency.   The insertion loss method and the stepped impedance method are often used for the LPF design.

In this HW your are asked to design two different types of LPFs using the ideal TL model.  One of them must be refined using the physical TL model and EM simulations to satisfy the requirements.  Duroid 5870 will be used as a substrate. It is important to note that the effective dielectric constant (or wavelength) depends on the line width (characteristic impedance).  Also to satisfy the fabrication requirement, the minimum TL width should be greatern than 0.4mm.

<strong>Reference:</strong>

ED tutorial including EM simulations

EE572 Lecture notes <strong>Supplies:</strong>

Double-sided PC board

Duroid 5870, <sub>r</sub>=2.33 – <em>j</em>0.0028, d=1.57mm (62 mil) <strong>Important: The minimum TL width should be greater than 0.4 mm.</strong>

<h1>I. LPF Design and Simulations Using Ideal TL Model</h1>

The first step of this project is to design 2 LPFs using the ideal TL model.  They are butterworth and stepped impedance.  You do not need to include “T”, “step”, and “cross” in the ED simulations.  The microstrip TL (Ideal TL) is specified by Zo and electrical length (phase) at the given frequency. You don’t need to worry about the min width of TL in this section.  The cutoff frequency of simulationss will/should agree with the calculation.

<strong>Assignment 1: Butterworth Filter Simulations</strong>

Using the insertion loss method and maximally flat response, design a LPF.  The filter must have the following characteristics.  <strong><u>Cutoff freq.=2.5 GHz</u></strong>, maximally flat response, and minimum attenuation of  25 dB at 5 GHz.

-Using the ideal TL, simulate your design in Designer.  The passband response and cutoff frequency should be close to the expected one.

-Plot S<sub>11</sub>and S<sub>21</sub> from 1 to 10 GHz.

<strong>Assignment 2: Stepped Impedance Filter Simulations</strong>

Using the stepped impedance method, design a LPF.  The filter must have the following characteristics.  <strong><u>Cutoff freq.=2.5 GHz</u></strong>, maximally flat, and minimum attenuation of 20 dB at 5 GHz.  Assume <strong>Z</strong><strong><sub>high</sub> is 150 </strong><strong> and Z</strong><strong><sub>low</sub> is 15 </strong><strong>.</strong>

-Using the ideal TL, simulate your design in Designer.  The passband response and cutoff frequency should be close to the expected one. -Plot S<sub>11</sub>and S<sub>21</sub> from 1 to 10 GHz.

<h1>II. LPF Design and Simulations Using Physical TL Model</h1>

<u>Choose one LPF design to conduct detailed simulations and prepare for fabrication. You don’t need to do Section II for both LPFs</u>

This part should be done with the physical TL model.  All details must be included.  <strong>Also the minimum TL width should be greater than 0.4mm.  Both circuit and EM simulations must be done.  </strong>

<strong>If you choose the stepped impedance LPF,  you may need to adjust the width of TL. The TL width of Z</strong><strong><sub>low</sub>=15 ohm is 21.3 mm which is too wide and may create a strange result.</strong>

<strong>Circuit Simulations</strong>

<ul>

 <li>Include all details and physical characteristics of microstrip TLs in your model and simulate the response.</li>

 <li>If your LPF does not meet the specifications, revise and optimize your circuit.</li>

 <li>Create a layout. Make sure the minimum TL is greater than 0.4mm.  Also leave 10 mm section of 50 ohm TL on both end. These TLs are for attaching SMA connectors. Numerical simulations must be done without tapers.  <strong>Do not attach tapers to the 50 ohm TLs.</strong></li>

</ul>

<strong>EM Simulations</strong>

<ul>

 <li>Conduct the EM simulation of LPF layout.</li>

 <li>If your LPF does not meet the specifications, revise and optimize your circuit.</li>

</ul>

<strong>Final Layout File: </strong>

The Garber file is commonly used for the PCB fabrication.   However, it is not required in this assignment.

The final layout must contain a reference 10 mm square (or 10 mm line).

<h1>IV. Report and Discussion</h1>

<strong>The following items must be included.</strong>

<ol>

 <li>Intro/Objectives</li>

 <li>Calculation Simulations Data from ED Ideal TL case</li>

</ol>

Physical TL case

EM

<ol start="3">

 <li>Circuit layouts</li>

 <li>Discussion</li>

</ol>

<strong>Examples of LPFs</strong>

Fig. *: Low pass filter (Cutoff=3 GHz)