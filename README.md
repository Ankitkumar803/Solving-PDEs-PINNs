# Solving PDEs with Physics-Informed Neural Networks (PINNs) and Lagaris Approch

This repository contains Python code and Jupyter notebooks that demonstrate the use of Physics-Informed Neural Networks (PINNs) for solving Partial Differential Equations (PDEs).
Table of Contents

    Introduction
    Usage
    Examples
    Contributing
    License

## Introduction

Solving PDEs using traditional numerical methods can be computationally expensive, especially for high-dimensional problems. PINNs offer an alternative approach that leverages the power of neural networks to solve PDEs using limited data. In this project, we demonstrate the use of PINNs for solving a variety of PDEs.


## Usage

The code in this repository is organized into directories that correspond to different types of PDEs. To run a specific example, navigate to the relevant directory and run the corresponding Jupyter notebook.

## Examples

The following examples are included in this repository:

- 1D-Advection: Solving the 1D Advection equation using a PINN.
![image](https://user-images.githubusercontent.com/78913240/234979875-6b799c67-7985-46d6-a233-c00bb3556dbf.png)

- PDE using Lagaris Approch: we solved one PDE given in the [paper](https://arxiv.org/pdf/physics/9705023.pdf) using Lagrais Approch using one dense layer and 10 neurons.
![image](https://user-images.githubusercontent.com/78913240/234981409-70d400d5-345b-4450-bc30-9241a5ec9dfd.png)

- PDE using PINNs : We took same PDE as above and solved using PINNs (Raissi Approch) , as given the PINNs [paper](https://arxiv.org/pdf/1711.10561.pdf) 


## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
