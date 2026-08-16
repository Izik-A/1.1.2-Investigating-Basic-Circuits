# 1.1.2 Investigating Basic Circuits

## Overview

In this activity, you will build and investigate simple LED circuits. You will measure voltage, apply Ohm’s Law, and compare the behavior of series and parallel circuits.

## Learning Objectives

By the end of this activity, you should be able to:

- Compare voltage, current, and resistance and describe how they are related.
- Identify basic circuit components and explain their functions.
- Measure voltage in a circuit using an auto-ranging digital multimeter (DMM).
- Evaluate how series and parallel component arrangements affect a circuit.
- Use Ohm’s Law to guide circuit construction and analysis.

## Key Questions

As you complete this activity, consider the following questions:

- What is an electrical circuit?
- How can circuit components be arranged to achieve a desired result?
- What are voltage, current, and resistance?
- How are voltage, current, and resistance related?
- How do you measure voltage across components in a circuit?
- How does component arrangement affect circuit behavior?
- How can calculations help you design a circuit before building it?

## Materials

- Breadboarding hardware or Digital MiniSystem (DMS)
- Auto-ranging handheld digital multimeter (DMM)
- Two 470 Ω resistors
  - Color code: yellow, violet, brown, gold or silver
- Two LEDs
- Four 22-gauge solid wires
  - One red
  - One black
  - Two additional colors
- Multipurpose wire stripper
- 5 V DC power source

## Safety and Measurement Notes

- Turn off or disconnect power before changing circuit wiring.
- Always use a current-limiting resistor in series with an LED.
- For voltage measurements:
  - Connect the black meter lead to the `COM` port.
  - Connect the red meter lead to the `VΩ` or `VΩmA` port.
  - Set the DMM to DC voltage mode, typically marked `V⎓`, `VDC`, or `V---`.
  - Place the meter probes in parallel with the component or part of the circuit being measured.
- Because your DMM is self-ranging, it automatically selects the best range. Wait for the displayed reading to stabilize before recording a measurement.
- A negative voltage reading means the red and black probes are reversed relative to the direction selected as positive.

---

# Part A: Simple Circuit and Circuit Measurements

## Step 1: Build a Simple LED Circuit

Construct the circuit shown below using one 470 Ω resistor and one LED.

> **Image Placeholder:** Insert a photo or circuit diagram of the simple 5 V resistor-and-LED series circuit here.

<!-- IMAGE: Simple LED circuit with 5 V source, 470 Ω resistor, and LED -->

Pay attention to LED orientation:

- The flat edge on the LED body identifies the **cathode**.
- Orient the LED with its flat edge, or cathode, toward ground.
- Conventional current should flow from the 5 V rail, through the resistor and LED, to the 0 V/GND rail.

### Checkpoint

**What is the role of the resistor in this circuit?**

> _Write your answer here._

---

## Step 2: Trace Current Flow

In a circuit, **conventional current** is defined as flowing from the positive supply terminal (`VCC`) toward ground (`GND`).

Trace the path of conventional current through your circuit.

### Checkpoint

**Describe the path of conventional current through the circuit. How does electron flow compare with conventional current flow?**

> _Write your answer here._

---

## Step 3: Investigate LED Polarity

With the LED illuminated:

1. Turn off or disconnect power.
2. Reverse the LED so that its flat edge is now oriented toward the positive rail.
3. Restore power and observe the circuit.
4. Turn off power again.
5. Return the LED to its original orientation.
6. Restore power and confirm that it illuminates.

### Checkpoint

**What does your observation tell you about diodes and LEDs?**

> _Write your answer here._

---

## Step 4: Measure Circuit Voltage

Set your auto-ranging DMM to DC voltage mode (`V⎓`, `VDC`, or `V---`).

Measure the voltage across the resistor-and-LED combination:

1. Place the red probe at the top of the resistor, nearest the 5 V rail.
2. Place the black probe at the bottom of the LED, nearest ground.
3. Allow the meter reading to stabilize.
4. Record the measured voltage.
5. Reverse the meter probes and record the new reading.

