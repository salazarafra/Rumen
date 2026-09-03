# Optimising plant fibre degradation in synthetic rumen communities
This repository contains Jupyter notebooks (accompanied by an HTML version) and data files used to produce all figures in Individuality and Selection of Microbial Communities, Chapter 4. All code is written in Julia Language.

### Data

1. <i>METACommunityPool.csv</i> contains all combinations tested along the experiment.

2. <i>YYYY.MM.DD_METACommunity_Round-N.csv</i> The communities with their average functional scores per round N, obtained from the experiments.

### Notebooks

1. <i>Re-assembly-StartingCommunities.ipynb</i> imports the data obtained from the enrichment experiments and assembles the starting communities for the experiment (Round 0), producing figures 4.2 and 4.3.

2. <i>Re-assembly-MutationSimulation.ipynb</i> imports the results from each round and creates the community combinations for the following round, given the desired criteria for community selection. 

3. <i>Degradation-plotting.ipynb</i> imports the results from each round of experiments, producing figures 4.4 to 4.7. 
