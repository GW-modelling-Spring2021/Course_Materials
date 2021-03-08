# Transients

A flopy code is provided to you that simulates flow in a single layer model.  There is a well in the domain and uniformly distributed recharge.  There is no ET.  The aquifer is unconfined.  You will use this to explore the response of an aquifer to time-varying pumping.       


### Model Description
​The model that you have been provided is set up for a homogeneous medium.  The single-layer domain is 50x50 cells.  The cells are 10 m in lateral extent and 50 m in vertical. There is a well located at [0,20,20] (layer, row, column).  Recharge occurs at a rate of 5e-4 m/day.  The left and right boundaries have constant heads of 50 and 30, respectively.  The well is pumped cyclically.  Water is withdrawn at 500 m3/day for 90 days and then it is turned off for 270 days.  (Pretend that a year is 360 days long.)  The simulation is set to run for 100 years.  


### The Challenges
a) The gradient is not uniform for the initial steady state conditions - discuss the influences of recharge and the unconfined condition on this nonlinearity

b) Determine if the system has reached steady state - consider a point at the well and another at the center of the domain.  

c) Find the zone of influence of the well defined in two ways:
    - Based on the drawdown from the initial steady state to the end of simulation time (end of final no-pumping stress period).
    - Based on the drawdown from the end of the last pump-on stress period to the end of simulation time.

d) How long does it take a point at the center of the domain to reach steady state.  At that point, explain how you could divide the domain into a steady and transient part and solve each separately.

e) Find a constant pumping rate (same throughout the year) that matches the head time series at the middle of the domain.  

f) Find a constant pumping rate (same throughout the year) that matches the head time series at the well, leaving only a regular, repeating seasonal residual.  Are the two pumping rates the same?

g) Discuss the sources of water captured by this well.  If you're up for a challenge, calculate them for the final pump-on period!

h) Discuss how you would define the capture zone of the well.  How is it different than our definitions of capture zone so far in the course?


### Correct Key Figures

In my opinion, there are four key figures.

a) left panel showing the head at the well and right panel showing the head at the midpint of the domain, both as functions of time over the entire simulation.

b)  The head along a transect between the constant head boundaries through the well at three times: the initial steady state; the final pump-on period; and the final pump-off period.

c) A contour map with flow vectors at three times: the initial steady state; the final pump-on period; and the final pump-off period.

d) A contour map of the drawdown calculated for two periods: between the initial steady state and the final  simulation time and between the final pump-on period and the final pump-off period.

Decide as a class if you have found the right figures!!  I am more than happy to answer questions.  But, I want you to try to do these analyses independently first!  

Due dates are the same.  Sunday night: submit the key figures.  Monday night: submit your initial responses to The Challenge.  Tuesday night: submit your final responses to The Challenge.

Enjoy!


### Discussion Points
**In addition to The Challenge, start thinking about the following ideas**

Once again, I think that you have enough to consider from The Challenge without adding more this week!
