---
title: "What is decibel (dB)? A better explanation for students"
postdate: December 30, 2021
image: "/images/db.jpg"
description: " Decibel (dB) is a logarithmic unit used by engineers to measure power, voltage/current or sound level"
alt: "An explanation of decibel (dB)"
weight: "23"
author: Mohammad Abdul
categorylink: /categories/electronics
categories: ["Electronics"]
type: posts
wordcount: false
mathjax: true
draft: false
---

<img src="/images/db.jpg" alt="decibel formula">

{{< ste >}} Decibel (dB){{</ ste >}} is a logarithmic unit used by engineers to measure power, voltage/current or sound level.

It is mostly used when there is loss or gain in power (or signal strength), pressure, voltage or sound level.

In essence the {{< ste >}} dB{{</ ste >}} is a measure of the ratio between two parameters. The parameter can be a signal strength from one point to another in a transmission line, pressure between two points, voltage between two points etc.

In transmission medium where power or signal strength is important, when there is loss (attenuation), decibel value is negative and when there is gain (amplification) decibel value is positive.

The formula for decibel is expressed below;

For power: $dB = 10\log_{10}{\frac{P_{2}}{P_{1}}}$ where $P\_{1}$ is a ref.

For magnitude (voltage, pressure or current): $dB = 20\log_{10}{\frac{V_{2}}{V_{1}}}$ or $20\log_{10}{\frac{I_{2}}{I_{1}}}$ where $V_{1}$ and $I_{1}$ are reference value respectively.

{{< ste >}} For example (1) {{</ ste >}}
<br>

When a signal is transmitted from point 1 to 2 and the power from point 1 to 2 is 10w and 5w respectively.

$dB = 10\log_{10}{\frac{5}{10}} = 10\log_{10}{(0.5)} = -3dB$. This is to say that $P_{2}$ is $\frac{1}{2}$ of $P_{1}$ (ref)

hence, $dB = 10\log_{10}{\frac{0.5P_{1}}{P_{1}}}$.

{{< ste >}} What if we have 0dBm {{</ ste >}}; it simply means there is no loss as the power transmitted (at the transmitting point) is same as the power received at the receiving end.

$dB = 10\log_{10}{\frac{P_{2}}{P_{1}}}$ if $P_{2} = P_{1}$, $dB = 10\log_{10}{\frac{P_{1}}{P_{1}}} = 10\log_{10}{(1)} = 0dB$

{{< ste >}} For example (2){{</ ste >}}
<br>

When the voltage at (point 1) is 4v and at (point 2) is 2v then it expression in dB will be
$dB = 20\log_{10}{\frac{2}{4}} = -6dB$.

<blockquote class="blockquote">
<p class="little-nugget">Note</p>
<p class="quote-text">In the context of power -3dB is means half of the reference or transmitted power. While in voltage -6dB refers to half of the reference value.</blockquote>
<br>

However when you see -3dB, it doesn’t simply mean there is a power loss or -6db means there is a voltage loss because dB is just a unit that does not simply elaborate in what context it need to be used or mean.

Rather there are some subscript that is written beside dB to tell you if it is in the context of power or magnitude (voltage, current or pressure).

For voltages, it is denoted as $dB_{V}$ where the V stands for voltage.

For power, it is denoted as $dB_{m}$ where the m stands for milliwatt.

Since we have been taking about decibel (dB) in terms of loss so let's talk about gain.

As for gain, the value will be positive so a $+3dB_{m}$ means a gain that is twice the value of the reference power. To calculate for this,

$dB_{m} = 10\log_{10}{\frac{P_{2}}{P_{1}}} = 10\log_{10}{\frac{2P_{1}}{P_{1}}} = +3dbm$ where $P_{2}$ is twice the reference value $P_{1}$.

{{< ste >}} In conclusion{{</ ste >}}, the concept of decibel (dB) is just a way that allows engineers to express large numbers or values in a more defined and efficient way in order to reduce cumbersomeness or complexity.

So in power,

{{< ste >}} No Loss or Gain {{</ ste >}} (of power)
<br>

$dB_{m} = 10\log_{10}{(1)} = 0dB_{m}$

{{< ste >}} Loss {{</ ste >}} (of power)
<br>

$dB_{m} = 10\log_{10}{(0.5)} = -3dB_{m}$

$dB_{m} = 10\log_{10}{(0.25)} = -6dB_{m}$

{{< ste >}} Gain {{</ ste >}} (of power)
<br>

$dB_{m} = 10\log_{10}{(2)} = +3dB_{m}$

$dB_{m} = 10\log_{10}{(4)} = +6dB_{m}$

and in voltage,

{{< ste >}} No Loss or Gain {{</ ste >}} (of voltage)
<br>

$dB_{v} = 20\log_{10}{(1)} = 0dB_{v}$

{{< ste >}} Loss {{</ ste >}} (of voltage)
<br>

$dB_{v} = 20\log_{10}{(0.5)} = -6dB_{v}$

$dB_{v} = 20\log_{10}{(0.25)} = -12dB_{v}$

{{< ste >}} Gain {{</ ste >}} (of voltage)
<br>

$dB_{v} = 20\log_{10}{(2)} = +6dB_{v}$

$dB_{v} = 20\log_{10}{(4)} = +12dB_{v}$
