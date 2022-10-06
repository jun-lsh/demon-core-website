---
author: Justin
title: "Document 9: Accident Report"
date: 1946-05-22
description: 
math: true
---

<br>

## <ins>Recalling Fundamentals</ins>

The Demon Core itself is a barely sub-critical plutonium sphere, so how did it attain a prompt supercritical state in the two accidents? We know that it was triggered by neutron reflectors, but the chain of events is actually more complex than just an increase in neutron reflection.

### A more detailed expression for $k_{eff}$

Recall that we write $k_{eff}$ as a ratio of *gained neutrons* to *lost neutrons*. As a set of brief descriptions of terms often used in these calculations:

- In calculation we have to consider the *flux-averaged* macroscopic cross-section (often denoted as $\Sigma$), which describes the probability of a nuclear reaction occuring across an area when neutrons are being blasted at it.
- We also have to consider the *neutron flux* (often denoted as $\Phi$) which describes the number of neutrons passing through a unit area in a unit time.

These two values when multiplied together describes *the number of effective neutrons able to cause a reaction in unit time*.

With this, we can express the following:
- The **gain** group equation only consists of fission, described as $\nu\overline{\Sigma_{f}}\Phi$ where $\nu$ is the number of neutrons per fission.

- There are two **loss** equations
    - The first accoounts for absorption, described as $\overline{\Sigma_{a}}\Phi$
    - The second accounts for leakage due to geometry, described as $\overline{D}B^2_g\Phi$, where $D$ is the diffusion coefficient which denotes how easily a neutron would diffuse through a material and $B^2_g$ is the *geometric buckling* of the geometry, which in the case of a sphere is $(\frac{\pi}{R})^2$ where $R$ is the radius of the sphere. 

These leads to an overall expression of

$$
k_{eff} = \frac{\nu\overline{\Sigma_{f}}\Phi}{\overline{\Sigma_{a}}\Phi + \overline{D}B^2_g\Phi} = \frac{\nu\overline{\Sigma_{f}}}{\overline{\Sigma_{a}} + \overline{D}B^2_g} 
$$

Now, we can analyse the various stages of the accident.

### The Demon Core at rest, partially covered.

At this stage, the sphere is still subcritical. When the top hemisphere is lowered, the leakage term decreases, increasing $k_{eff}$. However, $k_{eff} < 1$ at this stage still.

### The Demon Core once the screwdriver slips.

Here, the leakage term drops rapidly, causing $k_{eff}$ to go over $1$. The sphere is now *prompt-supercritical* This means the amount of reactivity added is greater than the fraction of delayed neutrons so there is no slow feedback of neutrons to be had. There is an exponential increase in power within milliseconds.

### The Demon Core is now prompt-supercritical with a blue glow.

Lots of power is released in one go and the core gets very hot. Neutrons are travelling father and faster, increasing leakage far more than the increase in rate of reaction. $k_{eff}$ decreases, but does not go sub-critical.

### Fission products begin building up

Krypton (Kr) is a product of the fission of plutonium, an element with a high absorption cross section. This lowers the 