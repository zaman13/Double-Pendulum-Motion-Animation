# Double-Pendulum-Motion-Animation

<p float="left">
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Julia%20Code"> <img src="https://img.shields.io/badge/Language-Julia-blue" alt="alt text"> </a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Python%20Code"> <img src="https://img.shields.io/badge/Language-Python-blue" alt="alt text"> </a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/LICENSE"> <img src="https://img.shields.io/badge/license-MIT-green" alt="alt text"></a>
<a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation"> <img src="https://img.shields.io/badge/version-1.2-red" alt="alt text"> </a>
</p>

<p>
<img align = "right" src="https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/sample_output_2.gif" alt="alt text" height="180">
Animation of the chaotic motion a double-pendulum using Julia and Python. The julia version is implemented in a Jupyter notebook environment whereas the python version is a conventional script. Double pendulums of arbitrary lengths, masses, initial positions, and the initial velocities can be simulated using this code. Both versions of the code allow the animation to be saved in either mp4 or gif format. 
</p>

## Julia version <a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Julia%20Code"> <img src="https://img.shields.io/badge/Language-Julia-blue" alt="alt text"> </a>
The code can save the animation as a gif file. It can also playback the video in Jupyter notebook environment. The animation is recorded at equal time steps to preserve relative velocity of the pendulums in the video.

## Python version <a href = "https://github.com/zaman13/Double-Pendulum-Motion-Animation/tree/master/Python%20Code"> <img src="https://img.shields.io/badge/Language-Python-blue" alt="alt text"> </a>
The animation is done using FuncAnimation() of matplotlib. The code can save the animation as a mp4 file. The python script was tested in spyder environment. Plotting in external window should be enabled to view the animation.



## Package requirements for Julia version
 1. Plots
 2. Differential Equations
 3. Direckx

## Package requirements for Python version
 1. numpy
 2. scipy.integrate (odeint)
 3. pylab, matplotlib (animation) 
 4. imagemagick (to save animation as a gif file)


## Use
The mass and length of the pendulums, gravitational acceleration constant, the initial conditions and the simulaiton duration are defined at the beginning of the code. Different cases can be simulated by changing these parameters. 




## Sample output
Double pendulum system animation. The left animation is from the julia code with m<sub>1</sub> = m<sub>2</sub> = 1kg, L<sub>1</sub> = L<sub>2</sub> = 1m, initial conditions: θ<sub>1</sub> = 5π/8, θ<sub>2</sub> = 5π/9, ω<sub>1</sub> = 0, ω<sub>2</sub> = 0. The right animation is from the python code with m<sub>1</sub> = 2kg, m<sub>2</sub> = 1kg, L<sub>1</sub> =1.4m,  L<sub>2</sub> = 1m, initial conditions: θ<sub>1</sub> = 5π/11, θ<sub>2</sub> = 5π/9, ω<sub>1</sub> = 0, ω<sub>2</sub> = 0. 


Here, θ<sub>1</sub> and θ<sub>2</sub> are the initial angular positions, and, ω<sub>1</sub> and ω<sub>2</sub> are initial angular velocities in SI units.

<p>
<img src="https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/sample_output.gif" alt="alt text" height="250">
<img src="https://github.com/zaman13/Double-Pendulum-Motion-Animation/blob/master/sample_output_2.gif" alt="alt text" height="290">
</p>


## References
1. http://sophia.dtp.fmph.uniba.sk/~kovacik/doublePendulum.pdf
2. http://www.phys.lsu.edu/faculty/gonzalez/Teaching/Phys7221/DoublePendulum.pdf
3. http://louistiao.me/posts/notebooks/save-matplotlib-animations-as-gifs/

