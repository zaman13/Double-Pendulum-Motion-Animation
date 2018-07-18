# Double-Pendulum-Motion-Animation
Animation of the motion a double-pendulum using Julia.

The code saves the animation as a gif file. It can also playback the video in Jupyter notebook environment. The animation is recorded at equal time steps to preserve relative velocity of the pendulums in the video.

## References
1. http://sophia.dtp.fmph.uniba.sk/~kovacik/doublePendulum.pdf
2. http://www.phys.lsu.edu/faculty/gonzalez/Teaching/Phys7221/DoublePendulum.pdf


## Package requirements
 1. Plots
 2. Differential Equations
 3. Direckx

## Use
The mass and length of the pendulums, gravitational acceleration constant, the initial conditions and the simulaiton duration are defined at the beginning of the code. Different cases can be simulated by changing these parameters. 




## Sample output
Double pendulum system with m<sub>1</sub> = m<sub>2</sub> = 1kg, L<sub>1</sub> = L<sub>2</sub> = 1m. Initial conditions θ<sub>1</sub> = 5π/8, θ<sub>2</sub> = 5π/9, ω<sub>1</sub> = 0, ω<sub>2</sub> = 0. Here, θ<sub>1</sub> and θ<sub>2</sub> are the initial angular positions, and, ω<sub>1</sub> and ω<sub>2</sub> are initial angular velocities in SI units.


<img src="https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/sample_output.gif" alt="alt text" width="300">
