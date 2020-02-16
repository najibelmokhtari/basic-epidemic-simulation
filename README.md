Basic epidemic simulation application
================================


What Is This?
-------------

This is a simple Python epidemic simulation used to illustrate the spread of epidemics through two factors:
- Death rate of a disease
- Contagion ratio (R0) of the disease

The script can be configured by changing the constant values corresponding to each of these factors. A pre-vaccination ratio can also be used to make a part of the population immune before the epidemic outbreak.
This is only a basic model and the purpose of this application was to illustrate basic concepts of epidemiology in a Moroccan pop science youtube video.

The episode is available here:

https://youtu.be/02WZ08QTVmg


How To Use This
---------------
- `pip install -r requirements.txt`

- Modify constants such as `PROBA_DEATH`, `CONTAGION_RATE` and `VACCINATION_RATE`.

- Run the simulation through:
`python epidemic.py`

- Press the Space bar to run or re-run the simulation
