# RoadCraft v1.1 — High Detail Curved Model

The project now includes a first smooth, rounded SUV body mesh prototype.

The model is deliberately not a Minecraft cube model:
- rounded body profile
- curved cabin
- separate wheel geometry
- material-slot planning
- separate-part architecture for future detachable components

Next integration work:
1. connect the mesh to the Fabric entity renderer
2. split hood/doors/mirrors into independently rendered components
3. add textures and materials
4. add animations for wheels, steering, hood and doors


## v1.2 additions
- renderer-oriented vehicle state
- wheel rotation state
- steering animation state
- smooth hood opening progress
- separate mirror states
- model-part animation metadata


## v1.3 additions
- entity-facing vehicle state
- driver/occupancy state
- mechanical-to-render bridge
- vehicle entity integration metadata
- mountable/driver-control feature definitions


## v1.4 additions
- vehicle control input state
- throttle, brake and steering
- handbrake state
- driver/passenger door interaction state
- hood and trunk interaction state
- dashboard data state
- control mapping metadata
