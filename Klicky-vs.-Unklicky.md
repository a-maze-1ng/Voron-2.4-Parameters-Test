# Klicky-vs.-Unklicky
**Comparison between Klicky and Unklicky probe**

The Unklicky probe is an exciting alternative to the Klicky probe. 
I wanted to compare the two probes with each other.

**My Voron 2.4 setup:**
* Mainboard: 2x SKR 1.4 Turbo
* Probe-port (at the Stealthburner) is connected with an BAT85 diode to the mainboard (originally an inductive probe was used).

**My test setup:**
* Klicky Probe with a genuine Omron DFH-5L (the lever was removed)
* HS-BFP (BFP-HS.stl and Heatset pin_v1.stl)

- before each PROBE_ACCURACY measurement, a QGL was performed
- PROBE_ACCURACY PROBE_SPEED=10 SAMPLES=100 SAMPLE_RETRACT_DIST=1.0

**Two scenarios where investigated:**

* bed at room temperature (22 °C).

* bet at ABS printing temperature (105 °C).
--> for this scenario the chamber,  the Klicky, and the Unklicky (HS-BFP) probe were preheated for 1 hour (chamber temp ~52 °C).

**Scenario 1 - bed at room temperature (22 °C)**

![This is an image](https://github.com/a-maze-1ng/Klicky-vs.-Unklicky/blob/main/pic/BFP_Klicky_22C_2.png)


**Scenario 2 - bed at room temperature (105 °C)**

![This is an image](https://github.com/a-maze-1ng/Klicky-vs.-Unklicky/blob/main/pic/BFP_Klicky_105C_2.png)

**Summary**

* It seems that the Klicky probe is a bit more consistant in direct comparison to the Unklicky (HS-BFP) probe. However both probes are doing a good job!
* I cant explain why the first 4 measurments at the beginning of the PROBE_ACCURACY test are so off
