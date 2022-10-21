# 3D printing the parts
This file details the list of 3D printed parts required to build the controller and gives information about the main printing parameters used. All parts were printed using an [Ultimaker 3](http://ultimaker.com) printer. The print direction given was set as the positive Z direction in the printer. So if the direction **+Y** is given, the positive Y direction from the .stl file was set as positive Z in the slicing software.

Parts usually require a small amount of post finishing. A kit of fine grit files like [this](https://www.mcmaster.com/8174A42/) is very useful for that purpose.

## List of files

1. [Casing_Top](./_static/download/stl/Top.zip)
2. [Casing_Bottom](./_static/download/stl/Bottom.zip)
3. [Switch_Body](./_static/download/stl/Switch_Body.zip)
4. [Shutter_Cap](./_static/download/stl/Shutter_Cap.zip)
5. [Shutter_Blade](./_static/download/stl/Shutter_Blade.zip)
6. [DPad_Support](./_static/download/stl/DPad_Support.zip)
7. [Dir_Button](./_static/download/stl/Dir_Button.zip)
8. [Button_Cap](./_static/download/stl/Button_Cap.zip)
9. [DPad_Cover](./_static/download/stl/DPad_Cover.zip)
10. [Button_Cover](./_static/download/stl/Buttons_Cover.zip)
11. [Interface_Casing_Top](./_static/download/stl/Interface_Top.zip)
12. [Interface_Casing_Bottom](./_static/download/stl/Interface_Bottom.zip)

## Casing top
[Top.zip](./_static/download/stl/Top.zip) | <img src="./_static/3dprint/Casing_Top.png" alt="Casing Top" width="200"/>
------|--------
Weight|53.8 g
Volume|46.4 cm<sup>3</sup>
Bounding box | 155.4 x 43.5 x 94.9 mm
Qty | 1
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 40%
Nozzle 1 size | 0.8 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.15 mm
Print direction | +Y
Comments

## Casing bottom
[Bottom.zip](./_static/download/stl/Bottom.zip) | <img src="./_static/3dprint/Casing_Bottom.png" alt="Casing Bottom" width="200"/>
------|--------
Weight|107.9 g
Volume|87.0 cm<sup>3</sup>
Bounding box | 169.8 x 58.8 x 95.1 mm
Qty | 1
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 40%
Nozzle 1 size | 0.8 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.15 mm
Print direction | -Y
Comments

## Switch body
[Switch_Body.zip](./_static/download/stl/Switch_Body.zip) | <img src="./_static/3dprint/Switch_Body.png" alt="Switch Body" width="200"/>
------|--------
Weight|3.6 g
Volume|2.9 cm<sup>3</sup>
Bounding box | 16.0 x 18.5  x 16.0 mm
Qty | 8
Material 1 | PLA
Material 2 (support) | same as material 1
Material 1 density | 100%
Material 2 density | 40%
Nozzle 1 size | 0.25 mm
Nozzle 2 size | N/A
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | N/A
Bed temperature | 50 °C
Layer height | 0.1 mm
Print direction | +Y
Comments|

## Shutter cap
[Shutter_Cap.zip](./_static/download/stl/Shutter_cap.zip) | <img src="./_static/3dprint/Shutter_Cap.png" alt="Shutter Cap" width="200"/>
------|--------
Weight|0.19 g
Volume|0.15 cm<sup>3</sup>
Bounding box | 7.5 x 6.3  x 7.5 mm
Qty | 8
Material 1 | PLA
Material 2 (support) | -
Material 1 density | 100%
Material 2 density | -
Nozzle 1 size | 0.25 mm
Nozzle 2 size | -
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | -
Bed temperature | 50 °C
Layer height | 0.1 mm
Print direction | -Y
Comments|

## Shutter blade
[Shutter_Blade.zip](./_static/download/stl/Shutter_Blade.zip) | <img src="./_static/3dprint/Shutter_Blade.png" alt="Shutter Blade" width="200"/>
------|--------
Weight|0.014 g
Volume|0.0012 cm<sup>3</sup>
Bounding box | 0.5 x 11.7 x 2.2 mm
Qty | 8
Material 1 | PLA
Material 2 (support) | -
Material 1 density | 100%
Material 2 density | -
Nozzle 1 size | 0.25 mm
Nozzle 2 size | -
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | -
Bed temperature | 50 °C
Layer height | 0.06 mm
Print direction | +X
Comments | This works better if printed with dark (ideally black) material. This part takes very little material, prints fast and warps easily, so print lots of it and keep the best ones.

## Direction pad support
[DPad_Support.zip](./_static/download/stl/DPad_Support.zip) | <img src="./_static/3dprint/DPad_Support.png" alt="Directional Pad Support" width="200"/>
------|--------
Weight|14.6 g
Volume|11.8 cm<sup>3</sup>
Bounding box | 46.9 x 13.2  x 48.5 mm
Qty | 14
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.4 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.1 mm
Print direction | +Y
Comments | Some post finishing of guiding slots may be required to get smooth button motion. Use of fine grit small detailing files or sanding paper recommended. This part can be printed at lower density than 100%, but make sure that walls are thick enough. Cura's default with 0.4 mm nozzle is 1 mm. At least double that.

## Button support
[Buttons_Support.zip](./_static/download/stl/Buttons_Support.zip) | <img src="./_static/3dprint/Button_Support.png" alt="Directional Pad Support" width="200"/>
------|--------
Weight|16.0  g
Volume|12.9 cm<sup>3</sup>
Bounding box | 46.9 x 13.2  x 48.5 mm
Qty | 1
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.4 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.1 mm
Print direction | +Y
Comments | Some post finishing of guiding slots may be required to get smooth button motion. Use of fine grit small detailing files or sanding paper recommended. This part can be printed at lower density than 100%, but make sure that walls are thick enough. Cura's default with 0.4 mm nozzle is 1 mm. At least double that.

## Direction button
[Dir_Button.zip](./_static/download/stl/Dir_Button.zip) | <img src="./_static/3dprint/Direction_Button.png" alt="Direction_Button" width="200"/>
------|--------
Weight|1.6 g
Volume|1.3 cm<sup>3</sup>
Bounding box | 14.0 x 12.0  x 13.0 mm
Qty | 4
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.25 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.06 mm
Print direction | +Y
Comments | Precision of dimensions and finish quality are very important for this part. Fill percentage does not really matter, but this is a very small part, so material quantity and print time are both are not a problem.

## Round button
[Button_Cap.zip](./_static/download/stl/Button_Cap.zip) | <img src="./_static/3dprint/Round_Button.png" alt="Round_Button" width="200"/>
------|--------
Weight|1.19 g
Volume|0.96 cm<sup>3</sup>
Bounding box | 10.65 x 13.0  x 13.5 mm
Qty | 4
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.25 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.06 mm
Print direction | +Y
Comments | Precision of dimensions and finish quality are very important for this part. Fill percentage does not really matter, but this is a very small part, so material quantity and print time are both are not a problem.

## Direction pad cover
[DPad_Cover.zip](./_static/download/stl/DPad_Cover.zip) | <img src="./_static/3dprint/DPad_Cover.png" alt="DPad_Cover" width="200"/>
------|--------
Weight|1.19 g
Volume|0.96 cm<sup>3</sup>
Bounding box | 10.65 x 13.0  x 13.5 mm
Qty | 4
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.25 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.06 mm
Print direction | +Y
Comments |

## Button_Cover
[Button_Cover.zip](./_static/download/stl/Button_Cover.zip) | <img src="./_static/3dprint/Button_Cover.png" alt="Button_Cover" width="200"/>
------|--------
Weight|1.19 g
Volume|0.96 cm<sup>3</sup>
Bounding box | 10.65 x 13.0  x 13.5 mm
Qty | 4
Material 1 | PLA
Material 2 (support) | PVA
Material 1 density | 100%
Material 2 density | 30%
Nozzle 1 size | 0.25 mm
Nozzle 2 size | 0.4 mm
Nozzle 1 temperature | 205 °C
Nozzle 2 temperature | 230 °C
Bed temperature | 50 °C
Layer height | 0.06 mm
Print direction | +Y
Comments | This part uses 2 colors printing for the markings. You need to load 5 stl files in your slicer, assign each to the appropriate material, then merge them into one piece
