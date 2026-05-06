# Detailed Solutions: Mole Concept Basics

This document provides step-by-step solutions for the questions in `qbp-basics.md`.

---

### Question 1: The Scale of Atoms

**Q1.1: Why is it impractical to use "grams" for individual atoms in a lab?**
**Solution:**
Individual atoms have extremely small masses. For example, a Carbon-12 atom weighs approximately $1.99 \times 10^{-23}$ grams. In a laboratory setting, such tiny quantities cannot be measured by conventional balances. Using grams for individual atoms would involve calculations with extremely small exponents, making it mathematically cumbersome and physically irrelevant for macroscopic experiments.

**Q1.2: If we define a "bundle" of atoms such that the mass of the bundle in grams is numerically equal to the atomic mass in amu (12.00), how many atoms must be in that bundle?**
**Solution:**
To find the number of atoms in the bundle:
$$\text{Number of atoms} = \frac{\text{Total mass of the bundle}}{\text{Mass of one atom}}$$
$$\text{Number of atoms} = \frac{12.00 \text{ g}}{1.9926 \times 10^{-23} \text{ g/atom}} \approx 6.022 \times 10^{23} \text{ atoms}$$
This number is known as **Avogadro's Number ($N_A$)**.

---

### Question 2: Counting by Weighing

**Q2.1: What is the molar mass of $H_2O$?**
**Solution:**
Molar mass is the sum of the atomic masses of all atoms in a molecule:
$$\text{Molar mass of } H_2O = 2 \times (\text{Atomic mass of } H) + 1 \times (\text{Atomic mass of } O)$$
$$M = 2(1.008) + 16.00 = 18.016 \text{ g/mol}$$
*(Approximated as $18 \text{ g/mol}$ for basic calculations).*

**Q2.2: How many moles of water molecules do you have in 36 grams?**
**Solution:**
Using the formula: $n = \frac{m}{M}$
$$n = \frac{36 \text{ g}}{18 \text{ g/mol}} = 2 \text{ moles}$$

**Q2.3: How many total atoms (Hydrogen + Oxygen) are present in this sample?**
**Solution:**
1. One molecule of $H_2O$ contains 3 atoms ($2 \times H$ and $1 \times O$).
2. Total number of molecules = $n \times N_A = 2 \times 6.022 \times 10^{23}$.
3. Total number of atoms = $(\text{Number of molecules}) \times (\text{Atoms per molecule})$
$$\text{Total atoms} = 2 \times 6.022 \times 10^{23} \times 3 = 3.6132 \times 10^{24} \text{ atoms}$$

---

### Question 3: The Gaseous State

**Q3.1: What is the volume occupied by 4.4 grams of $CO_2$ at STP?**
**Solution:**
1. Calculate molar mass of $CO_2$: $M = 12 + 2(16) = 44 \text{ g/mol}$.
2. Calculate moles of $CO_2$: $n = \frac{4.4 \text{ g}}{44 \text{ g/mol}} = 0.1 \text{ moles}$.
3. Calculate volume at STP:
$$\text{Volume} = n \times 22.4 \text{ L/mol}$$
$$\text{Volume} = 0.1 \times 22.4 = 2.24 \text{ Liters}$$

**Q3.2: If the pressure is doubled while keeping temperature constant, what happens to the volume of 1 mole of gas?**
**Solution:**
According to **Boyle's Law** ($PV = k$ at constant $T$), pressure and volume are inversely proportional.
If pressure is doubled ($P \to 2P$), the volume must be halved ($V \to V/2$).
$$\text{New Volume} = \frac{22.4 \text{ L}}{2} = 11.2 \text{ Liters}$$

---

### Question 4: Concentration in Solutions

**Q4.1: How many moles of $NaOH$ are present in 40 grams?**
**Solution:**
1. Calculate molar mass of $NaOH$: $M = 23 (Na) + 16 (O) + 1 (H) = 40 \text{ g/mol}$.
2. Calculate moles:
$$n = \frac{40 \text{ g}}{40 \text{ g/mol}} = 1 \text{ mole}$$

**Q4.2: What is the Molarity (moles per liter) of the solution in 500 mL?**
**Solution:**
1. Convert volume to Liters: $500 \text{ mL} = 0.5 \text{ L}$.
2. Use the Molarity formula: $Molarity (M) = \frac{\text{moles of solute}}{\text{Volume of solution (L)}}$
$$M = \frac{1 \text{ mole}}{0.5 \text{ L}} = 2 \text{ mol/L} \text{ (or 2M)}$$
