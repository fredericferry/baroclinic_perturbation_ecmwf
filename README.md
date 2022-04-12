# perturb_era5
Study a baroclinic perturbation in ERA5 reanalysis data with plots of various meteorological diagnostics

Note 1 : This code was developed for educationnal purposes, and for French students. So the comments in the notebook are in French but the graphics and legends are in English.

Note 2 : If you have any comment/suggestion, if you find this code useful --> please send me an email : mailto:frederic.ferry@meteo.fr

The ERA5 data needed to run the notebook (MSLP, z, u, v, t, pv, w, q) are NOT provided. They can be downloaded here :
https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=form
https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-pressure-levels?tab=form

If you can't find the data ask me and I'll make it available for you.

With the student notebook you will be able to compute and plot :
- Thickness
- Potential temperature
- Equivalent Potential temperature (Metpy function)
- Relative humidity (Metpy function)
- Geostrophic and agesotrophic winds
- Divergence
- Vorticity (relative/absolute)
- Potential vorticity
- Temperature advection
- Differential vorticity advection

With the full notebook you will be able to compute and plot more advanced diagnostics :
- Interpolation of the isobaric potential vorticity on an isentropic surface (Metpy function)
- Gostrophic forcing and its convergence/divergence (Q1, Q2, div(Q))
- Frontogenesis and deformation field

--------------------------------------------------------------------------------------------------------------------------------------------------
![ERA5_ZTadv850_VV600_2014-01-26T00](https://user-images.githubusercontent.com/76565450/162592422-875a3217-d37c-4fe0-9964-d9cd2b425936.png)
![ERA5_Zvortadv300_850_VV600_2014-01-26T00](https://user-images.githubusercontent.com/76565450/162592424-b66539ec-0c18-4e1d-b9a8-a259a71c01e6.png)
![PV300_Thetae850_vort925_20140125-T00-20140126-T18](https://user-images.githubusercontent.com/76565450/162592407-3a73f917-a802-4b73-8bb9-3ac1ef06a085.gif)
![ERA5_Q_2014-01-26T00](https://user-images.githubusercontent.com/76565450/162981292-3851784e-e2c4-4545-840a-dc9859e46d4c.png)
![ERA5_fronto1_2014-01-26T00](https://user-images.githubusercontent.com/76565450/162981308-868855d7-3c01-4ad2-be33-13d720d00508.png)
