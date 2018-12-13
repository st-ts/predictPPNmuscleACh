# Prediction modeling for PPN cholinergic (ACh) neurons, EMG, and muscle activity
## Description of the project
### Recordings 
1. Identified spike events from PPN neurons activity, these neurons are optogenetically identified as cholinergic.
2. EMG (filtered, needed to get unfitered data)
3. Raw muscle activity. Probably from movements sensor, ask Daniel.
## Info on the code
### Clustering
It looks like there is a number of different types of data, corresponding to the ones described in the paper. Ananysis of all the data is impossible because of this, so the recordings should be clustered according to their type.
There are few questions:
1. What should be the criteria for clustering?
2. What should be the number of types of the data?
There is an issue that within one recording there might be defferent types of activity. Then there should be some segmenting of data based on this, and same questions: number of type of clusters, criteria for clustering.
