# NXP Auriol 008 Logbook

2024.10.09

 * Create this Github repo and logbook.
 * Update fc firmware to px4 1.15.0 stable release.
Change SDLOG_PROFILE to 784 (high rate, RAW fifo hr gyro, RAW fifo hr accel).
 * Preparing the drone test stand for Auriol008
 * Acro flight mode set

 ![Aurioal attached to the test stand ](Content/Teststandfertig.jpg)
  * Create high rate logfile for vibration and gyroscope analysis
 * create three logfiles with 40hz, 36hz, and 45hz imu_gyro_cutoff frequency
 * compare influence on the oscillation of the Pitch Angular Rate
 ![Aurioal attached to the test stand ](Content/PitchAngularRate.png)