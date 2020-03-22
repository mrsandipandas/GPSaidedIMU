# GNSS aided IMU

Here we study an inertial navigation system (INS) constructed using sensor fusion by a Kalman filter. The code provides a working system with an inertial measurement unit (IMU, here accelerometer+gyro) and GNSS (GPS). The folloing things are evaluated:
*The effects of GPS signal outage on the navigation solution
*An improved vehicle motion model (”car does not skid or fly”)
*Measurements from a speedometer to the navigation fusion filter.
and study the improved performance during GPS signal outage.

### GNSS-receiver outage simulation

#### GNSS-receiver outage at 200s
<table><tr>
<td> <img src="Plots/gnss_outage.jpg" alt="GNSS outage at 200s" style="width: 45%;"/> </td>
<td> <img src="Plots/gnss_outage_speed.jpg" alt="Speed vs Time" style="width: 45%;"/> </td>
</tr></table>

#### GNSS-receiver outage at 200s with position error

<table><tr>
<td> <img src="Plots/gnss_outage_height.jpg" alt="GNSS outage with height profile" style="width: 45%;"/> </td>
<td> <img src="Plots/gnss_outage_xy.jpg" alt="GNSS outage with X, Y profile" style="width: 45%;"/> </td>
</tr></table>
