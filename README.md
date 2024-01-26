# modFG20
UV background used in Ploeckinger &amp; Schaye; UVB is based on Faucher-Giguere (2020) but with additional attenuation until H and He reionization is complete

The ascii file modFG20_cloudy.txt is formatted so that it can be used directly with [Cloudy v17.01](https://www.nublado.org/) by replacing the hm12_galaxy.ascii file. 

Content of modFG20_cloudy.txt:
* Line  1: version check for Cloudy, this needs to match the number that Cloudy expects; this might be different for different Cloudy versions and it should match that of the first line in the replaced hm12_galaxy.ascii 
* Line  5: number of redshifts
* Line  6: number of wavelengths
* Line 11: redshifts
* Line 12: wavelengths in units of Angstrom
* Line 13 - : J_nu in units of erg s^-1 cm^-2 Hz^-1 sr^-1; each line is J_nu(wavelength as in line 6) at a constant redshift (order as in line 5)

