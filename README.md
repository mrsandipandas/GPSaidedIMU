# GNSS aided IMU

Here we study an inertial navigation system (INS) constructed using sensor fusion by a Kalman filter. The code provides a working system with an inertial measurement unit (IMU, here accelerometer+gyro) and GNSS (GPS). The folloing things are evaluated:
*The effects of GPS signal outage on the navigation solution
*An improved vehicle motion model (”car does not skid or fly”)
*Measurements from a speedometer to the navigation fusion filter.
and study the improved performance during GPS signal outage.

#### GNSS-receiver outage simulation

![GNSS outage at 200s](Plots/gnss_outage.jpg)
