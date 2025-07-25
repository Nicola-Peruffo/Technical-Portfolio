# Technical Portfolio

This technical portfolio presents one **Lumerical FDTD** project and one **Zemax** project.  
The repository includes the portfolio document, along with all Zemax and Lumerical simulation files (or screenshots).

## Figure 2

Figure 2 is composed of four panels. For each of them, Lumerical files and log files (or screenshots) are provided.

### `Figure_2_transversal_plasmon_simulation.fsp` and `.log`

These files contain the simulation data for the **transversal plasmon**.  
- The light source polarisation is set parallel to the **short axis** of the nanorod.  
- In this configuration, the dye does not affect the optical properties of the rods, as it absorbs at different energies than the transversal plasmon.  
- Consequently, the refractive index of the nanorod shell (labelled as `CL` in the simulation file) is set to a constant value of 1.73  and the extinction profile retrieved from this simulation is reused for all panels in Figure 2.

### `Figure_2a_longitudinal_plasmon`

This is a screenshot from the same simulation as above, but with the light source polarised along the **long axis** of the nanorods, to reveal the **longitudinal plasmon** extinction.  
The same file was used to retrieve the electromagnetic field using a very small mesh (0.05 nm, see Figure_cover_EM_field). Due to file size limitations, only a screenshot is included.

### `Figure_2b_sweep_3_p0_PIC_0,3uM`

These files refer to the same simulation setup, with the addition of a **Lorentzian absorption** in the nanorod shell at the energy of the longitudinal plasmon.  
The oscillator strength was set to 0.0475. This allowed the simulation of **PIC–nanorod** extinction.

### `Figure_2c_sweep_4_p0_PIC_0,6uM` and `Figure_2d_sweep_6_p0_PIC_7,4uM`

These files were obtained by sweeping the oscillator strengths and selecting the one matching the experimental extinction.
- `Figure_2c_sweep_4_p0_PIC_0,6uM`, oscillator strength set to 0.055
- `Figure_2d_sweep_6_p0_PIC_7,4uM`, oscillator strength set to 0.1

This enables the modelling of different **PIC concentrations** on the surface of the nanorod.


## Figure 3

The screenshots in `Figure_3_EFSERS_file` and `Figure_3_EFSERS_file_setup` show the simulation file and configuration used to evaluate the **SERS enhancement factor** of the vibration at 675 cm⁻¹ for a nanorod–TDBC sample.
- The simulated sample corresponds to the one with the **highest EF value** in Figure 3 (~35,000, blue line).  
- The field was calculated at `λ_excitation = 580 nm` and `λ_emission = 604 nm` (as reported in `Figure_3_EFSERS_file_setup`, and determined experimentally)

The file `Figure_3_EFSERS_script.txt` contains the script used to calculate the **EF_SERS** after field simulation.


## Figure_cover_EM_field

This screenshot was retrieved from the same simulation file used to generate `Figure_2a_longitudinal_plasmon`.  
It shows the simulated **electromagnetic field** of a gold nanorod excited at 590 nm and with polarization parallel to the **long nanorod axis**.

This image appears on the **front cover** of the portfolio.


## Microscope_zemax

The following files define the microscope designed with **Zemax** and described in this portfolio:

- `Microscope_zemax.ZDA`
- `Microscope_zemax.zmx`
