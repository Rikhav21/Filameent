# Recycliment
## About
This is supposed to be a really affordable filament recycler. Basically it is made up of an extruder, a filament winder and puller, and a filament shredder. The filament shredder is basically a mini one based of the one by recreator 3d, because otherwise, the shredder itself would take up way more than the budget of the rest of the build, and I do not currently have the means to machine metal, although I would love to make a cnc to mill metal. I also think that it is importanat that the entire build still costs less than 280 dollars, and is a lot more afforable than other filament extruders. I hope to be able to make high quality filament, and I think that I should be able to this this using a small geared motor, rather than a large motor, so that it might be slower, but still cheaper. If you already have some basic parts like wood, I think that your should be able to buil dthe extruder and the winder for less than 200 dollars. 
## Why I made this
So for this I mainly jsut want to recyle the over 3 kg of filament waste I have I print way to much, and although it will probably not save me money right now, I also want to experiment with making different types of filaments. I saw CNC kitchen make filament from plastic spoons, and I wanted to saw what other types of filaments that I could make, maybe with wood fillings or othe rodd types of filaments, that I think would be cool to jmake. I also want to sort of experiment with different extrusion ways to learn a little bit more about how filament is made, because i am really interested  in the 3d printing space. I also wanted to see if I could blend different pellets to make composite filamets with different properties.

## CAD
I have the link for [Onshape](https://cad.onshape.com/documents/f48d7279894860b6ba842288/w/ddca002676b835894c3001ed/e/73c4766b2e0be6da7adfd5e1?renderMode=0&uiState=6848c3cd49e7b737193d131e), along with the step files in the repo. Here I have the entire filament assembly, and the parts in blue are going to be custom made, the boards are going to be made of wood, while the rest is printed.

![IMG](https://hc-cdn.hel1.your-objectstorage.com/s/v3/63652451610ba19f72e33f3622bdd9e8dfba1bb5_image.png)

![IMG](https://hc-cdn.hel1.your-objectstorage.com/s/v3/592e73b5a4363f9f1a14578a8e91928d3ec6ad37_image.png)
![ING](https://hc-cdn.hel1.your-objectstorage.com/s/v3/63652451610ba19f72e33f3622bdd9e8dfba1bb5_image.png)
![IMG](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2878c4de57fb77733c3c1e6564e1a5e29f5441c7_image.png)

## PCB
So this is just for the filament diameter sensor and is completely optional. I want to be able to see how consistant my filament diameter is for different tests of blends of filament, and this is based off other open source filament diameter measurers. Diafil is the name of the PCB part.
![IMG](https://hc-cdn.hel1.your-objectstorage.com/s/v3/7e6d1a6e955f22f384cadb8ab52cb8e7a0cf28c2_screenshot_2025-06-10_175309.png)

## BOM
| Part Name          | Category   | Price |
| :----------------- | :--------- | :---- |
| Extruder Motor     | Motor      | 9.1  |
| Winder Motor       | Motor      | 18.2  |
| Auger              | Auger      | 9.25  |
| Voltage Regs       | Motor PMW  | 9.3   |
| Heater Band        | Band       | 9.3   |
| PID + SSR + thermo | REX        | 20.9  |
| PIpe               | Iron thing | 7.5   |
| Coupler            | Black      | 6.4   |
| Plugs              | 1/2 NPT    | 4.3   |
| Fans               | 12 V       | 5.8   |
| Power              | 3 pin      | 4.2   |
| Flange             | 1/2        | 6.8   |
| Screws             | 1          | 3.3   |
| Screws             | 2          | 4.2   |
| Spring             | stretch    | 3.1   |
| insulation         | G11        | 7.0   |
| Insulation         | blanket    | 5.2   |
| Cutting blades     | 1/8        | 4.5   |
| Kapton Tape        | 10mm       | 5.5   |
| switches           | 110 V      | 1.7   |
| PSU                | 150W       | 23.4  |
| Wire               | 12 AWG     | 12.9  |
| flange             | 1/2        | 7.3   |
| steel nipple       | 1/2 inch   | 5.2   |
| Drill bit          | flush trim | 12.3  |
| Drill              | any works  | 30.2  |
| Filament           | Easy ABS   | 20.00 |
| Magnet             | 6x2mm      | 0.5   |
| Resistors          | Kit        | 1.0   |
| bearings           | v62zz      | 1.0   |
| Capacitors         | 10UF       | 1.0   |
| ATTiny85           | 1          | 3.0   |
| Arduino nano       | type c     | 3.03  |
| LCD screen         | I2C        | 2.9   |
| Dowels             | m3         | 2.0   |
| PCB cost           | JLCPCB     | 4.5   |
Total cost 266.63


