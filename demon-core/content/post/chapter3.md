---
author: Justin
title: "Document 3: Neutron Control"
date: 1942-02-12
description: Information dump
math: true
---
<br>

## <ins>K-infinity and K-effective</ins>

In order to determine whether a reaction will go critical, we must have a way of calculating $k$. However, there are two variants of $k$ to consider: we define $k_{eff}$ as the ratio of neutrons produced in the $(n+1)$th stage of fission against the number of neutrons from the $n$th stage of fission, whereas $k_{\infty}$ is this ratio but in a system of infinite size where there is **no loss from leakage**.

This means in $k_{eff}$, we have to consider a *leakage* term which affects the number of neutrons that can trigger a chain reaction.

Therefore, we have the following:

$$
\frac{k_{eff}}{k_{\infty}} = \frac{\frac{\text{Fission}}{\text{Absorption} + \text{Leakage}}}{\frac{\text{Fission}}{\text{Absorption}}} = \frac{\text{Neutrons Absorbed}}{\text{Neutrons Absorbed} + \text{Neutrons Leaking Out}}
$$

In other words, $k_{eff} = k_{\infty}P$ where $P$ is called the non-leakage probability. Adjusting $P$ will determine whether we can turn the system critical!

## <ins>The Six-Factor Formula</ins>

Neutron multiplication can also be described by the six-factor fomula $k_{eff} = \eta f p \epsilon P_{FNL}P_{TNL} = k_{\infty} P_{FNL}P_{TNL}$, where,

- Thermal fission factor (eta / $\eta$)
    - the ratio of neutrons produced to neutrons absorbed (determined by the material chosen)
- Thermal utilization factor ($f$)
    - $f = \frac{\text{neutrons absorbed by the fuel isotope}}{\text{neutrons absorbed anywhere}}$
    - Among all absorbed neutrons, the more is absorbed by the fuel, the higher k is. 
- Resonance escape probability ($p$)
    - the probability that neutrons esccape capture and reach thermal energies where they may cause fission
- Fast fission factor (epsilon / $\epsilon$)
    - $\epsilon = \frac{\text{total number of fission neutrons}}{\text{number of fission neutrons from just thermal fissions (slow neutron fission)}}$
- Fast non-leakage probability ($P_{FNL}$)
    - $\frac{\text{number of fast neutrons that do not leak from reactor}}{\text{number of fast neutrons produced by all fissions}}$
    - Here, fast neutrons refers to neutrons which can trigger a reaction. 
    - The less leakage, the higher k is. 
- Thermal non-leakage probability ($P_{TNL}$)
    - $\frac{\text{number of thermal neutrons that do not leak from reactor}}{\text{number of thermal neutrons produced by all fissions}}$
    - The less leakage, the higher k is. 

## <ins>Controlling k and Avoiding Criticality</ins>
When properly manipulated, the $p$ and $f$ factors of $k$ can keep $k$ as close to 1 as possible, and this is done in a nuclear reactor to harness to power of fission.

$k$ is reliant on leakage and absorption, and there are ways to control fission to avoid criticality (or supercriticality) when we don't want it.

These include:

### Geometry
The shape of the fissionable material affects the likelihood of an escaping neutron from fission being surrounded by more fissionable material or a reflector. A **sphere** will go critical with the least fissionable material as it has the **smallest surface area**. This is why *rods* are used in nuclear reactors, as the neutrons can escape easily.