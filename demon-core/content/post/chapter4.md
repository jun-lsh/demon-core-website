---
author: Justin
title: "Fundamentals 4: Dose Rate"
date: 1945-08-13
description: When radiation passes through objects, it deposits energy, and of course, we need ways of quantifying it.
math: true
---

<br>

## <ins>Units of Dose</ins>

As a radiation particle loses energy traveling through a material, it ionizes nearby atoms and molecules. This energy deposited is what we call a *dose* of radiation. 

The Roentgen is a commonly used unit, which is defined as:

$$
\text{One Roentgen is the amount of radiation that will deposit 1 esu in 1 cubic centimeter of air at S.T.P}
$$

(esu refers to *electrostatic unit of charge*, otherwise known as a *statcoulomb*)

Since usually we are concerned with radiation energy deposited in human tissue, the *gray* (Gy) was proposed as a unit.

$$
\text{One gray (Gy) is the amount of radiation that will deposit 1 J of energy in 1 kg of tissue}
$$

However, energy alone will not let us quantify the effects of radiation. As the *density* of ionization is important as well, we multiply the energy deposited (the dose) with a *quality factor* $Q$, which varies for neutrons of different energies and the different types of radiation.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky" colspan="2">Type of radiation</th>
    <th class="tg-0pky">Quality Factor (Q)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" colspan="2">X, gamma or beta radiation</td>
    <td class="tg-0pky">1</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2">Alpha particles, multiple-charged particles</td>
    <td class="tg-0pky">20</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2">Fission fragments, heavy particles of unknown charge</td>
    <td class="tg-0pky">20</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2">Neutrons of unknown energy</td>
    <td class="tg-0pky">10</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="8">Neutrons</td>
    <td class="tg-0pky">Neutron Energy (MeV)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">2.5 * 10^-8</td>
    <td class="tg-0pky">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">1*10^-5</td>
    <td class="tg-0pky">2</td>
  </tr>
  <tr>
    <td class="tg-0pky">1*10^-2</td>
    <td class="tg-0pky">2.5</td>
  </tr>
  <tr>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">11</td>
  </tr>
  <tr>
    <td class="tg-0pky">5</td>
    <td class="tg-0pky">8</td>
  </tr>
  <tr>
    <td class="tg-0pky">20</td>
    <td class="tg-0pky">8</td>
  </tr>
  <tr>
    <td class="tg-0pky">400</td>
    <td class="tg-0pky">3.5</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2">High-energy protons</td>
    <td class="tg-0pky">10</td>
  </tr>
</tbody>
</table>

The resultant value is the *dose equivalent* with the units *sievert* (Sv). 