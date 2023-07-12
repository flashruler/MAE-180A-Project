MATLAB MAE180A - Team Project - Candelario Caldera, Charles Cody, Jay Buensuceso, and Kevin Bishara

MATLAB package required:
- Aerospace Toolbox

This MATLAB algorithm implements the Gaussian method to receive INPUT of 
- Site coordinates (latitude, local sideareal time of the telescope and site altitude) 
- Right ascension of the ascending node, declination angles
- Observation times (in Julian Day Numbers), 
- Final epoch for orbit propogation 

This aglorithm propogates the state vector into the future and OUTPUTS 
- Inertial position and velocity vectors (r,v) in the Earth-centered inertial (ECI) frame (km and km/s)
- The classical orbital elements (a, e, i, Ω, ω, M ) in km, km/s, and degrees.

Lines 37 through 40 can be uncommented if the file directory includes file name 'Iridium33Cosmos2251Collision.tle' 
This will allow algorithm to show Iridium 33's orbit along with the Earth model. 
*NOTE: These lines are currently uncommented for performance 

