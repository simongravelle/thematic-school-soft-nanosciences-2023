# Thematic school on soft nanosciences

25 septembre 2023, Grenoble

## 1 - Install LAMMPS

Install the open source code LAMMPS following the instructions of 
[this page](https://docs.lammps.org/Install.html). On linux system,
the following command usually does the trick:

```bash
sudo apt-get install lammps
```

## 2 - Close this repository

Download the content of this repository, or clone it 
using 

```bash
https://github.com/simongravelle/thematic-school-soft-nanosciences-2023.git
```

## 3 - Run a simulation

Choosing any of the 3 simulations located in the [molecular-dynamics-scripts/](molecular-dynamics-scripts/) folder, run lammps by executing
the input script:

```bash
lmp -in input.lammps
```

Here the input.lammps file contains all the commands that control the simulation. Each command is describe in depht on the [LAMMPS website](https://docs.lammps.org/Manual.html). 

If you are interested to learn molecular simulations from scratch, you can find [beginners tutorials here](https://lammpstutorials.github.io/).





