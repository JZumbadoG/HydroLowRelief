Files description and headers

Geometry_Parameters.dat
Contains the porosity and frontal area values as a function of vertical position for both density cases.
Header: Variable Name / Units / Variable description
z       (m) : Vertical position
ncD     (-) : Porosity of the dense reef
ncD_unc (-) : Uncertainty of the porosity dense reef
ncS     (-) : Porosity of the sparse reef
ncS_unc (-) : Uncertainty of the porosity sparse reef
aD      (1/m) : Frontal area per canopy volume of the dense reef
aD_unc  (1/m) : Uncertainty of the frontal area per canopy volume of the dense reef
aS      (1/m) : Frontal area per canopy volume of the dense reef
aS_unc  (1/m) : Uncertainty of the frontal area per canopy volume of the dense reef

Dense_Hydro.dat and Sparse_Hydro.dat
Contains the hydrodynamic variable as a function of vertical position for both density cases.
Header (for both): Variable Name / Units / Factor* / Variable description
z          (m)  (10^-2): Vertical position
u          (m/s)(10^-2): Double-averaged streamwise velocity 
u_unc      (m/s)(10^-2): Uncertainty of double-averaged streamwise velocity 
v          (m/s)(10^-2): Double-averaged lateral velocity 
v_unc      (m/s)(10^-2): Uncertainty of double-averaged lateral velocity 
w          (m/s)(10^-2): Double-averaged vertical velocity 
w_unc      (m/s)(10^-2): Uncertainty of double-averaged vertical velocity 
uRMS       (m/s)(10^-3): Streamwise dispersive turbulence intensity
uRMS_unc   (m/s)(10^-3): Uncertainty of streamwise dispersive turbulence intensity
vRMS       (m/s)(10^-3): Lateral dispersive turbulence intensity
vRMS_unc   (m/s)(10^-3): Uncertainty of lateral dispersive turbulence intensity
wRMS       (m/s)(10^-3): Vertical dispersive turbulence intensity
wRMS_unc   (m/s)(10^-3): Uncertainty of vertical dispersive turbulence intensity
up         (m/s)(10^-2): Spatially-averaged streamwise turbulence intensity
up_unc     (m/s)(10^-2): Uncertainty of spatially-averaged streamwise turbulence intensity
vp         (m/s)(10^-2): Spatially-averaged lateral turbulence intensity
vp_unc     (m/s)(10^-2): Uncertainty of spatially-averaged lateral turbulence intensity
wp         (m/s)(10^-2): Spatially-averaged vertical turbulence intensity
wp_unc     (m/s)(10^-2): Uncertainty of spatially-averaged vertical turbulence intensity
upwp       (m^2/s^2)(10^-4): Spatially-averaged streamwise-vertical Reynolds shear stress
upwp_unc   (m^2/s^2)(10^-4): Uncertainty of spatially-averaged streamwise-vertical Reynolds shear stress
upvp       (m^2/s^2)(10^-4): Spatially-averaged streamwise-lateral Reynolds shear stress
upvp_unc   (m^2/s^2)(10^-4): Uncertainty of spatially-averaged streamwise-lateral Reynolds shear stress
vpwp       (m^2/s^2)(10^-4): Spatially-averaged Lateral-vertical Reynolds shear stress
vpwp_unc   (m^2/s^2)(10^-4): Uncertainty of spatially-averaged lateral-vertical Reynolds shear stress
uppwpp     (m^2/s^2)(10^-4): Streamwise-vertical dispersive stress
uppwpp_unc (m^2/s^2)(10^-4): Uncertainty of streamwise-vertical dispersive stress
uppvpp     (m^2/s^2)(10^-4): Streamwise-lateral dispersive stress
uppvpp_unc (m^2/s^2)(10^-4): Uncertainty of streamwise-lateral dispersive stress
vppwpp     (m^2/s^2)(10^-4): Lateral-vertical dispersive stress
vppwpp_unc (m^2/s^2)(10^-4): Uncertainty of lateral-vertical dispersive stress
k          (m^2/s^2)(10^-3): Spatially-averaged turbulent kinetic energy
k_unc      (m^2/s^2)(10^-3): Uncertainty of spatially-averaged turbulent kinetic energy
kD         (m^2/s^2)(10^-3): Dispersive turbulent kinetic energy
kD_unc     (m^2/s^2)(10^-3): Uncertainty of dispersive turbulent kinetic energy

Dense_MomBalance.dat and Sparse_MomBalance.dat
Contains the terms of the momentum balance equation for both density conditions
Header (for both): Variable Name / Units / Factor* / Variable description
z        (m)(10^-2):     Vertical position
Rey      (m/s^2)(10^-3): Streamwise-vertical Reynolds shear stress
Rey_unc  (m/s^2)(10^-3): Uncertainty of Streamwise-vertical Reynolds shear stress
Disp     (m/s^2)(10^-3): Streamwise-vertical dispersive stress
Disp_unc (m/s^2)(10^-3): Uncertainty of streamwise-vertical dispersive stress
Drag     (m/s^2)(10^-3): Oyster drag term (residual)
Drag_unc (m/s^2)(10^-3): Uncertainty of oyster drag term
SK       (m/s^2)(10^-3): Secondary currents of Prandtl’s second kind (residual)
SK_unc   (m/s^2)(10^-3): Uncertainty of Secondary currents of Prandtl’s second kind 
dpdx     (m/s^2)(10^-3): Pressure gradient

Dense_DragCoeff.dat and Sparse_DragCoeff.dat
Contains the local drag coefficient for both density conditions. Note: The filtered values according with the SNR criterium are reported as NaN.
Header (for both): Variable Name / Units / Factor* / Variable description
z       (m)(10^-2): Vertical position
CD      (-)(-):     Local drag coefficient
CD_unc  (-)(-):     Uncertainty of local drag coefficient
CDW     (-)(-):     Local drag coefficient without dispersive stress
CDW_unc (-)(-):     Uncertainty of local drag coefficient without dispersive stress
Lc      (m)(-):     Local drag length-scale 
Lc_unc  (m)(-):     Uncertainty of local drag length-scale 
LcW     (m)(-):     Local drag length-scale without dispersive stress
LcW_unc (m)(-):     Uncertainty of local drag length-scale without dispersive stress

Dense_lmix.dat and Sparse_lmix.dat
Contains the eddy viscosities and mixing length for both density conditions.
Header (for both): Variable Name / Units / Factor* / Variable description
z         (m)(10^-2): Vertical position
lmix      (m)(10^-2): Mixing-length values
lmix_unc  (m)(10^-2): Uncertainty of mixing-length values
vt        (m^2/s)(10^-4): Eddy viscosity values
vt_unc    (m^2/s)(10^-4): Uncertainty of Eddy viscosity values

Model_Solution.dat
Contains the estimated streamwise velocities and Reynols stress values from the simplified model.
Header: Variable Name / Units / Factor* / Variable description
z       (m)(10^-2): Vertical position
upwp_D  (m^2/s^2)(10^-4): Solved spatially-averaged streamwise-vertical Reynolds shear stress for dense condition
upwp_S  (m^2/s^2)(10^-4): Solved spatially-averaged streamwise-vertical Reynolds shear stress for sparse condition
u_D     (m/s)(10^-2): Solved double-averaged streamwise velocity for dense condition
u_S     (m/s)(10^-2): Solved double-averaged streamwise velocity for sparse condition

* To obtain dimensional quantities in the tables, the factors reported above must be multiplied by each variable.
