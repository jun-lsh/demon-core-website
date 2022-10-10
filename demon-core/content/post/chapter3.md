---
author: "Justin"
title: "Fundamentals 3: Neutron Control"
date: "1942-02-12"
description: "Controlling the neutron multiplication factor is crucial and understanding how we can calculate it gives us an idea of what factors contribute to it."
math: true
---
<br>

## <ins>Defining $k_{\infty}$ and $k_{eff}$ </ins>

In order to determine whether a reaction will go critical, we must have a way of calculating $k$. However, there are two variants of $k$ to consider: we define $k_{eff}$ (K-effective) as the ratio of neutrons produced in the $(n+1)$th stage of fission against the number of neutrons from the $n$th stage of fission, whereas $k_{\infty}$ (K-infinity) is this ratio but in a system of infinite size where there is **no loss from leakage**.

This means in $k_{eff}$, we have to consider a _leakage_ term which affects the number of neutrons that can trigger a chain reaction.

Therefore, we have the following:

$$
\frac{k_{eff}}{k_{\infty}} = \frac{\frac{\text{Fission}}{\text{Absorption} + \text{Leakage}}}{\frac{\text{Fission}}{\text{Absorption}}} = \frac{\text{Neutrons Absorbed}}{\text{Neutrons Absorbed} + \text{Neutrons Leaking Out}}
$$

In other words, $k_{eff} = k_{\infty}P$ where $P$ is called the non-leakage probability. Adjusting $P$ will determine whether we can turn the system critical!

If a system goes critical after <a class="tooltip">one generation of reaction<span>Which in this case means we do not consider delayed neutrons, or neutrons which come from successive generations of reaction.</span></a>, it is called _**prompt critical**_

## <ins>Controlling k and Avoiding Criticality</ins>
When properly manipulated, the $p$ and $f$ factors of $k$ can keep $k$ as close to 1 as possible, and this is done in a nuclear reactor to harness to power of fission.

$k$ is reliant on leakage and absorption, and there are ways to control fission to avoid criticality (or supercriticality) when we don't want it.

### Geometry
The shape of the fissionable material affects the likelihood of an escaping neutron from fission being surrounded by more fissionable material or a reflector. A **sphere** will go critical with the least fissionable material as it has the **smallest surface area**. This is why *rods* are used in nuclear reactors, as the neutrons can escape easily.

### Neutron Absorbers (aka Nuclear Poison)
Neutron absorbers are another way of controlling $k$ as an absorbed neutron is essentially the same as an escaped neutron. 

### Temperature
When the temperature rises, the average thermalized neutron energy increases, causing the speed of neutrons to increase. This means the possibility of escape increases further. 

### Moderators
However, the speed of neutrons can be decreased by moderators, which would increase the likelihood of neutrons being reflected back into the fissionable material.

### Reflectors
And usually, good moderators are also good reflectors. Reflectors cause the neutrons to change direction and (as the name would imply), reflect back to the fissionable material and continue the fission chain reaction.