> **Image Placeholder:** Insert a photo showing DMM probes placed across the resistor-and-LED combination.

<!-- IMAGE: DMM measuring total voltage across resistor and LED -->

| Measurement | Voltage |
|---|---:|
| Red probe at resistor top; black probe at LED bottom | ___ V |
| Probes reversed | ___ V |

### Checkpoint

**What changed when you switched the meter leads? Why did the magnitude of the voltage remain approximately the same?**

> _Write your answer here._

### Voltage Reminder

Voltage is a measure of electric potential difference. A component must have a potential difference across it in order to transfer energy or do work.

$$
\Delta V = V_f - V_i
$$

One volt means one joule of energy is transferred for every coulomb of charge.

$$
1\text{ V} = 1\frac{\text{J}}{\text{C}}
$$

---

## Step 5: Record an Accurate Voltage Measurement

Because your DMM is self-ranging, it automatically selects the most appropriate measurement range.

1. Keep the meter in DC voltage mode.
2. Hold the probes steadily across the resistor-and-LED combination.
3. Wait for the reading to stabilize.
4. Record the displayed value using the number of decimal places shown on the meter.

### Checkpoint

**What voltage did the auto-ranging DMM display across the resistor-and-LED combination? Why is it useful for a multimeter to select a measurement range automatically?**

> _Write your answer here._

---

## Step 6: Measure Voltage Across Wires

With the DMM still set to DC voltage mode:

1. Place the probes at opposite ends of the red wire.
2. Record the voltage.
3. Repeat the process for the black wire.

| Wire | Measured Voltage |
|---|---:|
| Red wire | ___ V |
| Black wire | ___ V |

### Checkpoint

**What do your measurements tell you about the voltage drop across a short connecting wire?**

> _Write your answer here._

---

## Step 7: Measure Individual Component Voltages

In Step 4, you measured the voltage across the resistor and LED together.

Now measure the voltage across each component separately:

1. Measure the voltage across the 470 Ω resistor.
2. Measure the voltage across the LED.
3. Compare the two values with the supply voltage.

> **Image Placeholder:** Insert a photo or diagram showing voltage measurement across the resistor.

<!-- IMAGE: DMM probes across 470 Ω resistor -->

> **Image Placeholder:** Insert a photo or diagram showing voltage measurement across the LED.

<!-- IMAGE: DMM probes across LED -->

| Component | Measured Voltage |
|---|---:|
| 470 Ω resistor | ___ V |
| LED | ___ V |
| Resistor and LED combined | ___ V |

### Checkpoint

**Before measuring the LED, predict its voltage. Was your prediction correct? Why is a resistor necessary in this circuit? How do the component voltages compare with the total supply voltage?**

> _Write your answer here._

### Ohm’s Law

Ohm’s Law relates voltage, current, and resistance.

$$
V = IR
$$

Assume the voltage across the 470 Ω resistor is approximately 3 V.

$$
I = \frac{V}{R}
$$

Calculate the conventional current through the resistor.

$$
I = \frac{3\text{ V}}{470\ \Omega}
$$

**Current in amperes:** ___ A

**Current in milliamperes:** ___ mA

In this circuit, current has only one path through the resistor and LED. Components arranged in a single path are connected **in series**.

---

# Part B: Series and Parallel Circuits

## Step 8: Series Circuits

Build a circuit with two identical 470 Ω resistors connected in series.

> **Image Placeholder:** Insert a circuit diagram or photo of two 470 Ω resistors connected in series.

<!-- IMAGE: Two-resistor series circuit -->

Before building or measuring the circuit, make predictions.

### Predictions

**What voltage do you expect across both resistors together? What voltage do you expect across each resistor individually? Explain your reasoning.**

> _Write your answer here._

**What is the equivalent resistance of two 470 Ω resistors in series?**

$$
R_{\text{eq}} = R_1 + R_2
$$

$$
R_{\text{eq}} = 470\ \Omega + 470\ \Omega
$$

