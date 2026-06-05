<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="./docs/assets/mental-dark.png"
  >
  <source
    media="(prefers-color-scheme: light)"
    srcset="./docs/assets/mental-light.png"
  >
  <img
    src="./docs/assets/mental-light.png"
    height="100"
    align="left"
    alt="mentaldsp logo"
  >
</picture>

<br clear="left" />

### Table of Contents

- [Bill of Materials](#bill-of-materials)
- [Hardware](#hardware)
- [Software](#software)
- [Acknowledgment](#acknowledgment)

## Bill of Materials

|Component|Specifications|Quantity|Price (per unit)|Price (total)|Where to buy|
|---|---|---|---|---|---|
|Stepper Motor|NEMA 17 (17HS4023)|3|€6.53|€19.59|[AliExpress](https://a.aliexpress.com/_EuMzXUE)|
|Stepper Motor Driver|TMC2209 (BTT v1.3)|3|€3.8|€11.4|[AliExpress](https://a.aliexpress.com/_EGuPfX0)|
|Flexible shaft|L300mm D4mm|3|€5.93|€17.79|[AliExpress](https://a.aliexpress.com/_EHIs5H8)|
|Coupler (motor to shaft)|5mm to 4mm|3|€0.45|€1.35|[AliExpress](https://a.aliexpress.com/_EwQRNfs)|
|Coupler (shaft to pots)|5mm to 6.35mm|3|€0.45|€1.35|[AliExpress](https://a.aliexpress.com/_EwQRNfs)|
|2020 Aluminum Extrusion|L100mm|6|€depends|€depends||
|2040 Aluminum Extrusion|L100mm|3|€depends|€depends||
|2020 Extrusion Bracket|90deg|6|€0.25|€1.5|[AliExpress](https://a.aliexpress.com/_EIpKqK2)|
|Slide-in Nut|M5 10mm|48|€0.16|€7.68|[AliExpress](https://a.aliexpress.com/_EICuedC)|
|DIN912 M5 screws|M5 10mm|18|€0.19|€3.42|[AliExpress](https://a.aliexpress.com/_EJXdA0I)|
|ISO7380 M5 screws|M5 10mm|30|€0.16|€4.8|[AliExpress](https://a.aliexpress.com/_EGQIF4S)|
|M5 washers (for 10mm M5 screws)|M5|48|€depends|€depends||
|3M/Scotch Dual lock|1m|1|€depends|€depends||
|ESP32-S3 Dev Board|Supermini|1|€3.8|€3.8|[AliExpress](https://a.aliexpress.com/_EJnZ8Py)|

## Hardware

### KiCAD

![top](https://thvofi.github.io/mentaldsp/assets/top.png)
rendered with [kicad-render](https://github.com/linalinn/kicad-render)

### 3D models

## Software

### Embedded

### Recording and Training

## Acknowledgment

This project would not exist without the help of these amazing people and projects:
- My advisor and good friend [Valtteri](https://kallinen.xyz/)
- Solomon at the [Aalto Fablab](https://studios.aalto.fi/fablab/)
- [Daniel Frenkel](https://valarsystems.com/) and his [Trinamic Guide](https://valarsystems.com/products/controlling-trinamic-drivers-pdf)
- teemuatlut for making the [TMCStepper](https://github.com/teemuatlut/TMCStepper) library
- [DukeDesigns3D](https://dukedesigns3d.com/) and [JHS Pedals](https://www.youtube.com/@jhspedals) for the inspiration from the [Toe-N Control](https://www.youtube.com/watch?v=elcASapCZRY)

Projects I have looked at:
- [AndreaFavero71/stepper_sensorless_homing](https://github.com/AndreaFavero71/stepper_sensorless_homing)
- [janelia-arduino/TMC2209](https://github.com/janelia-arduino/TMC2209)
