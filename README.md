# Solving PDEs with Physics-Informed Neural Networks (PINNs) and Lagaris Approch

This repository contains Python code and Jupyter notebooks that demonstrate the use of Physics-Informed Neural Networks (PINNs) for solving Partial Differential Equations (PDEs).

## Introduction

Solving PDEs using traditional numerical methods can be computationally expensive, especially for high-dimensional problems. PINNs offer an alternative approach that leverages the power of neural networks to solve PDEs using limited data. In this project, i have demonstrate the use of PINNs for solving a variety of PDEs.I also implemented a methodology similar to PINNs (Raissi) i.e Lagaris Approach. These are the papers I used methodologies from.
1. Lagaris et. al. (1997) https://arxiv.org/pdf/physics/9705023.pdf
2. Raissi et. al. (2017) https://arxiv.org/pdf/1711.10561.pdf  [**PINNs**]


## Examples

The following examples are included in this repository:

- **1D-Advection.ipynb:** Solving the 1D Advection equation using a PINN.
![image](https://user-images.githubusercontent.com/78913240/234979875-6b799c67-7985-46d6-a233-c00bb3556dbf.png)

- **PDE_using_Lagaris_Approch.ipynb:** we solved one PDE given in the [paper](https://arxiv.org/pdf/physics/9705023.pdf) using Lagrais Approch using one dense layer and 10 neurons.
![image](https://user-images.githubusercontent.com/78913240/234981409-70d400d5-345b-4450-bc30-9241a5ec9dfd.png)

- **PDE_using_PINNs.ipynb :** We took same PDE as above and solved using PINNs (Raissi Approch) , as given the PINNs [paper](https://arxiv.org/pdf/1711.10561.pdf) 

## Results
  

PDE solution using PINNs             |  PDE solution using Lagaris Approch
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/78913240/234987466-29867eb4-df2c-46c2-bbe6-e151233a4a83.png)  |  ![image](https://user-images.githubusercontent.com/78913240/234987482-0e751293-16da-47ee-8f9c-a44d09fc13a7.png)

Solarized dark             | 
:-------------------------:|
![](https://...Dark.png)  | 

## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the repository and submit a pull request.

