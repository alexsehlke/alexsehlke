---
Title: Thermoluminescence
---


# Thermoluminescence (TL)

## Introduction

Thermoluminescence (TL) is a form of luminescence that occurs when a material emits light upon being heated. This phenomenon is commonly used in archaeological dating, geology, and materials science. TL can provide insights into the thermal history of a sample and its exposure to radiation over time.

## Basics of Thermoluminescence

### TL Build-Up

Thermoluminescence build-up occurs when a material is exposed to ionizing radiation, such as sunlight or cosmic rays. The energy from this radiation is absorbed by the material and stored in the form of trapped electrons within defects in the crystal lattice. Over time, these electrons accumulate, and the material builds up a latent luminescence signal.

The rate at which electrons are promoted to traps can be described by a first order rate equation such as:

$$\frac{dn}{dt} = \alpha (N - n) R$$

where $n$ is the number of trapped electrons, $N$ is the total number of available traps, and $R$ is the dose rate, $t$ is time, and $\alpha$ is a rate constant for electrons filling available traps, which can be determined experimentally from the growth curve of TL intensity versus dose.

### TL Decay

When the material is subsequently heated, the trapped electrons gain enough energy to escape from their traps. As they recombine with holes in the crystal lattice, they release the stored energy in the form of visible light. This emission of light is the thermoluminescence signal. The intensity of the emitted light is proportional to the number of trapped electrons, which correlates with the amount of radiation the material has been exposed to.

The decay of the thermoluminescence signal can be described by the following equation:


$$
\frac{dn}{dt} = -n s \exp \left( \frac{E}{kT} \right)
$$

where $ \frac{dn}{dt} $ is the rate of change of the number of trapped electrons over time, $ n $ is the number of trapped electrons, $ s $ is the frequency factor, which is a material-specific constant, $ E $ is the activation energy required for the electrons to escape from their traps, $ k $ is Boltzmann's constant, $ T $ is the absolute temperature, $ \exp \left( \frac{E}{kT} \right) $ is the exponential term describing the probability of the trapped electrons gaining enough energy to escape.

### Combined TL Equation

The overall thermoluminescence process can also be described by combining the build-up and decay processes into a more comprehensive equation. The general TL intensity as a function of time and temperature can be expressed as:

$I = \frac{n_0^2 s}{N} \exp \left( -\frac{E}{kT} \right) \left[ 1 + \frac{n_0 s}{N \beta} \int \exp \left( -\frac{E}{kT} \right) dT \right]^{-2}$


Where all the variables are as previously defined.

## Applications

Thermoluminescence is widely used in various fields such as:
- **Archaeology**: Dating ceramic materials and sediments.
- **Geology**: Understanding the thermal history of rocks and minerals.
- **Material Science**: Studying defects and properties of materials.

Thermoluminescence continues to be a powerful tool for researchers in unraveling the past and understanding the properties of materials.

---

