We need to define three standards:
- physical case configurations (initial conditions, forcings, thermodynamical constants etc...)
- 1D profiles output formats
and to write scripts to post process LES raw outputs to put them in the common format. 

# Physical case
## Geometry
f_z: traditional Coriolis parameter, s-1
f_y: non-traditional Coriolis parameter, s-1

## Thermodynamical Constants

## Forcings

## Initial condition



# Outputs (short name: long name, units, comments)

## Grid specification
Vertical axis oriented from bottom to top.
z_c: vertical coordinate at the center of the cell, m
z_f: vertical coordinate at the face of the cell, m



## Variables 
temp
salinity
u
v
w
tke (resolved)
tke_sbg (if available)
wt (resolved)
wu(resolved)
wv (resolved)
wt_sbg
wu_sbg
wv_sbg
wtke
w2
(temp)2


