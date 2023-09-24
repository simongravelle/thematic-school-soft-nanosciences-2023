# Thematic school on soft nanosciences

<a href="">
  <img src="https://raw.githubusercontent.com/simongravelle/thematic-school-soft-nanosciences-2023/main/molecular-dynamics-scripts/water-ethanol/image/figure1-dark.png" align="right" width="30%"/>
</a>

25 septembre 2023, UGA, Grenoble

## 1 - Install LAMMPS

Install the open source code LAMMPS following the instructions of 
[this page](https://docs.lammps.org/Install.html). On linux system,
the following command usually does the trick:

```bash
sudo apt-get install lammps
```

## 2 - Clone this repository

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

Here, the input.lammps file contains all the commands that control the simulation. Each command is described in depth on the [LAMMPS website](https://docs.lammps.org/Manual.html). 

If you are interested in learning molecular simulations from scratch, you can find [beginners tutorials here](https://lammpstutorials.github.io/).

## 4 - Visualise the trajectory

Each simulation will produce a trajectory file named "dump.lammpstrj", containing the positions of the molecules over time. You can open it using [VMD](https://www.ks.uiuc.edu/Research/vmd/),

```bash
vmd dump.lammpstrj
```





