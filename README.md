# Technical-Portfolio
The technical portfolio presents a Lumerical FDTD and a Zemax project. The repository presents both the portfolio, the Zemax and the Lumerical files.


Figure 2

Figure 2 is composed of 4 panels. For each of them, Lumerical files and log files (or screenshots) are provided.
"Figure_2_transversal_plasmon_simulation.fsp" and "Figure_2_transversal_plasmon_simulation.log" contain the simulation data for the transversal plasmon. The light source polarisation is set parallel to the short axes of the nanorod. 
In this configuration, the dye does not affect the optical properties of the rods, as it absorbs at different energies than the transversal plasmon. 
Consequently, the refractive index of the nanorod shell (labelled as CL in the simulation file) is set as a constant value of 1.73, and the extinction profile is reused for all panels in Figure 2.

"Figure_2a_longitudinal_plasmon" is a screenshot for the same simulation as above, but with the light source polarised along the long axes of the nanorods, in order to reveal the longitudinal plasmon extinction. 
The same file was used to retrieve the electromagnetic field with a very small mesh (0.05 nm). Due to file size limitations, only a screenshot is included.

Files starting with "Figure_2b" are Lumerical and log files of the same simulation, with the addition of a Lorentzian absorption in the nanorod shell at the energy of the longitudinal plasmon.
The oscillator strength of the Lorentzian curve was set to 0.0475. This allowed to simulate the PIC-nanorod extinction.

Files starting with "Figure_2c" and "Figure_2d" refer to simulations with different oscillator strengths (0.055 and 0.1, respectively), enabling the modelling of different PIC concentrations.


Figure 3

The screenshots reported in "Figure_3_EFSERS_file" and in "Figure_3_EFSERS_file_setup" show the simulation file and its configuration, used to evaluate the SERS enhancement factor of the vibration at 675 cm^-1 for a nanorods-TDBC sample.
The simulated sample is the one with the highest value in Figure 3 (approximately 35000, blue line).
The field was calculated at lambda_excitation = 580 nm and lambda_emission = 604 nm, as reported in "Figure_3_EFSERS_file_setup". These wavelengths were experimentally determined.


Figure_cover_EM_field

This screenshot was retrieved from the same simulation file used to produce "Figure_2a_longitudinal_plasmon". 
It represents the simulated electromagnetic field of a gold nanorod excited at 590 nm and with polarization parallel to the long nanorod axis, as reported in the front cover of the Portfolio.

Microscope_zemax

"Microscope_zemax.ZDA" and "Microscope_zemax.zmx" are the files that fully define the microscope designed with Zemax and described in this portfolio.

