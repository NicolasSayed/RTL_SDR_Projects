### Goal

The goal of this project is to receive AM channels with an RTL-SDR, which uses the [RTL2832U](../Datasheets/Data_rtl2832u.pdf) chipset.

The RTL SDR can receive frequencies from 500kHz - 1.75GHz. So we can aim for common AM channels such as 1030 AM, or 1030 kHz.

### Components

For this project I am using the V dipole antenna which comes with the RTL SDR.

The RTL SDR actually comes with two different antenna element types, both telescoping dipoles.

- The longer dipole has elements which range from 9 - 39 inches.

- The shorter dipole has elements which range from 2 - 5 inches.

### Procedure

Initially I plan to receive the signal of 1030 AM. So, what is the ideal sizing for my antenna elements? Way too big, I could look into this further but for now I plan to switch to FM demodulation before I understand everything. A simple link budget would show me if the efficiency would be good enough for the 50kW that these AM stations are able to emit.
