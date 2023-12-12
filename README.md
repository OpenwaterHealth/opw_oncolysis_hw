# Preclinical Oncolysis Prototype
## Overview

The Openwater Preclinical Oncolysis Prototype is designed to help researchers investigate the effect of different ultrasound parameters on a variety of in vitro and preclinical in vivo targets. Certain acoustic parameters may be well suited for damaging cancer cells while sparing surrounding healthy tissue, and this system is designed to systematically explore such effects in a laboratory setting.

Multiple focused ultrasound transducers are connected to a programmable signal generator through an amplifier and a switch to select which transducer is active. Samples are placed beneath the transducer(s), using 3D-printed coupling cones filled with water to make a path for the ultrasound and set the depth of the focal spot within the target. This system is compatible with in vitro targets held in standard 6-well plates as well as with mouse flanks, through the assistance of a stereotactic frame.

![image](https://github.com/OpenwaterHealth/opw_oncolysis_hw/assets/6217005/76b72cb4-2e9d-4a80-8a56-801b848d6971)

Controller software allows for configuration of treatment parameters through a simple GUI application. With its default settings, the system can be configured to output focused ultrasound from the parameters shown in the table to the right. This allows for investigation of treatment parameters both within and well above the safety levels used for diagnostic ultrasound imaging.

![image](https://github.com/OpenwaterHealth/opw_oncolysis_hw/assets/6217005/e849b485-e208-44a8-8d42-2a0543ee723a)


Many of the components of the in vivo and in vitro systems were the same, although the precise fixturing used during the experiments was specific to each study.

## Files contained in the Openwater Oncolysis Hardware Repository
* [v1.2 Oncolysis User Manual](Oncolysis%20User%20Manual%20(V1.2).pdf)
  * This user manual is for the in vitro and in vivo systems. It includes:
    * List of components needed for each assembly with links to off-the-shelf components
    * Instructions for how to assemble all of the components for both setups
    * References to part numbers of 3D-printed parts 
* [in vitro setup components](in%20vitro%20setup)
* [in vivo setup components](in%20vivo%20setup)
* [acoustic output validation setup](acoustic%20output%20validation%20setup)

## Contributing
We welcome contributions from the community. If you have ideas for improvements or find any issues, please open an issue or submit a pull request.

Before contributing, please read our [Contributing Guidelines](CONTRIBUTING.md).

## License
This project is licensed under the AGPLv3 License - see the [License](LICENSE) file for details.

## Disclaimer
CAUTION - Investigational device. Limited by Federal (or United States) law to investigational use. This system has not been evaluated by the FDA and is not designed for the treatment or diagnosis of any disease. It is provided AS-IS, with no warranties. User assumes all liability and responsibility for identifying and mitigating risks associated with use
