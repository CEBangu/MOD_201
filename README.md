# Computational Neuroscience (Applied)
This repository contains work done for the applied Computational Neuroscience class at ENS (Master in Cognitive Science [Cogmaster]), in 2024. It is organized by homework topic, the chronology of which is indicated below. 
This course was focused on applied projects: simulations and mathematical modelling work. 
The outcome of each project is a multi-page report. The code used to do the simulation and generate the figures can be found in the accompanying notebooks. 

## Infectious Diseases
This project aimed to Model the spread of infectious diseases, exploring the SI model. 

## Neural Dynamics
This project explored models of the neuron and its spiking dynamics. It covers the modelling of neural spike trains, and the analysis of these simulations. It then extends this analysis to real neural data, 
namely data from a somatosensory neuron of a monkey. Finally, it considers two different models of the neuron: Leaky Integrate and Fire, and Hodgkin & Huxley. It gives an overview of these models, with some derivations, 
and examines how their dynamics evolve given different input current. 

## Neural Networks
This project explores a variety of neural networks. It first considers simple networks: the autapse neuron (a single self-connected neuron), and coupled neurons. It considers these models as dynamical systems, and explores their dynamics
from this perspective: Fixed points, 0 crossings, null-clines, and regimes. It then moves on to more complex networks. There we first consider Hoppfield Networks, and probe their storage limits. And finally, we explore a Ring Attractor network, 
using PCA to analyze its dynamics. 

## Decision Making & RNNS
This project approache Decision Making, specifically a 2 Alternative Forced Choice taks, from two perspectives. Firstly, it explores the Drift Diffusion Model, which aims to model the integration of MT neuron signals by LIP neurons. We look at how variation in parameters changes decision outcomes and reaction times. Then we design, train, and do PCA analysis on a Reccurent Neural Network trained to do the same task. **nb! the code for the RNN portion is based on a notebook by Dr. Adrian Valente**

## FORCE Learning
This project was an implementation and exploration of the paper "Generating Coherent Patterns of Activity from Chaotic Neural Networks" by David Sussillo and L.F. Abbott (2009). 
Specifically, it focuses on the notion of "First Order Reduced and Controlled Error" - FORCE - learning, recreating the network and applying this learning algorithm to recreates select figures from the paper. 
It also covers the notion of chaotic spontaneous activty, elucidates the learning and control phases, and comments on biological plausibility. 
