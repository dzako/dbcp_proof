# README #

This repository contains source files and numerical data of the computer assisted proof of a heteroclinic 
connection in diblock copolymer model (DBCP) as presented in the paper entitled 

*"Computer-assisted proof of heteroclinic connections in the one-dimensional Ohta-Kawasaki model"*

by Jacek Cyranka and Thomas Wanner

the file `config.in` contains the global configuration of the algorithm.. For the example used in the paper we have

    m=15
    M=75
    dftPts=32
    dftPts2=400
    order=16
    step=0.002
    lambda=4
    sigma=0.405284735
    piOverL=0.5

where `m` is the Galerkin approximation dimension (denoted the same in the paper), `M` is the finite dimensional part of the tail (denoted the same in the paper), `dftPts` is the number of points for the discrete Fourier transform (it has to be >2m for the considered equation), `dftPts2` is doesn't used in the proof, `order` is the Taylor method order, `step` is the fixed time step used by the integrator, `lambda` is the `\lambda = 1/\epsilon^2` parameter in the diblock copolymer equation (see the referenced paper for the detailed form). `sigma` is the `\sigma` parameter in the equation (`\sigma=0` is the Cahn-Hillard case).
`piOverL` is the value of `\pi` divided by the length of the domain `L`.






### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)