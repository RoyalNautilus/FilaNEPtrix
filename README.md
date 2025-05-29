# FilaNEPtrix
This is a mod inspired by several projects to create a toolhead filament cutter for Neptune 4 and 4 Pro printers. This allows reliable and consistent multi-material and multicolor printing when paired with a MMU such as the [Box Turtle](https://github.com/ArmoredTurtle/BoxTurtle), [ERCF](https://github.com/Enraged-Rabbit-Community/ERCF_v2), [Pico MMU](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU), or others.

  * Please note that this is an *extremely* early release. Further optimization, iteration, and testing will be done over the next few weeks to hopefully turn this project into a stable and relatively hassle-free upgrade. 
  * If you have questions, would like to make suggestions, or notice any glaring issues to be resolved, please open an issue and let me know so I can get to work on it!
  
### Compatibility Note:
This was originally designed as a personal upgrade for my Neptune 4 Pro. While other models of Neptune 4 (or even Neptune 3) may function, alignment, tolerances, and features may differ just enough that the cutter may not operate as intended. Use at your own risk if you decide to try this on one of the other models!

## Gallery
*coming soon™*

## Recommended (and required) Paired Upgrades
### Toolhead Shroud - *MANDATORY*
Though there are many variants of the [OrzOrzOrz v5/6 Fan Shroud](https://www.printables.com/model/711424-elegoo-neptune-4promaxplus-fan-shroud-v5 "Printables"), the [SilencedFrost version](https://www.printables.com/model/905447-sf-3x5015-neptune-4-fan-mod-shroud-optimized-enhan "Printables") is (IMO) the ultimate version out so far. With compatibility with Beacon probes, many options for ADXL mounts, and the top-mounted bowden coupler options, not to mention the *stellar* cooling performance, there's really no way to go wrong with the upgrade.

To address the "Mandatory" tag, this is to say that FilaNEPtrix can only be installed on a shroud with heatset inserts or a similar mounting solution positioned in the same places on the top of the toolhead as SilencedFrost's. This is typically a pair of M3x5mm heat-set inserts located 5.5mm behind the *center* of the filament inlet, spaced 55mm apart. This placement allows full operation of the filament inlet, extruder manual release trigger, and exposed gear on the top, as well as leaving room for cooling fans.

### X-Axis

With the cutting motion applying great forces to the x-axis motion system, several X-axis upgrades will greatly help to prevent belt skipping. 
 * First, [layer.shifted (@Lamarc)'s X-Axis Double Shear Mod](https://www.printables.com/model/1222791-neptune-44pro-x-axis-double-shear-motor-upgrade "Printables").
   * This mod helps attach the X-axis motor pulley on both ends, allowing more tension without damage and preventing twisting from happening. (Side-benefit, *much* greater input shaper acceleration values in my testing!)
   * This will also allow for 3rd-party stepper motor upgrades, unlocking potential for much more reliable performance in the cutting action.

## BOM
*coming soon™*

## Recommended Print Settings
*coming soon™*

## Assembly
*coming soon™*

## Software Config & Tuning
*coming soon™*