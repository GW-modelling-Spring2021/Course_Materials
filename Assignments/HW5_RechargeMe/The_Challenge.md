# Recharge Me

A flopy code is provided to you that recreates the 3D homogeneous box model with constant head boundary conditions.  The aquifer is now defined as unconfined - it was confined for the BoxModel simulations and the recharge package has been added.  You will use this to explore the impact of recharge into an unconfined aquifer.     

### Model Description
​The model that you have been provided is set up for a homogeneous medium.  There is a well located at [0,10,15], but it is not being pumped.  The recharge rate is zero.  The left and right boundaries have constant heads of 20 and 10, respectively.      

Remember that the focus of this course is primarily to use models to improve your hydrogeologic understanding.  In other words, getting the model to run correctly is step one, then The Challenge begins!

### The Challenge
For the initial boundary head values and pumping and recharge rates, compare the head versus x distance - along a transect from the middle of one constant head boundary to the other - to the results for the BoxModel.  Now reduce the boundary heads to 15 and 5.  Compare this result and explain any observed differences.  The overall gradient is the same, as is the K of the medium ... is the flow the same for both boundary conditions?  Why or why not?

Now add recharge at a constant rate of 1e-4 m/day over the entire top boundary.  Explain the head transect and boundary flows.  Is flow in this system 2D or 3D?  Is it represented as 2D or 3D?  Explain what you mean by your answers.

Now model a system with zero recharge except for a farm located in [6:10, 6:10] - in python terms.  Recharge beneath the farm is 1e-4 m/day due to excess irrigation.  First, calculate the annual excess irrigation, in meters, that has been applied to the farm.  Second, assuming that the crop is cotton, it is located in southern Arizona, and cotton is grown all year (for simplicity), calculate the total irrigation rate on the farm that would be associated with this amount of excess irrigation.  Finally, identify the area within the domain that might be subject to contamination if the recharge water was somehow tainted.    

Lastly, start the well pumping at a rate of 8 m3/day.  Using one color, identify the capture zone of the well.  Using a second color, show the area that might be contaminated by the irrigated farm fields.  Comment on the impact of the well on the pattern of potential contamination.   





### Correct Key Figures

OK, we're stepping it up another notch this week.  I am going to ask you to post what you believe to be the correct plots in Slack.  When at least three of you agree that the plots are correct, package them up and send them to me to check!  I will tell you that they are correct, or I will point out what is still incorrect, in Slack.  We will iterate until all of the plots are correct so that everyone can move forward!


### Discussion Points
**In addition to The Challenge, start thinking about the following ideas**

How can MODFLOW, which does not model unsaturated flow, represent an unconfined aquifer?

What do you think would happen (in MODFLOW) if you pumped an unconfined aquifer so hard that the water level dropped below the bottom of the aquifer?  Explain this from the point of view of what is happening in the model ... then think about what would happen in real life!

How will the steady state capture zone of a model with recharge differ from that in the same model without recharge?

What is recharge?  What does it mean to define recharge for a MODFLOW model?  How is it related to defining ET and precipitation?  Where, exactly, is the top boundary of the model?
