# GrblFor5AxisFoamCutterAndMill
GRBL Interpreter for Arduino MEGA and Ramps 1.4/1.5 and 4/5 Axis Machine (FoamCutter and/or Mill)

This GRBL-Interpreter is a marginal adapted Version of the grbl-Mega-5X (v1.1) (https://github.com/fra589/grbl-Mega-5X; fra589; Gauthier Brière) to fit the needs of my combined WireCutter and Mill machine (will be available at GitHub).

There are 2 new Codes to switch between HotWire-Mode (4 Axis) and Mill (5 Axis).
- M88 ... HotWire
- M89 ... Mill

I changed the following files:
- main.c
- defaults.h
- config.h
- gcode.c/h -> Codes M88 and M89
- system.h
- report.c/h
- motion_control.c




