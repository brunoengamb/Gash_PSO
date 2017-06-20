# Gash_PSO
R code and base data from canopy rainfall interception experiment from riparian forest

This code and database are part of the PhD Thesis in Environmental Technology and Water Resources by Bruno Esteves Távora. The research was developed in the Department of Civil and Environmental Engineering of the University of Brasília with the financial support of the Brazilian agency CNPq.
The code was developed in R, using RStudio Version 0.99.903.

1. To acess the rainfall interception simulation you must first connect to the folder containing the experimental data.
ex: setwd("C:/Users/~/Base Data")
2. The input parameters of the model are: free precipitation coefficient (p), precipitation evaporation rate (ER), canopy saturation sheet (Pg), index that identifies the event file .csv (event_number).
ex: Gash(p, ER, Pg, event_number)
3. Each event has a set of optimal parameters. Some are presented here:
ex: Event 1	-  Gash(p= 0.16, ER= 0.25, Pg= 2.93, event_number = 1)
    Event 2	-  Gash(p= 0.18, ER= 0.27, Pg= 1.79, event_number = 2)
    Event 3	-  Gash(p= 0.16, ER= 0.16, Pg= 2.86, event_number = 3)
    Event 4	-  Gash(p= 0.16, ER= 0.48, Pg= 1.63, event_number = 4)
4. Results consists of two graphs one of observed and another of the simulated net precipitation.
