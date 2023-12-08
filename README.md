# cap6707_uav_project
Repository for my CAP6707 Class Project

Data is taken from the LOG file for a UAV_speed of 10, Wind_speed of 5, and a UAV_altitude of 100 meters with a wind angle of 90 degrees

Note: All deliveries are under distances of 5 kilometers due to UAV battery constraints

## Variables
simt = Simulation time (measured in seconds)

id = Unique ID of UAV (as a string)

type = Type of UAV (as a string)

lat = Latitude (in degrees)

lon = Longitude (in degrees)

alt = Altitude (in meters)

distflown = Distance flown (in meters)

temp = Air temperature (in Kelvin)

trk = Track angle (in degrees)

hgd = Heading Direction (in degrees)

tas = Aircraft true airspeed (m/s)

cas = Aircraft calibrated airspeed (m/s)

vs = Aircraft vertical speed (m/s)

gs = Aircraft ground speed (m/s)

p = Air pressure (N/m^2)

rho = Air density (kg/m^3)

thrust = Aircraft net thrust calculated based on drag

drag = aircraft drag calculation based on OpenAP drag polar

phase = flight phase calculation based on altitude, speed, and vertical rate

fuelflow = fuel flow calculation

## Drone Specifications
All drones were DJI Matrice 600's (M600) and have the following constraints:

number of engines (n_engines): 6

engine type (engine_type): TS

max take-of weight (mtow): 15.1 kg

operating empty weight (oew): 9.1 kg

max fuel capacity (mfc): 0 Liters

engines: 6 Motor-6010s with a power of 0.482 kW

minimum speed (va_min): -18 m/s

maximum speed (va_max): 18 m/s

minimum vertical speed (vs_min): -5 m/s

maximum vertical speed (vs_max): 5 m/s

maximum altitude (h_max): 2500 m

maximum flight range (d_range_max): 10 km


Below is the LaTeX citation for the repository where the data was retrieved from.

@inproceedings{rigoni2022delivery,
  title={Delivery with UAVs: a simulated dataset via ATS},
  author={Rigoni, Giulio and Pinotti, Cristina M and Bhumika and Das, Debasis and Das, Sajal K},
  booktitle={2022 IEEE 95th Vehicular Technology Conference:(VTC2022-Spring)},
  pages={1--6},
  year={2022},
  organization={IEEE}
}
