# careful-cots
## Careful COTS engineering workspace

The proposed goals of Phase 4 Space are outlined below. 

1. Perform a [Careful COTS][1] (re)design of an Ettus Research 300 series USRP. 

   Blog post about the series.
https://www.ettus.com/blog/2014/01/ettus-research-releases-revolutionary-software-defined-radio-with-kintex-7

   Schematic for the x300.
https://files.ettus.com/schematics/x300/

   The USRP is a world-class SDR that is completely compatible with GNU Radio. Implementing a version of this USRP for space perfectly complements the work done to support DVB-S2/X for amateur radio payloads that is ongoing in Phase 4 Ground. 

2. Three-axis stabilization must be implemented to support directional microwave antennas at 5GHz, 10GHz, and beyond. 

3. Develop a payload that supports the [Rincon AstroSDR][2] donated from Mike Parker of Rincon. This device is hosted by Virginia Tech and uses the same FPGA as the Ettus series 7 USRPs.


[1]: https://digitalcommons.usu.edu/cgi/viewcontent.cgi?article=2934&context=smallsat

[2]: http://www.rincon.com/wp-content/uploads/2016/11/ASTROSDR_Brief_v1-3-1.pdf
