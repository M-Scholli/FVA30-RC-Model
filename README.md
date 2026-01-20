# FVA30-RC-Model
A 3D printable RC Model of the FVA30 with a Wingspan of around 2m to 2.8m

## To do

### Aerofreeze
- [ ] select scale and wingspan
- [ ] increase Wing Area to decrease Wingloading
- [ ] select Motor and Propeller
- [ ] select Profile for Wing
- [ ] select Profile for V-Tail
- [ ] select V-shape

### 3D Model
- [ ] Wing
  - [ ] wing outline  
  - [ ] wingtips
  - [ ] flapperons
  - [ ] add wing rofile
  - [ ] fuselage transition
- [ ] Fuselage
  - [ ] cross sections
  - [ ] canopy
  - [ ] canopy attachment
  - [ ] wing cutout
  - [ ] landing gear
  - [ ] servo position
  - [ ] tail wheel
  - [ ] cooling for ESC and Battery
- [ ] V-Tail
  - [ ] outline
  - [ ] shape
  - [ ] profile
  - [ ] fuselage transition
  - [ ] motor mounts
  - [ ] rudder cutouts 


## Tools

### Blender

The design is made with the 3dPPlaneDesign - 3D Printed Model Plane Non-destructive Blender Design Tools from nerk987
https://github.com/nerk987/3dpPlaneDesign 

## Design Considerations

### Finding the rigth model scale

| Scale | Wingspan [m] | Wing Area [dm²] | Root Chord [mm] | Ø Motor [mm] | Ø Prop [mm] | Ø Prop [inch] |
| ----- | ------------ | --------------- | --------------- | ------------ | ----------- | ------------- |
| 1:9   | 1.9          | 16.2            | 105             | 25           | 155         | 6 - 6.5       |
| 1:8.5 | 2            | 18.1            | 112             | 27           | 165         | 6.5           |
| 1:8   | 2.1          | 20.5            | 119             | 28.5         | 175         | 6-5 - 7       |
| 1:7.5 | 2.25         | 23.3            | 127             | 30.4         | 185         | 7 - 7-5       |
| 1:7   | 2.3          | 26.7            | 136             | 32.6         | 200         | 8             |
| 1:6.5 | 2.6          | 31              | 146             | 35           | 215         | 8.5           |
| 1:6   | 2.8          | 39              | 158             | 38           | 230         | 9             |

### Other Considerations
- Motor diameter:
  - standart outrunner BLDC sizes are 28 mm, 35 mm and 42mm.
  - for a 28 mm motor a wingspan of 2,1 m and for a 35 mm motor a wingspan of 2.6m would be nice. 
