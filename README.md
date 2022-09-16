# crab_pheno
If you use the data collection assembled here or the model calculations provided here, please reference our paper:

* L. Dirson and D. Horns* _Phenomenological modelling of the Crab Nebula’s broad-band
energy spectrum and its apparent extension_ arXiv:2203.11502_

The data points have been collected from different sources and compiled in a set of files. The files and their are provided as they are without
any guarantee that the values are acurate.  If you do find inconsistencies or disagreement, please notify us/open an issue.

Within each data file, the units have been adapted to a common format. The units are not identical for the different files. Please find below 
additional informations. We have included a sample notebook to read in the files and overplot the best fitting model from the publication for
$\alpha=0.51$. Each line carries a reference code of the paper in the form used by ADS (sth like `1972ApJ...171...41M`).

  * `radio_data.csv`: Frequency (in GHz), flux (in Jy), flux uncertainty (in Jy), epoch of observation, reference. Note, the fluxes have not been corrected for secular decline which is typically 0.1% per year. 
  * `ir_data.csv`: Wavelength (in Angstrom), flux (in Jy), flux uncertainty (in Jy), reference. 
  * `optical_data.csv`: Wavelength (in Angstrom), (corrected) flux (in Jy), absorption (in mag from 1993A&A...270..370V), ref, re-calculated absorption (in mag) from O94 model using $A_v=1.08$, $E_{B-V}=0.43$
  * `xray_data.csv`: Energy (in keV), photoel. absorption corrected energy flux (keV/cm$^2$/s), uncertainty, reference.
  * `gamma_data.csv`: Energy (in GeV), energy flux (in erg/cm$^2$/s), uncertainty, reference.
  * `sample_plot.ipynb`: should be self-explanatory. Req. py3.
