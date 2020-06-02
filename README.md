# Dynamic Occupancy Grid Maps (DOGMas)

Implementation of the algorithm proposed in:

D. Nuss, S. Reuter, M. Thom, T. Yuan, G. Krehl, M. Maile, A. Gern, and K. Dietmayer. A
random finite set approach for dynamic occupancy grid maps with real-time application. arXiv,
abs/1605.02406, 2016.

The code demonstrates the particle filter processing of occupancy grids into DOGMas.

Run the `run_all.sh` script from `dogma/`, which contains all the necessary commands in sequence. This sequence of commands generates a simple grid example from simulation and runs the particle filter velocity estimation.

The code is written in Python 2.7 with the following dependencies summarized in `requirements.txt`

