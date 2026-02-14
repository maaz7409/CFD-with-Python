# Computational Fluid Dynamics (CFD) with Python

Goal of this Repository is to illustrate how CFD can be done with Python from scratch.


## Installing Modules 

Run this (if you do not have libraries installed)
```
pip install -r requirements.txt
```

## Explanation and Codes

Explanation behind the implementation is provided in Explanation.ipynb, with code being in CFD.ipynb

## Expected Time and Output

The code on average takes 2 hours to run on 13th Gen Intel(R) Core(TM) i7-13620H CPU (CPU Boost Disabled).
Code also uses numba to speed up simulation.


On Running the code, it saves images of velocity and voriticty frames in /results folder, along with video of simulation as .mp4 file and a dataset for further surrogate modelling with PINN (as .npz file)

The code for Surrogate Modelling will be shared soon as a different repository.

Check Result section in Explanation.ipynb to learn more about output and results.

