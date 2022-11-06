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
We also use a quantum circuit to simulate the outcome of 1 ball based on the batsman and the type of bowler based on actual statistical data of the particular batsman. Quantum circuits are able to truely emulate randomness, and hence Quantum Random Number Generators can work much better than classical Pseudo-Random Number generators. 

This version of cricket makes certain assumptions:
1. Doubles and Triples are not allowed, since data to calculate the probability of doubles and triples was not available, hence only singles,fours,sixes,dots and wickets are considered.
2. Wide balls, No balls are not bowled by the bowler.
3. The stats of the players are assumed constant.

# Potential Future Uses and Enhancements
The recent covid pandemic had a heavy impact on the sports entertainment industry. Most of us were stuck at home with little to no form of sports rntertainment. Since we have been able to simulate an innings successfully with the help of this project, we can simulate entire matches based on actual statistics, and hence create a virtual cricket field. This would probably not be as amazing as a real match, but can be a potential source of entertainment for some audiences. Moreover, if we incorporate some elements of AI and ML into the project and/or constantly keep updating the data, the idea of virtual cricket matches could possibly work.

