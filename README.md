# RoadCraft Final Project v1.0

A clean Fabric 1.21.1 project intended to produce a real RoadCraft `.jar`.

Integrated systems:
- modular vehicle parts
- engine
- battery
- fuel tank
- radiator
- four wheels
- mirrors
- fuel consumption
- temperature
- engine health
- start/stop logic
- hood state
- steering
- speed and braking prototype

Important:
This archive is the source/build project. It is not a compiled `.jar` itself.
A real mod JAR must be produced by Fabric Loom with the required Minecraft/Fabric dependencies.

## Cloud build from a phone

This project includes `.github/workflows/build.yml`. Upload the project contents to a GitHub repository, then open **Actions → Build RoadCraft Mod → Run workflow**. When the workflow finishes, download the **RoadCraft-mod** artifact. The JAR inside `build/libs/` is the file to place in your Minecraft `mods` folder.

## Damage system

The vehicle now has an independent `VehicleDamageSystem` with `HEALTHY`, `DAMAGED`, `CRITICAL`, and `DESTROYED` states. Damage can be applied by zone (`FRONT`, `REAR`, `LEFT`, `RIGHT`, `ROOF`, `UNDERBODY`, `MECHANICAL`) and repaired per part. Critical mechanical damage prevents engine start.
