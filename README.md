# Eye-Head-Gaze_Spiking_Neural_Network_Model_Superior_Colliculus
Alizadeh A, Van Opstal AJ. Dynamic control of eye-head gaze shifts by a spiking neural network model of the superior colliculus. Front Comput Neurosci. 2022 Nov 17;16:1040646. doi: 10.3389/fncom.2022.1040646. PMID: 36465967; PMCID: PMC9714624.

### This repo records:
1. SNN_SC which is a python code for constructing a two-layer spiking neural network model of superior colliculus with a cortical input. Superior colliculus encodes the instantaneous trajectory of a desired straight gaze path 
2. HorGaze.m which models Horizontal gaze shifts to a single target with varying initial eye and head positions

* Neurons and the spiking neural network were simulated by Brian simulator. Brian is a python programming language. Brian 2 download link: https://brian2.readthedocs.io/en/stable/introduction/install.html
* Neurons are Adex model (see SNN_SC)
* Connectivity between neurons are Mexican hat type (see SNN_SC) with a local excitatory and global inhibitory connectivity.
* Parameters were optimized by genetic algorithm and brute force search (see SNN_SC.py)

