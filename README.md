# Python-star-formation-model
Copy of a particular assignment in Python, which models several individual elements which randomly grows up to a maximum value, then visualise their quantity.

The assignment was one of three comuptational physics course assignments, with this one in particular developed with the goal of simulating star formation by modelling 10000 protostars (forming pre-ignition 'baby' stars) with random increases in mass within. The report itself was written in LaTeX Notebook, while the Python code was written for Spyder.

## Computation_Physics_coursework.pdf summary

For the sake of simplicity and brevity on a highly technical and scientific report, the following is the summary of "Computation_Physics_coursework_2.pdf":
+ A series of equation working-out towards an equation referenced as the Bondi Accretion Rate equation, which was used for modelling mass increase of protostars
+ Outlining the initial conditions of the environment which the protostars are formed, from their beginning mass to the gas cloud's density and speed of sound (the latter necessary for transferring energy between gas particles), in addition to the set timescale of the formation period - defined as 3 million years
+ A small table which outlines the environment within the gas cloud, from the dense core to the dispersed edges, as well an additional equation derivation featuring a very simple star formation modelling equation to add into the graph to contrast
+ Additional contraints and discussions on the model against reality, namely the ommission of radiation from larger stars disrupting star formation
+ Reducing the time interval when star mass is added by 3 order of magnitude greatly increases accuracy of the model towards what is known as "unity value". Any further reductions however would be too computationally expensive for diminishing accuracy.
+ Adjusting the gas density of the cloud by 3 times more or less than the original value showed its impact on star formation. In particular, reducing density to 1/3 its original value had led to very few stars exceeding the minimal mass for protostars to ignite into true stars. 
