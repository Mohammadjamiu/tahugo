---
title: "What Is a Signal and its Different Types In Electronics And Communications?"
postdate: November 30, 2021
image: "/images/signals_6 (2).jpg"
description: "A signal is a function of an independent variable (e.g. of space, time, or density) that carries information representing a physical phenomenon. So anything that carries information is considered a signal"
alt: ""
weight: "16"
author: Mohammad Abdul
categorylink: /categories/signals-and-system
categories: ["Signals and System"]
type: posts
mathjax: true
wordcount: false
draft: false
---

## what is a signal?

A signal is a function of an independent variable (e.g. of space, time, or density) that carries information representing a physical phenomenon.

So anything that carries information is considered a signal e.g.

1. The temperature of a room,
2. Voltage and current in an electronic circuit
3. Digital images, video, or audio
4. Sounds or speeches etc.
5. Position, speed, acceleration, or velocity of an object
6. A stock market index
7. The flow rate of fluid

<br>

## Types of signals

In communications or digital electronics engineering in general, signals are classified into the following

<ul class="ul-in-post">

<li>
Continuous-time signal and discrete-time signal
</li>
<li>
Deterministic signal and non-deterministic (or random) signal
</li>
<li>
Periodic and non-periodic signal
</li>
<li>
Even and odd signal
</li>
<li>
Energy and power signal
</li>
<li>
Casual, anti-casual and non-casual signal
</li>

</ul>

## Continuous time signal and discrete time signal

{{< ste >}}Continuous-time signal (CTS){{</ ste >}} is a signal that is define for all time (t). example of a continuous time signal is a sine function.

<img src="/images/signals_8 (2).jpg" alt="Continuous time signals">

{{< ste >}}Discrete-time signal (DTS){{</ ste >}} is a signal that are defined only at discrete time (n).
It is same as that of continuous but instead of having a continuous value, it has value in form of height which are only present at discrete time e.g. (1, 2, 3 ..) But not 1.5, 2.5 which are fractions.

<img src="/images/signals_7 (2).jpg" alt="discrete time signals">

## Deterministic signal and non-deterministic (or random) signal

{{< ste >}}Deterministic signal{{</ ste >}} is a signal that has no uncertainty with respect to its value at any instant of time. This is quite similar to sin since at any instant of time (t) there is corresponding or defined value for the signal $x(t)$.

<img src="/images/signal_3.jpg" alt="Deterministic signals">

{{< ste >}}Non-deterministic signal{{</ ste >}} is referred to as a random signal and it is a signal that has uncertainty with respect to its value at any instant of time. It is defined in probabilistic terms as there is no define value.

<img src="/images/signals_3 (2).jpg" alt="non-deterministic (or random) signals">

## Periodic and non-periodic signal

{{< ste >}}Periodic signal{{</ ste >}} is a signal that repeat itself at regular interval of time (t).
It is defined by $x(t) = x(t + T)$ where $T$ is the period.

<p>{{< ste >}}Non-periodic signal{{</ ste >}} is also called aperiodic signal and it is a signal that don’t repeat itself at regular interval of time (t).
It is defined by $x(t) &ne; x(t + T)$.</p>

<img src="/images/signals_2 (2).jpg" alt="Periodic and non-periodic signals">

## Even and odd signal

<img src="/images/signals_6 (2).jpg" alt="Even and odd signals">

{{< ste >}}Even signal{{</ ste>}} is a signal that is symmetric about the value or y or vertical axis and ii is defined by this condition x(t) = x(-t).

1. Example of even signal.

   Q1. Verify if $x(t) = t^{2} + 1$ is an even function.

   Answer:

   $x(t) = t^{2} + 1$

   replace t with (-t)

   $x(-t) = (-t)^{2} + 1$ = $x(-t) = t^{2} + 1$

   So if the both equations are rewritten then we can see that $t^{2} + 1 = t^{2} + 1$

   $\begin{cases} x(t) = t^{2} + 1 &\\& x(-t) = t^{2} + 1\end{cases}$

   Therefore, $x(t) = x(-t)$ which means this is an even function.

{{< ste >}}Odd signal{{</ ste >}} is a signal that is symmetric around the origin and it is defined by the condition $x(t) = -x(-t)$

2. Example of an odd signal.

   Q1. Verify if $x(t) = 2t$ an odd function.

   Answer:

   $x(t) = 2t$

   replace t with (-t)

   $x(-t) = 2(-t) = -2t$

   make both equation to have $2t$ by dividing $x(-t) = -2t$ by $-1$

   hence, $-x(-t) = 2t$. So if the both equations are rewritten then we can see that $2t = 2t$

   $\begin{cases} x(t) = 2t &\\& -x(-t) = 2t\end{cases} $

   Therefore, $x(t) = -x(-t)$ which means this is an odd function

## Energy and power signals

{{< ste >}}A power signal{{</ ste >}} is a signal with finite power. It can be calculated using;

$$P = \lim_{ T\rightarrow ∞}\frac{1}{2T} \int_{-T}^{T} |x(t)|^{2} dt$$

{{< ste >}}An energy signal{{</ ste >}} is a signal with finite energy. It can be calculated using;

$$E =\lim_{T \rightarrow ∞ } = \int_{-T}^{T} |x(t)|^{2} dt= \int_{-∞}^{∞} |x(t)|^{2} dt$$

You can read more on what <a class="links-to-article" href="/signals-and-system/how-do-you-solve-energy-and-power-signals-problem/"> power and energy signals </a> are with some shortcut to help you know if a signal is a power or an energy signal.

## Casual, Anti-casual and Non-casual signal

{{< ste >}}Casual signal{{</ ste >}} is a signal that has zero value for all negative time.

{{< ste >}}Anti-casual signal{{</ ste >}} is the opposite of casual as it has zero value for all positive time.

{{< ste >}}Non casual signal{{</ ste >}} has no zero values in both the positive and negative time.

<img src="/images/signals_9.jpg" alt="non-deterministic (or random) signals">
