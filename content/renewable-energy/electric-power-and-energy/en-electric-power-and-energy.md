---
title: Electric Power and Energy
draft: true
authors: 
---

## Power and energy

Power is how fast energy flows. Energy is how much has flowed in total.

Power is measured in watts (W) or kilowatts (kW). Energy is power multiplied by time, so it is measured in watt-hours (Wh) or kilowatt-hours (kWh). A 2 kW kettle that runs for half an hour uses 1 kWh.

A water pipe helps: power is how many litres per second flow through it, energy is how many litres have filled the bucket.

## Active power

Active power is the part of electric power that does work: it heats the kettle, turns the pump, lights the lamp. It is measured in watts. When people say "power", they usually mean active power, and it is what the electricity bill counts, in kWh.

## Reactive power

Reactive power does no work, but it still flows. It is measured in volt-ampere reactive (var).

Think of a glass of beer. The beer is active power: it quenches the thirst. The foam is reactive power: it fills the glass, but quenches nothing. A glass with a lot of foam holds less beer.

A practical example is an electric motor, as in a pump or a compressor. To turn, it needs a magnetic field. In each cycle of the alternating current, the motor takes energy from the grid to build the field, and when the field collapses, the energy goes back to the grid. In Europe this happens 50 times a second, in both directions. Over time nothing is used, but current flows all the time.

## Why reactive power matters

The current that carries reactive power flows through the same cables and transformers as the current that does work. It heats them, takes up their capacity, and changes the voltage in the grid. So grid operators care about it, even though no one pays for it as energy.

Inverters, such as those in a PV plant, can produce or absorb reactive power on purpose. Grid operators use this to keep the voltage in range, and they can send setpoints for it to a plant.

## How the energy goes back

The current in the grid changes direction 50 times a second. While the current builds up, the motor's coil stores energy in its magnetic field, like a spring being pressed. When the current falls, the field shrinks and, like the spring letting go, pushes that energy back through the wires to the grid.

So the energy sloshes back and forth, 100 times a second, and almost none of it is used up.

## A side effect of AC

Reactive power exists only because of alternating current. With direct current, a coil's field builds up once when it is switched on, and then stays. Only because AC keeps reversing does the field build and collapse again and again.

The name fits: it comes from reactance, the way coils and capacitors react against a change in the current.

## What makes reactive power

Anything that stores energy for a moment, in one of two kinds of field:

- **A magnetic field (coils):** motors, transformers, older fluorescent lamps with ballasts, welding machines.
- **An electric field (capacitors):** capacitors, and also long underground cables.

The two kinds work against each other, so they cancel out. That is why capacitors are used to offset the reactive power of motors.

## In a factory

Besides the motors of pumps and compressors, the big sources are welding machines, induction furnaces and the lighting of halls with fluorescent tubes. Power supplies and drives add a little.

Larger factories are connected at medium voltage and own their transformer, so it counts as theirs too.

Factories often fix it locally: banks of capacitors cancel most of the reactive power on site, so it does not load the grid. Modern inverters can do the same electronically, on demand.

## Not a waste

Reactive power is not waste. The motor really needs it: without its magnetic field, it would not turn. What is wasted is the extra current it causes: it heats the cables and takes up room that active power could use.

## Apparent power: the whole glass

Apparent power is active and reactive power together: the whole glass, beer and foam. It is simply the voltage multiplied by the current.

Cables, transformers and inverters must be sized for apparent power, which is why an inverter is rated in kVA, not kW.

<table><thead><tr><th>Power</th><th>What it is</th><th>Unit</th></tr></thead><tbody><tr><td>Active</td><td>does the work, the beer</td><td>watt (W)</td></tr><tr><td>Reactive</td><td>flows back and forth, the foam</td><td>volt-ampere reactive (var)</td></tr><tr><td>Apparent</td><td>both together, the whole glass</td><td>volt-ampere (VA)</td></tr></tbody></table>
