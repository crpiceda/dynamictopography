# Calculation of Residual Topography
## About
This Jupyter Notebook is a python implementation of the modified approach by Gvirtzman et al. (2016) to calculate the residual topography in the Middle East region, including North Africa, Arabia, the Afar rift, the Mediterranean basins, Anatolia and the Zagros Mountains.

## Pre-requisites
1. A python installation (Anaconda). In case of not having anaconda, download it following this link:
https://docs.anaconda.com/anaconda/install/
2. Clone this repository containing the Jupyter Notebook and the input data files


## Extra dependencies
Install using command `conda install`
- cartopy 0.18.0

## Input data
- *topography.txt*: topography from DEM model ETOPO1 (Amante and Eakins, 2009)
- *l_sed.txt*: sediment thickness from CRUST1 model (Laske et al., 2013)
- *rho_sed.txt*: sediment density from CRUST1 model ((Laske et al., 2013)
- *l_crust.txt*: crustal thickness from CRUST 1 model (Laske et al., 2013)

## References
- Amante, C. and B.W. Eakins, 2009. ETOPO1 1 Arc-Minute Global Relief Model: Procedures, Data Sources and Analysis. NOAA Technical Memorandum NESDIS NGDC-24. National Geophysical Data Center, NOAA. doi:10.7289/V5C8276M [access date: 6/24/2021]
- Gvirtzman, Z., Faccenna, C., Becker, T. W., 2016. Isostasy, flexure, and dynamic topography. Tectonophysics, 683, 255–271.
- Laske, G., Masters., G., Ma, Z. and Pasyanos, M., 2013. Update on CRUST1.0 - A 1-degree Global Model of Earth's Crust, Geophys. Res. Abstracts, 15, Abstract EGU2013-2658

## License


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
