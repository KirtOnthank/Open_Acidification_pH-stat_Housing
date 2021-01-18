# TankController-Housing

The [Tank Controller](https://github.com/Open-Acidification/TankController) project utilizes a half-shield attached to an Arduino Mega. This repo holds the housing to hold all the components in a splash resistant container.

## Software Requirements

1. [FreeCAD](https://freecadweb.org/) - Using version 0.18, this 3D parametric modeler was used to created the housing.

## Viewing and Editing the Housing

1. Clone this repo to your local computer.
1. Open FreeCAD.
1. Using the menu `File` -> `Open`.
    * Navigate to your local repo location.
    * You may open any of the `*.FCStd` files.
    * The Skirt CAD file is missing, see #3.
1. View the model.

## Meshes

The mesh files generated from the CAD files have been saved in a folder called `meshes`. These files may be used to 3D print the housing.

## Related Projects

* Server - [Open_Acidification_Server](https://github.com/Open-Acidification/Open_Acidification_Server) allows for multiple tanks to be managed from one central location.
* Arduino Code - [TankController](https://github.com/Open-Acidification/TankController) forms the brain of the device.
* PCB - [TankController-KiCad](https://github.com/Open-Acidification/TankController-KiCad) holds the specifications for the PCB of the Arduino Half-Shield which connects various sensors to the Arduino.
* Case - __This repo__ is a 3d printed case for the tank controller.
