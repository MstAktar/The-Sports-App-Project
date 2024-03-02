# The Sports App Project - Physics final project (ID00CS50-3003)

**Name:** Mst Airen Aktar 
**Email:** t2akms@students.oamk.fi

## Calculation Results:
- Average speed is  1.6782391458590495 m/s
- Total distance traveled is  215.14092455483328 m
- The total acceleration in x direction is  9603.94380273996 m/s^2
- The total acceleration in y direction is  13128.732843633741 m/s^2
- The total acceleration in z direction is  25602.166787147522 m/s^2
- Number of steps (calculated from z component): 255.5


## Questions:
**Q1:** Does the acceleration calculated from the speed match the observed acceleration? What differences do you notice? What could be their cause?  
**Q2:** Is the number of steps logical?

## Observations:
From the provided data and calculations, it seems that there are some discrepancies between the observed acceleration and the calculated acceleration from speed.

- The calculated acceleration from speed does not match the observed acceleration entirely. This mismatch can arise due to various factors like noise in accelerometer data and errors in integration.

- The number of steps calculated from the z-component of acceleration might not be entirely logical. While acceleration in the z-direction can correspond to steps during walking (as the phone moves up and down with each step), it's unlikely that each peak or trough in the z-component corresponds to a single step. Factors such as irregular gait, variations in walking speed, and other movements could influence the z-component of acceleration, leading to an inaccurate step count.
