NEURON mod files for the Ih current from the paper:
McCormick DA, Pape HC.
Properties of a hyperpolarization-activated cation current 
and its role in rhythmic oscillation in thalamic relay neurones.
J. Physiol. 1990 431:291-318.

Running the kinetics.hoc simulation file will show 
the activation steady-state, the time constant, a simple simulation
using a somatic current injection, and a family of curves
generated modeling the same protocol used in the experiments. 

Since the experimental values were not explicitly given in the paper,
the voltage dependence of the time constant for activation and
de-activation (Fig.3A) has been approximated with an arbitrary function
using a temperature of 36C, as in the experiments.
 
Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows using NEURON 5.2:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on how to use this model should be directed to
michele@pa.ibf.cnr.it
