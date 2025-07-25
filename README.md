# Technical-Portfolio
The technical portfolio presents a Lumerical FDTD and a Zemax project. The repository presents both the portfolio, the Zemax and the Lumerical files.

Figure 2

Figure 2 is composed of 4 panels. For each of them, Lumerical files and log files (or screenshots) are added.
Figure_2_transversal_plasmon_simulation.fsp and Figure_2_transversal_plasmon_simulation.log are the simulation files for simulating the transversal plasmon. The light source polarisation is set parallel to the short axes of the nanorod. 
In this situation, the dye does not change the optical properties of the rods as it absorbs at different energies compared to the transversal plasmon. 
The refractive index of the nanorod shell (CL in the simulation file) is set as a constant of 1.73. Consequently, the extinction retrieved for this simulation is used for all panels of Figure 2.

Figure_2a_longitudinal_plasmon is a screenshot of the same simulation above, but with the light source parallel to the long axes of the nanorods, in order to reveal the longitudinal plasmon extinction. 
The same file was used to retrieve the electromagnetic field with a very small mesh (0.05 nm). The file was not uploaded, but only its screenshot, due to file weight constriction.

Files starting with "Figure_2b" are Lumerical and log files of the same simulation above, but introducing in the nanorod shell a lorentzian absorption at the energy of the longitudinal plasmon with an oscillator strength equal to 0.0475. 
This allowed to simulate the PIC absorption.

Files starting with "Figure_2c" and "Figure_2d" are Lumerical and log files of the same simulation above, but with different oscillator strengths (0.055 and 0.1), allowing the simulation of different PIC concentrations.

Figure 3

The screenshots reported in "Figure_3_EFSERS_file" and in "Figure_3_EFSERS_file_setup" show the simulation file and setup used to evaluate the SERS enhancement factor of the vibration at 675 cm^-1 for a nanorods-TDBC sample.
The sample simulated is the one with the highest value in Figure 3 (value of about 35000, blue line). 
The field was calculated at lambda_excitation and lambda_emission equal to 580 nm and 604 nm, as reported in "Figure_3_EFSERS_file_setup". The lambda_excitation and lambda_emission values were found experimentally.

Microscope_zemax

"Microscope_zemax.ZDA" and "Microscope_zemax.zmx" are two files that report integrally the microscope designed with Zemax and reported in this portfolio.

