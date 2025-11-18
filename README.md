# 3 Axis CNC Milling Machine
Design and construction of a custom 3-axis CNC milling machine, including CAD models, drawings, circuit diagrams, and associated software. The build was completed over the summer of 2024 in approximately 2.5 months.

# 1. CAD Model & Final Assembly
## 1.1 CAD Model
![Render of the CAD model](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/cad_cnc_router_iso_wm.png)
## 1.2 Final Assembly
![Image of the final assembly](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/cnc_full_setup.jpg)

# 2. Example Drawing & Circuit Diagram
## 2.1 Example Drawing of Right Side Gantry Support
Drawings were created for all non-standard components, including the full gantry assembly and all custom adapters.
![Technical drawing of the right side gantry support](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/right_side_gantry_support.png)
## 2.2 Circuit Diagram
General outline for referencing all wiring, signals, power and grounding for the machine.
![Circuit diagram](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/cnc_circuit_diagram.png)
## 2.3 Wiring
Annotated electrical as it sits inside of the electrical enclosure.
![Annotated image of the wiring inside the electronics enclosure](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/wiring_annotated.png)

# 3. Bill of Materials
Standard hardware is not listed individually. Non-standard parts were machined primarily from 1/4" and 3/8" aluminum plate as shown in [section 2.1](#21-example-drawing-of-right-side-gantry-support).
Additional materials:
- Spoilboard: 3/4" MDF
- Electronics enclosure: 1/2" Sande plywood
- Frame: 3030 T-slot aluminum extrusion

# 4. Tools & Software
## 4.1 Tools Used in Manufacturing
- Drill press
  - HSS bits used with WD-40 as a cutting fluid for aluminum
- Portable table saw
  - Fine-tooth carbide-tipped blade used with WD-40 as a cutting fluid for aluminum
- Belt sander
- Bench grinder
- Tap and die set
- Various handheld tools
  - Cordless drill/driver, angle grinder, screwdrivers, allen wrenches, clamps, etc.'
## 4.2 Software Used in Manufacturing
- Autodesk Fusion
  - For all CAD models/drawings
- Google Sheets
  - For budget tracking
## 4.3 Software Used in CNC Mill
- Autodesk Fusion
  - For CAM and generating toolpaths
- Universal G-Code Sender (Laptop)
  - For outputting G-code to Arduino Uno
- GRBL (Arduino Uno)
  - For interpreting G-code to stepper and spindle movement

# 5. Various Specifications
Here are some common metrics used to measure CNC machines for my final assembly:
- Cutting area: ~14" x 7.5" x 4"
  - 105 in<sup>2</sup>, 420 in<sup>3</sup>
- Max feedrate: 2,540 mm/min or 100 ipm
- Max acceleration: 254 mm/s<sup>2</sup> or 10 in/s<sup>2</sup>
- Resolution: 2 &mu;m at 1/16 microstep
- Spindle speed: 0-11,400 rpm
- Capable of plastic, wood, or aluminum milling

# 6. Project Showcase
## 6.1 Dragon Relief
[Credit to @stlfilesfree on cults3d.com for the 3D model!](https://cults3d.com/:19242)
![Image of a dragon relief made with the CNC mill](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/dragon_relief.jpg)
