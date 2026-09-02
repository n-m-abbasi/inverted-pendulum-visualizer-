# Inverted Pendulum Visualization Tool

This repository contains a standalone MATLAB visualization function for animating the inverted pendulum on a cart.  
It is used across all nonlinear, linear, and IO‑control simulations.

## Overview

The visualization tool provides a simple and clear animation of the cart and pendulum motion.  
It helps interpret simulation results and makes the system behavior easier to understand.

## Files Included

- visSim_cart_pole.m — Animation and visualization function

## Features

- Real‑time pendulum animation  
- Cart movement visualization  
- Compatible with all simulation scripts  
- Easy to integrate into other projects  

## Usage

Call the function with time, position, and angle data:

visSim_cart_pole([t, pos, ang], ref)

## Project Goals

- Provide a reusable visualization module  
- Improve interpretability of simulation results  
- Keep the visualizer independent from other projects  

## License

This project is for academic and portfolio purposes.  
Feel free to use or modify the code with proper credit.
