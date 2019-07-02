# CDSN-Firmware
China Digital Seismic Network (CDSN) Station Firmware - https://www.fdsn.org/networks/detail/CD/

This software was developed by me for the Albuquerque Seismological Laboratory (part of the USGS) from 1985 to about 1987.

This was developed on an RT-11 workstation and cross-compiled for the 8088 in C and burned onto e-prom.   There were 10 of these stations installed in China.

These were later replaced by GSN stations.

I also designed a separate unit which could read the 3M QIC cartridges that these systems made and converted them to 1600 BPI 9-Track Magtape.   This included designing the hardware for a basic Pertic-Interface.

This includes a seismic event detector developed by James N Murdock and ported from Fortran to C by me.

* https://pubs.er.usgs.gov/publication/ofr87158
* https://www.amazon.com/Language-Implementation-Murdock-Detector-Analyzer/dp/128883652X
* https://www.usgs.gov/centers/geohazards/about/albuquerque-seismological-laboratory
