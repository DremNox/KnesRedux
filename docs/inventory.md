# Knes port inventory

Total KSP1 part configs: **214**

## Families

- ATV: 16
- Core: 29
- Launcher: 100
- LiftingsBodies: 4
- MultiRoleKapsule: 21
- Spacecraft: 23
- SpacePlane: 21

## Most-used KSP1 modules

- ModulePartVariants: 97
- ModuleColorChanger: 80
- ModuleCargoPart: 80
- ModuleEnginesFX: 49
- ModuleJettison: 40
- ModuleSurfaceFX: 39
- FXModuleThrottleEffects: 39
- ModuleDataTransmitter: 29
- ModuleDecouple: 27
- ModuleReactionWheel: 27
- ModuleGimbal: 27
- ModuleCommand: 25
- ModuleSAS: 22
- ModuleScienceExperiment: 19
- ModuleScienceContainer: 19
- ModuleRCSFX: 16
- ModuleToggleCrossfeed: 15
- ModuleLiftingSurface: 13
- ModuleDragModifier: 12
- ModuleDeployableSolarPanel: 12
- ModuleInventoryPart: 11
- ModuleEngines: 10
- ModuleCargoBay: 9
- ModuleControlSurface: 9
- ModuleKerbNetAccess: 8
- ModuleAnimateGeneric: 7
- ModuleProceduralFairing: 7

## Resources

- ElectricCharge: 92
- MonoPropellant: 40
- LiquidFuel: 36
- Oxidizer: 36
- SolidFuel: 25
- Crystal: 5
- Ablator: 4

## Optional KSP1 compatibility patches

These are not required for the initial Redux port and will be handled separately if useful:

- TweakScale
- Waterfall
- MechJebCore
- KIS
- CryoTanks
- Pathfinder
- ODFC

## Porting note

KSP2 Redux's current SDK includes a KSP1 Mod Converter capable of generating KSP2 prefabs, part JSON, resources, localization and plume variants from KSP1 mod folders. The port will use that converter as the baseline, with manual fixes for unsupported/part-specific modules.
