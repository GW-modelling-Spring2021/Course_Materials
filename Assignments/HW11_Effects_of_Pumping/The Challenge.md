# Getting the Run Ensemble Code working

Two code have been provided to you for the second half of the term.  Both are available in The Big Challenge directory.  The first runs and ensemble of models and gives you options to design the ensemble.  The second analyzes the results of the ensemble run.  An overview of the codes and the Challenges for the second half of the term are presented in this video: https://2018hwr528.weebly.com/run-ensemble-code.html.  You will want to set up a separate python environment to run these models because they rely on an older version of flopy (and modpath).  A very helpful document is included in the Big Challenge directory named hwr528_environments.docx!  You will also have to establish three subdirectories below where you place the run and analyze codes - one named output, another named current model output, and a third called likelihood.  You will need to have the mf2005.exe and mp6.exe codes in the root directory (where you placed the two codes).  The steps for running the code are:

1) Get the run_ensemble code running.
2) Empty the current model output directory.
3) Delete all of the m#### files from the output directory.
4) Run run_ensemble.
5) Move the files from current output to output.
6) Run run_ensemble and extract the results that you want.
7) Copy the m### files to a 'hold' directory in case you want that model set later.
8) Set up run_ensemble to add models to your ensemble.
9) Repeat steps 2-8 to augment your ensemble.


### Model Description
​The basic set scenario is as follows.  There is a modeling-friendly mountain catchment, bounded by no flow boundaries on three sides.  The downgradient boundary has been established as constant head based on the results of a larger-scale model.  There is a municipal well in the basin.  Some of the water used by the town is recharged after treatment, some is returned to the stream that runs through the basin.  Recharge is associated with the mountain block.  ET occurs in the basin floor and at a higher rate in the riparian area adjacent to the stream.  An agricultural business has proposed to add a well and irrigate crops on a new field.  You are to use the model to determine the risks of this in terms of agrochemicals reaching the stream, reduced streamflow, and additional drawdown in the town well.  The model is run as three steady state conditions: No Town and No Ag (NTNA); Yes Town and No Ag (YTNA); and Yes Town and Yes Ag (YTYA).  Some model parameters are known, others are unknown.


### The Challenges

1) Describe the scenario being modeled based on the fixed parameter values and the base model parameter values.  WHo is the stakeholder? What is their definition of an MOC?  What are the selected 'design' options of the ag facility and the town (return flow fraction, location, field location, etc)?  Essentially, paint a picture of what is being represented by the model.

2) Construct an ensemble with 25 unique parameter sets chosen at random and generate output in current model output.

3)  Remove all of the m### models from output and move all of the models from current model output to output.  

4) Run analyze_ensemble and construct your version of the Key Figures - Ensemble 1.

5) Use the results to identify one MOC and use that to generate 10 additional similar models.

6) Move the m### model results from current model output to output.

7) Rerun analyze_ensemble and construct your version of the Key Figures - Ensemble 2.


Answer the following questions:

1) Based on your initial random ensemble, what is the most likely additional drawdown at the town well due to pumping the ag well?  How confident are you in that response - explain/defend your answer.

2) What is the likelihood that the reality (represented by the meager observed data) is best represented by an MOC?

3) What is the most likely loss in streamflow at the outflow end of the domain?  Justify your answer.

4) Is it likely that either the town or ag well could be contaminated by the ag field?  Justify your answer.

5) Make a set of plots based on ensemble 2 and discuss how each of your answers to the first four questions changed due to adding the MOC-inspired parameter sets.


### Correct Key Figures

My versions of what I consider to be the key figures are included in the key figures document under HW11 on GitHub.

### What is Due? When?

Sunday night: post your key figures.

Monday night: post your initial answers to The Challenges.

Tuesday: come to class ready to discuss how the stakeholder should view the risk of adding the ag well as proposed.

Wednesday night: post your final answers to The Challenges.


Enjoy!
