# WND_VAR_T

- source: https://data.open-power-system-data.org/time_series/, DE_wind_profile
- selected data: take profiles, if existing, else actual generation
	- DE4-E_A: 50 Hz onshore (DE_50hertz_wind_generation_forecast)
	- DE4-E_Offshore_A: 50 Hz offshore (DE_50hertz_wind_generation_forecast)
	- DE4-N_Offshore_A und DE4-W_Offshore_A: Tennet offshore (DE_tennet_wind_offshore_generation_actual)
	- DE4-S_A: ENBW (DE_transnetbw_wind_generation_forecast)
	- DE4-W_Onshore_A: Amprion (DE_amprion_wind_generation_forecast)
	- DE4-N_Onshore_A: DK2 Large (DK_2_wind_generation_actual)