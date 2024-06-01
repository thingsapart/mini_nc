# MiniNC
The V0 of CNC machines - small envelope with 200x150x70mm (8x6x2.75") work area, aims to cut alu well (enough)

# MiniNC - What is it?
A true small _Desktop CNC_ machine that can be used inside an apartment in a pinch but can still cut softer metals. One that does not require a full shop due to space, mess and noise and does not break the bank.

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
