---
description: >-
  A step-by-step guide to assembling your electronic light post. Learn how to
  arrange the components, connect the circuit safely, and test the power output.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# 💡 Light Post

<p align="center"><sup><em><mark style="color:red;"><strong>Your finished output will be like the picture below.</strong></mark></em></sup></p>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (24).png" alt=""><figcaption></figcaption></figure></div>

## <mark style="color:$primary;">Preparation</mark>

_Gather the required components below before starting the activity._

|            COMPONENT           |                                VISUAL REFERENCE                                |
| :----------------------------: | :----------------------------------------------------------------------------: |
|               LED              | <img src="../.gitbook/assets/Light Post (26).png" alt="" data-size="original"> |
|     Adjustable Power Supply    | <img src="../.gitbook/assets/Light Post (52).png" alt="" data-size="original"> |
| DC Jack Female Power Connector |                  ![](<../.gitbook/assets/Light Post (32).png>)                 |
|      Alligator Clips (2x)      | <img src="../.gitbook/assets/Light Post (27).png" alt="" data-size="original"> |

***

## <mark style="color:$primary;">Pictorial Diagram</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (4).png" alt=""><figcaption></figcaption></figure></div>

***

## 💡The LED

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (40).png" alt=""><figcaption></figcaption></figure></div>

***

<figure><img src="../.gitbook/assets/Light Post (49).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:$primary;">Step-By-Step Process</mark>

<details>

<summary><strong>Powering Up Your Circuit</strong></summary>

{% stepper %}
{% step %}
## <mark style="color:$primary;">Step 1: Prepare the Power Source</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption><p>Firmly connect the male DC plug from your power supply into the DC female jack connector to prepare your power source.</p></figcaption></figure></div>
{% endstep %}

{% step %}
## <mark style="color:$primary;">Step 2: Connect Female Jack Connector to LED</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption><p>Connect the red alligator clip from the positive (+) power supply terminal to the LED anode (long leg).</p></figcaption></figure></div>
{% endstep %}

{% step %}
## <mark style="color:$primary;">Step 3: Power the Circuit</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption><p>Ensure the power supply voltage knob is turned completely counter-clockwise to 0V. </p></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption><p>Turn on the power supply. </p></figcaption></figure></div>

{% hint style="warning" %}
<sup>**Important Step:**</sup> <sup></sup><sup>Always set your power supply voltage before connecting it to the circuit. Once set, turn the power supply OFF or disconnect the clips before wiring to prevent damage to the LED.</sup>
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption><p>Slowly turn the voltage knob clockwise until the display approximately reads 3.0V. </p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

</details>

***

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure></div>

### 🏆<mark style="color:$success;">Success!</mark>

Your LED is **illuminated**. You have successfully completed the circuit, establishing a continuous path for electrical current to travel to the LED.

***

## <mark style="color:$primary;">Step 4: Test the Voltage</mark>

_Observe how changes in electrical pressure (voltage) affect the circuit._

### <mark style="color:$tint;">Test: Raising the Voltage</mark>

* Slowly turn the voltage knob up to 7V.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure></div>

�&#xDD0D;_&#x57;hat do you observe?_&#x20;

* [x] The LED brightens significantly, flashes and turns off permanently.
* [ ] The LED dims.
* [ ] Nothing changes.

<details>

<summary>✅<strong>Correct Answer</strong></summary>

* [x] The LED brightens significantly, flashes and turns off permanently.

***

💡**Explanation:** When you push too much electricity through an LED, it gets too hot and burns out, just like a balloon pops if you blow it up too big. This happens because the LED has a limit on how much power it can safely handle.

</details>

***

## 📗<mark style="color:$primary;">Core Concept: Voltage and Current</mark>

<figure><img src="../.gitbook/assets/Light Post (37).png" alt=""><figcaption></figcaption></figure>

To understand how electricity works, it is helpful to compare it to water flowing through a pipe.

**⚡Voltage (V):** This is the electrical pressure that pushes electrons through a circuit, much like water pressure from a pump. It is measured in _**Volts (V)**_.

**➡️ Current (I):** This is the rate at which electrons flow through the wire, similar to the volume of water moving through a pipe. It is measured in _**Amperes**_, or **Amps (A)**.

***

## <mark style="color:$primary;">Switching to a Battery (Introducing Resistance)</mark>

## 🔋The Battery

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (45).png" alt=""><figcaption></figcaption></figure></div>

***

#### 🎯<mark style="color:$warning;">Challenge:</mark> Connect the LED to a fixed 9V Battery instead of the adjustable power supply.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (50).png" alt=""><figcaption></figcaption></figure></div>

�&#xDD0D;_&#x57;hat do you observe?_&#x20;

* [x] The LED brightens significantly, flashes, and turns off permanently.
* [ ] The LED dims.
* [ ] Nothing changes.

<details>

<summary>✅<strong>Correct Answer</strong></summary>

* [x] The LED brightens significantly, flashes, and turns off permanently.

