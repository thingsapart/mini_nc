# MiniNC
The V0 of CNC machines - small envelope with 200x150x70mm (8x6x2.75") work area, aims to cut alu well (enough)

# MiniNC - What is it?
A true small _Desktop CNC_ machine that can be used inside an apartment in a pinch but can still cut softer metals. One that does not require a full shop due to space, mess and noise and does not break the bank.

![MiniNC enclosed](/docs/MiniNC_enclosed.jpg)

## ALPHA
The machine is past the main design phase and a prototype has been built and is about to get tested. But that does not mean everything is finalized.

## Requirements
* Cuts aluminium well.
* Cost-efficient.
* Space-efficient.
* As quiet as possible.
* Not too messy.

## Inspiration/Credits
This design was influenced by the [Milk Cr8](https://www.milkcr8cnc.com) ([GH](https://github.com/Makers-On-Tap/milkcr8-cnc)) CNC's use of plywood as a stiff box structure to enclose and stiffen the machine at the same time. The idea was to use the wooden structure and combine it with aluminium extrusions to simplify the build while retaining some superior dampening over just an alu extrusion structure.

## Features
* Cuts aluminium well =>
   * Rigid (enough) => smaller size, slower feeds, single flute, smaller end mills,
   * As it won’t be the stiffest machine, make it well-dampened => not fully made of alu, use steel, epoxy granite and wood to dampen some of the vibrations,
   * Smaller, low-powered spindles 100-500W,
   * chip-evacuation system => CPAP or chip fan,
   * cooling via misting and air blast.
* Cost-efficient =>
   * Standard components => MGN12/MGN9 rails, small 100-500W spindles, 20 series extrusions for some of the structure,
   * smaller, lower-cost spindles,
   * smaller size.
* Space-efficient =>
   * gantry design => high space-efficiency, can be reasonably rigid in this smaller envelope
   * Smaller size to cut smaller parts fitting target use-cases,
* Beginner-Friendly =>
   * XYZ probe + tool setter + surface meshing,
   * community presets and forums,
   * custom interface for Duet RRF (much later),
      * source  + G-Code + Instructions packages like Coast Runner
      * Integrated forums,
      * g-code visualizer and simulated pre-runner including stock dimensions.
* As quiet as possible =>
   * fully enclosed and ideally tightly sealed,
   * interior/exterior sound insulation (?) => layer of foam + outer layer of ACM panels?,
   * no compressor,
   * BLDC spindles with reduced vibrations.
* Not too messy =>
   * fully enclosed (!),
   * dust extraction => CPAP or roborock fan,
   * misting but no flood cooling.

## Who is it for?
* Makers and 3D printer enthusiasts but really anyone without a full (metal-working) shop and/or space for a larger machine.
* Anyone without the space for one of the larger machines.

## Stiffness

The current wooden frame seems decently stiff at roughly 1N/&micro;m in Y at the spindle collet even with 3D printed X/Y plates - needs more testing though but seems like a good start.

Some general numbers I've found for comparison:
* [Siecni 12x30 Longmill MK2 ~ 0.07M/&micro;m X and 0.05N/&micro;m Y](https://sienci.com/wp-content/uploads/2022/09/Stiffness-Rating-with-Commentary.pdf),
* [MPCNC ~ 0.1-0.2N/&micro;m](https://forum.v1e.com/t/deflection-measurement/37968/34),
* [burly but _large_ CNC build ~ 1-3N/&micro;m](https://www.mycncuk.com/threads/7155-stiffness-measurements-cnc-mk3),
* I've seen 20N/&micro;m recommended for cutting alu very well,
* Milling Machines supposedly ~ 20-30N/&micro;m,
* professional cast-iron or epoxy granite VMCs are on the other 70-150N/&micro;m.
* (LET ME KNOW IF YOU HAVE OTHER/MORE DATA OR CORRECTIONS, I'D LOVE TO ADD IT)
  
NB: [Load cell tool design to apply a measured/specific force to the spindle](https://www.printables.com/model/473947-xy-forcing-mechanism-for-cnc-router-diagnostics).
NB: [Some numbers and suggested values for stiffness](https://www.cnczone.com/forums/uncategorised-metalworking-machines/378098-cnc-2.html?s=0ac995351d1eec0bfeb15a12f1eecd70) - 25kgf ~> <0.1mm deflection seems like a decent goal (2.5N/&micro;m).

Rough design for phase-2 buildout using a lasercut steel structure to increase stiffness if needed. 
![Steel structure under enclosure panels](/docs/MiniNC_steel.jpg)

## Use-Cases
* Small aluminium parts:
   * high-speed 3D printer motion system reinforcements and brackets,
   * higher-temp 3D printer component,
   * toolhead components.
* Makers:
   * Tools, …

## Optional Features/TODOs
* low-profile modular vise system,
* internal camera,
* laser Module Support,
* internal LED lighting + toolhead lighting,
* 4th axis?
