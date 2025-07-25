### Goal

The goal of this project is to receive AM channels with an RTL-SDR, which uses the [RTL2832U](../Datasheets/Data_rtl2832u.pdf) chipset.

The RTL SDR can receive frequencies from 500kHz - 1.75GHz. So we can aim for common FM channels such as 89.9 FM, a local Jazz station hosted by UCF.

### Components

For this project I am using the V dipole antenna which comes with the RTL SDR.

The RTL SDR actually comes with two different antenna element types, both telescoping dipoles. I used this antenna guide for my dipole, [link](https://makerworld.com/en/models/1127183-noaa-guide-for-rtl-sdr-kit-antenna#profileId-1126828).

- The longer dipole has elements which range from 9 - 39 inches (22.9 - 99 cm).

- The shorter dipole has elements which range from 2 - 5 inches (5.1 - 12.7 cm).

### Procedure

I plan to receive signal from 89.9 FM, which corresponds to 89.9 MHz. This means that I want my antenna elements to ideally be 83.47cm, which isn't terribly large. The VSWR I measured at this was about 1.5 with a 120 degree V.
