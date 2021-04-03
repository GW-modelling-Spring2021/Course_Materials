# Getting the Run Ensemble Code working

Two code will be provided to you for the second half of the term.  Both are available in The Big Challenge directory.  The first runs and ensemble of models and gives you options to design the ensemble.  The second analyzes the results of the ensemble run.  An overview of the codes and the Challenges for the second half of the term are presented in this video: https://2018hwr528.weebly.com/run-ensemble-code.html.  You will want to set up a separate python environment to run these models because they rely on an older version of flopy (and modpath).  A very helpful document is included in the Big Challenge directory named hwr528_environments.docx!  You will also have to establish two subdirectories below where you place the run and analyze codes - one named output and the other current model output.  Finally, you will need to have the mf2005.exe and mp6.exe codes in the root directory (where you placed the two codes).


### Model Description
​The basic set scenario is as follows.  There is a modeling-friendly mountain catchment, bounded by no flow boundaries on three sides.  The downgradient boundary has been established as constant head based on the results of a larger-scale model.  There is a municipal well in the basin.  Some of the water used by the town is recharged after treatment, some is returned to the stream that runs through the basin.  Recharge is associated with the mountain block.  ET occurs in the basin floor and at a higher rate in the riparian area adjacent to the stream.  An agricultural business has proposed to add a well and irrigate crops on a new field.  You are to use the model to determine the risks of this in terms of agrochemicals reaching the stream, reduced streamflow, and additional drawdown in the town well.  The model is run as three steady state conditions: No Town and No Ag (NTNA); Yes Town and No Ag (YTNA); and Yes Town and Yes Ag (YTYA).  Some model parameters are known, others are unknown.


### The Challenges

Your only task for this challenge is to get the Run_Ensemble code up and running on your computer!  If you are successful, you will have a bunch of similarly-named files in your current model output file with a very recent creation date.  


### Correct Key Figures

There are no figures to check for this assignment.  You will know if

### What is Due? When?

Sunday night: Slack me if you are running into trouble getting things running!

Monday night: If you have had success getting the Run Ensemble code running, see if the Analyze Ensemble will also run.  Have a quick look at the plots and see which do and do not make sense to you.  To do this, you will first want to delete all of the m#### files from your output directory.  Then cut and paste all of the models from your current model output directory to the output directory.  Make sure that the two 'truth' files stay in the output directory.

Tuesday: come to class ready to walk through the Run and Analyze codes together.

Wednesday night: nothing.


Enjoy!
