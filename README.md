# opendillo

opendillo is a FPV frame for fullsized cams and is compatible with the [spare arms for the floss (2)](http://pirofliprc.com/5mm-Replacement-Arms-For-Hyperlite-Floss-5-inch-22XX-5-pcs-_p_4425.html).

<img src="https://raw.githubusercontent.com/Robinhuett/opendillo/master/pictures/opendillo_render.png" width="600">

## Specifications

- Wheelbase: 223mm 5"
- Baseplate: 3mm
- Arm thickness: 4-5mm
- Stackmount: 30,5mm x 30,5mm

## Directory structure

- `/`

  The assembly files and git related stuff

- `/base/*`

  All necessary parts for the frame exluding the parts in `/flavor/*`.

- `/flavor/*`

  Remaining parts for the frame in multiple variations. Pick one depending on your needs. In the SolidWorks files it's probably a configuration.

- `/accessories/*`

  Additional stuff like GoPro Mounts.

## Manufacturing

Anufacturing of this frame is a little bit more complex than most other frames, since it currently depends on carbon milling, aluminum milling and 3D printing.

### Carbon parts

- `/base/base*`
  - 3mm
- `/flavor/arm*`
  - 4-5mm

### Aluminum parts

- `/base/bracket*`

Currently i'm milling the brackets myself with an 3Axis CNC mill and drilling the remaining holes with the help of an 3D printed drill guide (Kinda a negative of the brackets). 5Axis milling would be preferable though.

### 3D printed parts

- `/base/canopy*`
- `/flavor/antennamount*`
- `/accessories/*`

All parts should pe printed in TPU. Also all parts can be printed without support structures. The `canopy` is a little bit tricky but definitely possible. When im doing the next print, I'll be updating with my print settings.

## Compatibility

All SolidWorks files are saved with SolidWorks 2018.

Unfortunatly this frame is currently not compatible with the C-Train arms for the floss 2.1. But in the SolidWorks files you can find (pretty half-assed) configurations for compatible parts. This will change in the future, when I broke all my spare parts or demand is high enough.

## Authors

* **Robin Tripp** - *Initial work* - [Robinhuett](https://github.com/Robinhuett)
* **Felix Röse** - *Initial work*

See also the list of [contributors](https://github.com/Robinhuett/opendillo/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* **KababFPV** - *[Youtube Channel](https://www.youtube.com/user/eatkabab)* - *[Floss2 Frame](http://pirofliprc.com/HyperLite-Floss-2-5mm-ARMS-Choose-Arm-Length-_p_4194.html)*
