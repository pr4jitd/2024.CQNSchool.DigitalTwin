# CQN Winter School - Exploring and Designing Quantum Networks via Digital Twin Simulations (level 2)

## Instructors: Dirk Englund<sup>1</sup>, Prajit Dhara<sup>2</sup>, and Hyeongrak "Chuck" Choi<sup>1</sup>
<sup>1</sup> ![MIT](https://img.shields.io/badge/RLE-MIT-violet),
<sup>2</sup> ![Univ. Arizona](https://img.shields.io/badge/Univ.-Arizona-violet), 


The course aims to provide training for quantum network simulation and modeling, emphasizing starting from first principles to model elementary quantum links for realistic deployed quantum networks. Essential topics in quantum information and quantum optics will also be surveyed.

## Curriculum

1. Dirk Englund: Introduction to Quantum Network Simulations
2. Prajit Dhara: Midpoint Source Protocol Simulation
3. Hyeongrak "Chuck" Choi:  QuREBB: Quantum Remote Entanglement Building Block Simulations

## Running Notebooks
[![Pipenv](https://img.shields.io/badge/pipenv-locked-brightgreen)](https://pipenv.pypa.io/)

The virtual environment in this QuREBB repository is managed by [pipenv](https://pipenv.pypa.io/en/latest/).
To install pipenv you can use pip:

```bash
$ pip install pipenv --user
```

Using pipenv you then want to install all the dependencies of the repository by syncing with pipenv.
First navigate in the terminal to the QuREBB folder. Then run:

```bash
$ pipenv sync
```

Once you are synced you can go into a shell of this virtual enviroment (again while being in the QuREBB folder):

```bash
$ pipenv shell
```

The commands you now run are within this virtual enviroment, e.g.:

```bash
$ jupyter lab
```

## License
[![license](https://img.shields.io/badge/license-New%20BSD-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

Our lecture note is licensed under the BSD 3-Clause License, which allows for the free use, modification, and distribution of software as long as certain conditions are met.

See the LICENSE.txt file for more details.

## Citing Relevant Works
![Paper Availability](https://img.shields.io/badge/paper-available-orange)

If you use ZALM in your resarch, please cite the original [ZALM paper](https://arxiv.org/abs/2206.03670) and [Cascaded Source paper](https://arxiv.org/abs/2107.14360)
If you use QuREBB in your research, please cite the original [QuREBB paper](https://arxiv.org/abs/2310.19878) and github repository [Repository](https://github.com/QuTech-Delft/QuREBB)
