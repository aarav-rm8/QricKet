# QricKet
QricKet is a Quantum Cricket Match Innings Simulator built by team |Quantelligent> for the Qiskit Fall Fest Hackathon 'Dead &amp; Alive' Organised by QCG IITR. 

# Teammates
Aarav Ratra - EPh 2Y
Nandini Gupta - EPh 2Y
Ankit Patel - EPh 2Y
Keerthi - Civil 2Y

# Instructions
1. The batting lineup has already been inserted by default, but can be modified later on.
2. All the cells are run from top to bottom (if the .ipynb file is used, else the .py file can be run directly if qiskit is installed) 

The match is simulated with the help of quantum circuits.
We use quantum circuits to choose a specific type of bowler depending on actual statistics of which type of bowlers play which matches.
We also use a quantum circuit to simulate the outcome of 1 ball based on the batsman and the type of bowler based on actual statistical data of the particular batsman

This version of cricket makes certain assumptions:
1. Doubles and Triples are not allowed, since data to calculate the probability of doubles and triples was not available, hence only singles,fours,sixes,dots and wickets are considered.
2. Wide balls, No balls are not bowled by the bowler.

