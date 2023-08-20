# ALP-SMR
Aircraft Landing Problem - Static case with multi-runways

# Introduction 
This project was delivered for the course " Analytical decision support systems" of the Master in Data Science and Engineering.
It was a group project, which required from us to solve a given problem using MILP and constrain programming.

The chosen topic “[Aircraft landing](http://people.brunel.ac.uk/~mastjjb/jeb/orlib/airlandinfo.html)” consists in deciding on assigning a landing sequence to aircrafts, in one or more runways, meeting the mandatory predefined separation times for each type of aircraft. This approach observed a static sequence Aircraft landing problem.
Each landing sequence in a determined runway – or multiple runways –, lies within a predefined time slot, ensuring the most effective use of the available runways allowing the minimization of costs involved when deviation from the target landing time occurs.

# Solution
To reach optimal solutions to the problem the DOCplex mp and cp solvers were used. Regarding multiple runaways sequence landing problem, using CP model, was developed an original approach that was proven very efficient considering the obtained feasible results.

# Authors
[João Pedro Pêgo](up199502401@up.pt), [Pedro Gouveia](202100813@up.pt), [Ricardo Vilaça] (201308080@up.pt)
