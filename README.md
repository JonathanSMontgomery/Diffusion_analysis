The scripts given are to be used to quantify one-dimensional diffusion of particles based on already measured position vs time traces.
Traces exported from pylake jupyter notebooks will contain the track ID, time (pixels), positions (pixels), time (seconds), position (microns)
Each trace must have a unique identifier. 

The code will use the mean squared displacement as a function of lag time to estimate the diffusion coefficient, D, and the anomalous diffusion exponent, α. 

Additionally, the characteristic lifetime of traces can be determined by fitting the cumulative distribution function of the total time of each trace as a single exponential decay.
