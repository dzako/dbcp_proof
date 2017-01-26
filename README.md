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

where `m` is the Galerkin approximation dimension (denoted the same in the paper), `M` is the finite dimensional part of the tail (denoted the same in the paper), `dftPts` is the number of points for the discrete Fourier transform, `dftPts2` is doesn't used in the proof, `order` is the Taylor method order, `step` is the fixed time step used by the integrator, `lambda` is the :math:`\lambda`




### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)