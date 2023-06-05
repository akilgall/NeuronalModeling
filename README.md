# NeuronalModeling
A framework illustrating some neuronal modeling of single particles as well as machine learning aspects to track segmentation.

SimulationPars_To_ClassifiedTracks illustrates turning a track simulation into segmented tracklets using a simple LSTM model trained on the simulated data.
createNeuronalProcessesWithTraces illustrates creating a map of processes radii from a whole-cell RoI.  It shows a simplified way of simulating tracks over a set of approximated 3D cylinders defined from the RoI.
