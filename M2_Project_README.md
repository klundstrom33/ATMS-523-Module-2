# This describes the M2_Project notebook
1) Choose a variable from the hourly 0.25° Pressure and Surface Level Data... in this case we choose total precipitation [m]

2) Choose a city location... in this case we choose Pinedale, WY (42.87 N, 109.86 W)


Subset the data into the following:
- At a point nearest to city for date range
- 5 X 5 degree lat/long box around city for date range
- Total precipitation at every ERA5 grid point for each month from 1981 to 2020


3) Plots:
- Daily total precipitation at City location over time period
- CDF and 95th percentile of daily total precipitation averaged over the 5X5 box
- Map of mean daily total precipitation for the continential US on days where the mean precipitation in the 5X5 box >= 95th percent
- Map of the anomoly of mean daily total precipitation for the continential US on days where the mean precipitation in the 5X5 box >= 95th percent from the mean daily total precipitation for the continential US from 1981-2020

4) Data saved: daily precipitation for a 5 X 5 degree lat/long box around city for date range

## Citations
Information on how to download the ERA5 data is found at: https://github.com/google-research/arco-era5

Citation: 
Carver, Robert W, and Merose, Alex. (2023):
ARCO-ERA5: An Analysis-Ready Cloud-Optimized Reanalysis Dataset.
22nd Conf. on AI for Env. Science, Denver, CO, Amer. Meteo. Soc, 4A.1,
https://ams.confex.com/ams/103ANNUAL/meetingapp.cgi/Paper/415842

ERA5 Dataset Citation:
Hersbach, H., Bell, B., Berrisford, P., Hirahara, S., Horányi, A., 
Muñoz‐Sabater, J., Nicolas, J., Peubey, C., Radu, R., Schepers, D., 
Simmons, A., Soci, C., Abdalla, S., Abellan, X., Balsamo, G., 
Bechtold, P., Biavati, G., Bidlot, J., Bonavita, M., De Chiara, G., 
Dahlgren, P., Dee, D., Diamantakis, M., Dragani, R., Flemming, J., 
Forbes, R., Fuentes, M., Geer, A., Haimberger, L., Healy, S., 
Hogan, R.J., Hólm, E., Janisková, M., Keeley, S., Laloyaux, P., 
Lopez, P., Lupu, C., Radnoti, G., de Rosnay, P., Rozum, I., Vamborg, F.,
Villaume, S., Thépaut, J-N. (2017): Complete ERA5: Fifth generation of 
ECMWF atmospheric reanalyses of the global climate. Copernicus Climate 
Change Service (C3S) Data Store (CDS).