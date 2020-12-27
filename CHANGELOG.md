# Corvus Community Fixes - Changelog

* v{VERSION}
  * <TODO>

* v1.3.6 2020-12-27
  * Add Inventory and Cargo configurations to parts for KSP1.11.

* v1.3.5
  * Fix excessive drag on Corvus Nosecone when RealChute mod is installed.
  * Add german translation.
  * Add spanish translation - thanks to *Fitiales*.

* v1.3.4
  * Revert a bug introduced in the last version for DeadlyReentry.
  * Add Snacks! storage to the Corvus Supply Module.
  * Add crossfeed toggling to the Corvus Heatshield.

* v1.3.3
  * Fix and tweak ModuleManager patch for DeadlyReentry.

* v1.3.2
  * Nerf the Corvus Supply Pod RCS fuel cell - 1 unit of RCS now generates 100 units of electricity instead of 1000.
  * Nerf the Corvus Nosecone RCS capacity - reduced from 30 to 15 units.
  * Minor tweaks to the Corvus Adapter - adjust drag and breaking force.
  * Fix the warning message emitted by the Corvus Adapter
    + The Adapter will NOT shield its contents in Stock Aero unless the Animated Decouplers mod is installed
    + Alternatively, install NEAR or FAR.
    + Or mount only physics-less parts into it.
  * Update version to reflect compatibility with KSP 1.4.1

* v1.3.1
  * Integrate the "Corvus Extras" parts.
  * Integrate (most of) Deimos Rast's tweaks and fixes.
  * A few more bits and pieces localised using the KSP default localisation strings.
  * Minor directory cleanup

  * KNOWN ISSUES:
    + The Corvus Extras 1.875m Adapter part generates an error during load (IScalarModule), but otherwise appears to function.

* v1.3.0
  * Fix version file for CKAN ::oops::!
  * Add localisation support (breaks compatibility with KSP1.2)

* v1.2.0
  * Integrate Corvus v1.1.1 mod due to changed licensing of the original mod

* v0.1
  * Initial release
  * Adds missing part modules to Corvus parts for KSP1.2
  * Rebalances heat and buoyancy
  * Fixes heatshield ablation usage
  * Adds custom Snacks! override
