# WWV/H Characterization Signal Ports

This project contains ports of the code used to generate the WWV/H Characterization Signal (https://doi.org/10.5281/zenodo.5602094).

Because different languages may make use of different random number generators, the results of these ports may not be bitwise-identical to the original version. However, the noise should still have the same properties.


## Port Status

- Python: mostly complete

![Spectrogram comparison of MATLAB result and Python ported result](spectrograms.png)

(Spectrograms created with Mathematica, I haven't gotten the ones in the Python code to print as nicely yet.)
