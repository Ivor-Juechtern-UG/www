---
title: Energy Flexibility in Production Planning
draft: true
authors: 
---

## The idea

A factory plans production against orders, machines and people, but rarely against energy. Kjerner plans production and capacity, Oliva manages energy behind the meter, and Ivor Jüchtern UG automates the machines in between. Combined, energy becomes one more resource in the plan: what runs when depends also on the price of electricity, the sun on the roof and the limits of the grid connection.

## Kjerner

[Kjerner](https://www.kjerner.nl) in Delft builds custom ERP, MES and planning software on its own model-driven [Alan Platform](https://www.kjerner.nl/alan-platform/), developed since 2011. One application model holds the database, the business logic and the user interface, and the screens are generated from it. Rick van der Arend is its CEO.

- **[Alan Planning](https://www.kjerner.nl/alan-planning/):** capacity planning and production planning (advanced planning and scheduling) for people, materials and machines, in slots from 10 minutes to a week, with dependencies between tasks and business rules.
- **Integrations:** ERP, accounting, webshops and shop-floor systems.
- **Customers:** food and dairy above all (Visser Kaas), and production companies, among them [Hydro](https://www.kjerner.nl/cases/hydro/) (aluminium), where a new MES is credited with 30% more labour productivity and 98% of orders on time.

Energy appears nowhere in Alan Planning. That is the gap this cooperation fills.

## Oliva

Oliva Energy runs energy management behind the meter for factories and industrial sites in the Netherlands. A controller on each site reads the meters and steers the energy assets: solar inverters, batteries, and loads such as heat pumps and charging points.

- **What it knows:** what each asset is doing now, and from settings and data, what it will do days ahead.
- **What it steers:** curtailing solar, charging batteries from the sun or the grid, staying within the limits of the grid connection.
- **What it adds here:** an energy forecast and energy limits the production plan can take into account, and the steering to follow the plan once it is set.

## Ivor Jüchtern UG

Ivor Jüchtern UG does industrial automation: the controllers that connect a plan to the machines. Its work at De Hoop Pekso became a [Phoenix Contact use case](https://www.plcnext-community.net/news/industrial-energy-management-ivor-juechtern/) for industrial energy management on PLCnext controllers.

- **What it adds here:** the machine side. Which machines can shift, pause or slow down, how long a switch takes, and how to do it safely and in a way that is gentle on the grid.

## Why combine them

Energy flexibility is worth most where the plan is made, not after it. A planner who knows the energy forecast can put the heavy jobs where the power is cheap, green or plentiful, before anyone has to curtail.

- **Prices:** electricity prices change by the hour. Energy-heavy jobs move to the cheap hours.
- **Solar:** production that follows the sun uses more of the factory's own power and exports less.
- **Grid limits:** a plan that knows the connection's limit doesn't exceed it, and makes room for growth without a bigger connection.
- **Feedback:** the energy actually used flows back into the plan, so the next plan is better.

Neither side can do this alone: Kjerner doesn't see energy, and Oliva doesn't see orders.

## Open questions and next steps

- Which Kjerner customers have energy-heavy production and a flexible plan? Aluminium (Hydro) is the obvious first candidate.
- Which interface between Alan Planning and Oliva: an energy forecast in, a plan out, how often?
- A first pilot site, possibly De Hoop Pekso.

## Sources

- [Kjerner](https://www.kjerner.nl)
- [Alan Planning](https://www.kjerner.nl/alan-planning/)
- [Alan Platform](https://www.kjerner.nl/alan-platform/)
- [Hydro case](https://www.kjerner.nl/cases/hydro/)
- [Phoenix Contact use case](https://www.plcnext-community.net/news/industrial-energy-management-ivor-juechtern/)
