# Deuterium-Hydrogen-Ratio
TEXES data used for the research paper Blake et al. (2021)

This .sav file contains the following variables: 

AIRMASS         FLOAT     = Array[53, 53]
CONTMAP         FLOAT     = Array[53, 53]
EMISMAP         FLOAT     = Array[53, 53]
HDR             STRING    = Array[122]
INTTIME         FLOAT     = Array[2488, 53, 53]
LATITUDE        FLOAT     = Array[53, 53]
LONGITUDE       FLOAT     = Array[53, 53]
MAPGRID         FLOAT     = Array[53]
MAP_PIXEL_SCALE FLOAT     =      0.700000
SKY             FLOAT     = Array[2488, 53, 53]
SPEC_CUBE       FLOAT     = Array[2488, 53, 53]
VEL_MAP         FLOAT     = Array[53, 53]
WAVENUMBER      DOUBLE    = Array[2488]

The airmass, contmap, emismap, latitude, longitude and velmap arrays correspond to the spectels of the spec_cube.
The spec cube contains the radiance in nW /arcsec /str /micron for each wavenumber in each spectel.
The header is in HDR which contains all ancilliary ephemeris of the IRTF telescope at the the time of observation.
