---
title: Programmable Logic Controllers
draft: true
authors: 
---

In 1968, General Motors asked for a programmable controller. Before that, people had to rewire relays and timers.

## Before PLCs

Control logic was hard-wired from relays, timers and contactors in a cabinet. Every change to a production line meant rewiring it.

## The first PLC

- **The request:** in 1968, GM Hydramatic, the automatic transmission division of General Motors, asked for an electronic replacement for hard-wired relay systems, based on a white paper by its engineer Edward R. Clark.
- **The winner:** Bedford Associates of Bedford, Massachusetts, with Dick Morley. Built in 1969, it was called the 084 because it was their 84th project. To build and sell it they founded Modicon, the "Modular Digital Controller".
- **The team:** Richard Morley, Mike Greenberg, Jonas Landau, George Schwenk and Tom Boissevain.
- **The language:** ladder logic, which copies relay wiring diagrams, so that electricians could program it.
- **The hardware:** the specification asked for 16 inputs, 16 outputs and 1 kilobyte of memory, all upgradable. The prototype had 125 words of memory and was never sold; the production 084 had 1 to 4K words. It was modular and solid-state, in three parts: processor board, memory and logic solver board.
- **What came after:** the Modicon 184 in the early 1970s, later the 984 series and Quantum. Modicon now belongs to Schneider Electric.

## Who came next

- **Digital Equipment (DEC):** in June 1969 its PDP-14 was installed at GM to control a gear grinder ([source](https://hybridplc.org/wp-content/uploads/chap1_S.pdf)).
- **Allen-Bradley:** bought into 3-I and the rights to its PDQ-II controller, and acquired 3-I in late 1969. The PDQ-II was judged too complex and too large; the next attempt was the Programmable Matrix Controller ([automation.com](https://www.automation.com/article/the-dawn-of-the-programmable-logic-controller-plc), [AutomationPrimer](https://automationprimer.com/2017/03/19/birth-of-the-programmable-controller/)). The name "PLC" is said to come from Allen-Bradley, around 1971.
- **Siemens:** the Simatic S3 in 1973, its first PLC; the S5 in 1979, programmed with STEP 5 on CP/M and MS-DOS; the S7 in 1994 ([control.com](https://control.com/technical-articles/siemens-simatic-plcs-hardware-history/)).

## Languages

- **Ladder logic:** the first, from the late 1960s.
- **IEC 61131-3,** from 1993, standardised five languages: Ladder Diagram, Function Block Diagram, Structured Text (textual, based on Pascal), Instruction List (deprecated since 2013) and Sequential Function Chart. One project can mix them.
- Ladder and Function Block Diagram can often be converted into each other; Structured Text usually cannot be turned back into Ladder, because it can do more: loops, arrays, complex expressions.

## The open, Linux-based wave

Until about 2013, controllers ran closed, proprietary real-time systems, and you could load only a PLC program. Between about 2013 and 2018 came controllers that run Linux and let you run your own apps beside the PLC program: WAGO's PFC200, the Revolution Pi, Phoenix Contact's PLCnext and Opto 22's groov EPIC.

## To check before publishing

- What kind of input and output modules the 084 had: relay, solid-state, 120 V AC? Not found yet; to ask in a group of people who collect and photograph electronic components.
- General Electric, Square D and Texas Instruments in the early 1970s; Mitsubishi and Omron in Japan in the 1970s.
- The year Allen-Bradley coined the name "PLC".
- The dates of the Linux-based controllers.
