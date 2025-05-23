# Physical case: WANG1_FR_lat60 (Free Convection and Full Rotation)
Similar to case 1 of Wang (2006), https://doi.org/10.1016/j.dynatmoce.2006.01.001
## Geometry
- latitude=60°N --> f_z: 1.26 e-4 s-1, f_y: 7.29 e-5 s-1

## Thermodynamical Constants
Linear EOS $b= g( \alpha (T - T_0) - \beta (S - S_0))$
- $T_0= 13.5 °C$       
- $\alpha = 2.6e-4 K^{-1}$       
- $S_0=32.6 psu$
- $\beta = 7.7475e-4 psu^{-1}$
- $c_p = 4178 J K^{-1} kg^{-1}$
- $\rho_0 = 1000 kg m^{-3}$

## Forcings
- heat flux (non-solar): $-111 Wm^{-2}$
- oceanic shear stress: $\tau_x = 0.0 Pa$
- waves: $0$
- solar flux: $0 Wm^{-2}$
- freswater flux: $0 psu.m.s^-1$

## Initial conditions
Initial temp. mixed layer of 1000m, then linear below
- $T(z) = 3.0 °C$ between 0 and -1000m, then $T(z) = N_0^2 (z+1000) / (g \alpha) + T_{\rm sfc} $
- $T_{\rm sfc}$ = 3.0 °C 
- $N_0^2 = 1.44 e-8 s^{-2}$
- $S(z) = 32.6 psu$

# Outputs 

## MésoNH LES
- /summer/plume/LES_mesoNH/WANG1_FR_lat60
- domain: $L_x=14400 km, L_y= 14400 km, L_z= 4500m$
- grid: $\Delta x = 75m,\Delta y= 75m,\Delta z= 25m$
- duration: 276h, time step: 150s
- turbulence scheme: 3D TKE
- reference describing the simulation: PhD thesis of Manolis Perrot, chapter 5.
