# Airfoil Noise Predication :
NASA processed the self-noise data set used in this example. It was obtained from a series of aerodynamic and acoustic tests of two and three-dimensional airfoil blade sections conducted in an anechoic wind tunnel.

The NASA data set comprises different NACA 0012 airfoils at various wind tunnel speeds and angles of attack. The span of the airfoil and the observer position was the same in all experiments.

### Step are perform are :
#### Data set
[dataset](EDA/airfoil_self_noise.dat)
The file airfoil_self_noise.csv contains the data for this example. Here the number of variables (columns) is 6, and the number of instances (rows) is 1503.

In that way, this problem has the 6 following variables:

frequency, in Hertzs, used as input.
angle_of_attack, in degrees, used as input.
chord_length, in meters, used as input.
free_stream_velocity, in meters per second, used as input.
suction_side_displacement_thickness, in meters, used as input.
scaled_sound_pressure_level, in decibels, used as the target.


### Requirement:
1. [Github Account](https://github.com)
2. [VS code IDE](https://code.visualstudio.com/)
3. [Git cli](https://git-scm.com/downloads)

Creating conda environment
```
conda create -p venv python==3.7 -y
```

To check the coda version are working or not
```
conda --version
```
Download all the required library
```
pip install -r reqirements.txt
```