***

💡**Explanation:** Connecting a 9V battery directly to an LED destroys it because the battery provides too much voltage for the tiny component to handle.

</details>

#### **⚠️How To Fix It**

A 9V battery is too strong for the LED, so we use a resistor to slow down the electricity. Think of it like pinching a hose to keep the flow at a safe, steady level!

***

### 💡 The Solution: Introducing Resistance

_To protect the LED from burning out, we must add a Resistor to the circuit path._

<table><thead><tr><th width="259" align="center">COMPONENT</th><th align="center">VISUAL REFERENCE</th></tr></thead><tbody><tr><td align="center">9V Battery</td><td align="center"><img src="../.gitbook/assets/Light Post (30).png" alt="" data-size="original"></td></tr><tr><td align="center">330 Ω Resistor</td><td align="center"><img src="../.gitbook/assets/Light Post (29).png" alt="" data-size="original"></td></tr><tr><td align="center">LED</td><td align="center"><img src="../.gitbook/assets/Light Post (26) (2).png" alt="" data-size="original"></td></tr><tr><td align="center">Alligator Clips (3x)</td><td align="center"><img src="../.gitbook/assets/Light Post (27) (1).png" alt="" data-size="original"></td></tr></tbody></table>

***

<p align="center"><sup><em><mark style="color:red;"><strong>Your finished output will be like the picture below.</strong></mark></em></sup></p>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (14).png" alt=""><figcaption></figcaption></figure></div>

## <mark style="color:$primary;">**Pictorial Diagram**</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (7).png" alt=""><figcaption></figcaption></figure></div>

***

_Follow these steps to safely connect your components and complete the circuit loop:_

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Light Post (51).png" alt=""><figcaption></figcaption></figure></div>

## <mark style="color:$primary;">Step-By-Step Process</mark>

<details>

<summary><strong>Powering Up Your Circuit</strong></summary>

{% stepper %}
{% step %}
## <mark style="color:$primary;">Step 1: Prepare the Power Source</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption><p>Connect the red alligator clip to the positive (+) terminal of the 9V battery.</p></figcaption></figure></div>
{% endstep %}

{% step %}
## <mark style="color:$primary;">Step 2: Attach the Resistor</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption><p>Connect the red positive (+) wire of the alligator clip to either leg of the 330 Ω resistor.</p></figcaption></figure></div>
{% endstep %}

{% step %}
## <mark style="color:$primary;">Step 3: Connect to the LED</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption><p>Attach the remaining leg of the resistor to the longer leg (Anode / Positive) of the LED.</p></figcaption></figure></div>
{% endstep %}

{% step %}
## <mark style="color:$primary;">Step 4: Complete the Circuit</mark>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption><p>Connect one end of the yellow alligator clip to the shorter leg (cathode / negative) of the LED, and the other end to the negative (-) terminal of the battery.</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

</details>

�&#xDD0D;_&#x57;hat do you observe?_&#x20;

* [x] The LED lights up safely and stays glowing.
* [ ] The LED flashes brightly and turns off permanently.
* [ ] The LED does not light up at all.

<details>

<summary>✅<strong>Correct Answer</strong></summary>

* [x] The LED lights up safely and stays glowing.

***

💡**Explanation:** By adding the 330 Ω Resistor, you successfully controlled the battery's power. The resistor acts as a safety bottleneck, blocking the dangerous extra voltage before it can reach the light. This leaves just the right amount of safe pressure for the LED to glow brightly without burning out.

</details>

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

### 🏆<mark style="color:$success;">Success!</mark>

Your LED is **illuminated**. You have successfully completed the circuit, establishing a continuous path for electrical current to travel to the LED.

***

## 📗<mark style="color:$primary;">Core Concept: Resistance</mark>

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

* 📏 **Resistance&#x20;**_**(R)**_**:** It is the opposition or friction against the flow of electrical current. It acts exactly like a deliberate narrowing in a water pipe, restricting how easily electrons can move through a circuit.

**📋 Key Takeaways**

* It lowers high voltage safely to protect sensitive parts.
* It is measured in **Ohms (Ω)**. A higher value means a tighter bottleneck.

**⚠️ Why it matters:** Without resistance to manage the power source, components like LEDs will pull too much current and burn out instantly.

***

### <mark style="color:$success;">🎉 Quest Complete: Circuit Protector!</mark>

You have successfully completed your first hardware challenge! By mastering the concept of resistance, you safely protected your component from damage.

* **🏆 Badge Unlocked:** _The Current Controller_
* **🔋 Progress:** <mark style="color:$success;">Level 1 Basics Cleared!</mark>

#### 🔓 Next Quest: Building the Light Post (The Pro Way!)

Ready to level up? Now that you know how to connect parts, it is time to use a breadboard!

A breadboard helps you keep your wires tidy and makes your circuit look professional. In this challenge, you will take the same parts from your first project and build your light post on the breadboard.

Click <mark style="color:$success;">Next</mark> to start!

***
