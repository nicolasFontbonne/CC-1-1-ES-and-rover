# CC-1-1-ES-and-rover

This repository hold the code for the paper Adaptive Team Cooperative Co-Evolution for a Multi-Rover Distribution Problem.

## Installation

Install pytorch, tqdm, numpy and jupyter notebooks.

```bash
conda install torch numpy matplotlib jupyter
```

## Reproduce simulations

Batch of experiment can be launched using the `launch_exp.py` file. You must provide a list of parmeters file as a `.json` file. Exemple of such file is provided in the `exp_list` folder.

Launching a set of run can then be performed as follow:
```bash
python3 launch_exp.py exp_list/exp.json
```

## Run analysis

The result are stored in the `logs` folder and are composed of a `info.json` file that hold all the parameters of the experiments, and a `out.npz` that hold the logs.


## Cite as