**Equivalent resistance:** ___ Ω

### Measurements

Use the auto-ranging DMM in DC voltage mode to measure the following:

| Measurement Location | Measured Voltage |
|---|---:|
| Across both resistors | ___ V |
| Across resistor 1 | ___ V |
| Across resistor 2 | ___ V |

### Series LED Investigation

Build a series circuit with two LEDs and appropriate current-limiting resistance using a 5 V power source.

> **Image Placeholder:** Insert a photo or diagram of two LEDs connected in series.

<!-- IMAGE: Two LEDs in series with resistor(s) and 5 V source -->

With both LEDs illuminated:

1. Turn off power.
2. Remove one LED from the circuit path.
3. Restore power and observe the result.

### Checkpoint

**What happened when one LED was removed from the series circuit? Why did this occur?**

> _Write your answer here._

Next, try connecting three LEDs in series with the 5 V power source.

### Checkpoint

**Why do you think the three LEDs do not illuminate?**

> _Write your answer here._

---

## Step 9: Parallel Circuits

Build a parallel circuit with two LED branches.

> **Image Placeholder:** Insert a circuit diagram or photo of two LED branches connected in parallel.

<!-- IMAGE: Two LEDs in parallel, each with appropriate current-limiting resistance -->

With both LEDs illuminated:

1. Turn off power.
2. Remove one LED from one branch.
3. Restore power and observe the other branch.

### Checkpoint

**What happens to the remaining LED when one LED branch is removed? How is this different from the series circuit?**

> _Write your answer here._

Draw a circuit diagram for two 470 Ω resistors connected in parallel.

> **Diagram Placeholder:** Draw or insert your two-resistor parallel circuit diagram here.

<!-- IMAGE: Student-created two-resistor parallel circuit diagram -->

---

## Step 10: Analyze Parallel Current

In a series circuit, all components carry the same current. In a parallel circuit, current can divide among separate branches.

### Checkpoint

**What electrical quantity is the same across components connected in parallel?**

> _Write your answer here._

Use Ohm’s Law to calculate the current through each 470 Ω resistor in a parallel circuit connected to a 5 V source.

$$
I = \frac{V}{R}
$$

$$
I_1 = \frac{5\text{ V}}{470\ \Omega}
$$

**Current through resistor 1:** ___ A

$$
I_2 = \frac{5\text{ V}}{470\ \Omega}
$$

**Current through resistor 2:** ___ A

$$
I_{\text{total}} = I_1 + I_2
$$

**Total current:** ___ A

---

# Reflection Questions

Answer each question in complete sentences.

## 1. Measuring Voltage

Describe the correct placement of DMM leads when measuring voltage across a component. Include the settings and steps you use with an auto-ranging DMM to obtain a stable and precise voltage measurement.

> _Write your answer here._

## 2. Negative Voltage Readings

If the multimeter displays a negative voltage value, what does that tell you about the orientation of the DMM leads relative to conventional current flow?

> _Write your answer here._

## 3. LED Characteristics

LEDs and resistors both transfer electrical energy into other forms. What important characteristic makes an LED, as a diode, different from a resistor?

> _Write your answer here._

## 4. Series Circuits

In your own words, describe what it means for components to be connected in series. Which characteristic do series components always have in common: voltage, current, or resistance?

> _Write your answer here._

## 5. Parallel Circuits

In your own words, describe what it means for components to be connected in parallel. Which characteristic do parallel components have in common: voltage, current, or resistance?

> _Write your answer here._

---

# Optional Extension

## Equivalent Resistance in Series

How is equivalent resistance calculated for resistors connected in series?

$$
R_{\text{eq}} = R_1 + R_2 + R_3 + \dots
$$

> _Write your explanation here._

## Equivalent Resistance in Parallel

How is equivalent resistance calculated for resistors connected in parallel?

$$
\frac{1}{R_{\text{eq}}}
=
\frac{1}{R_1}
+
\frac{1}{R_2}
+
\frac{1}{R_3}
+
\dots
$$

> _Write your explanation here._
