# BimComplexity

## How to use

1. Download this project `Code (green button) 🠖 Download ZIP`
2. Unpack the archive and go to inside
3. Copy your the file of building information model to this folder
4. Open the file `main.py` in the Visual Studio Code
5. Replace the path to file of building information model in variable of `file`
6. Run the program

### Example output

1. The first building with **one exit** (from the zone named 'Comp 1').

<img src="https://raw.githubusercontent.com/bvchirkov/imgs/main/example-graph-one-exit.png" height="350" />

Output of the program for the first building:

```
N_w = 6 - Number of zones
N_b = 6 - Number of transits
M_w = 1 - Width graph
L_w = 6 - Depth graph
```
---------

2. The second building with **two exits** (from zones named 'Comp 1' and 'Comp 5').

The graph changed.

<img src="https://raw.githubusercontent.com/bvchirkov/imgs/main/example-graph-two-exits.png" height="350" />

Output of the program for the second building:

```
N_w = 6 - Number of zones
N_b = 7 - Number of transits
M_w = 3 - Width graph
L_w = 3 - Depth graph
```
