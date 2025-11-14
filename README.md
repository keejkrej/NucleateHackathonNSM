# Envue Data Analyzer - Nucleate Hackathon

A particle tracking challenge for analyzing kymograph data from microscopy experiments. This repository contains tools to estimate particle sizes from Brownian motion trajectories in noisy kymograph images.

## Challenge

Given noisy kymograph data, develop algorithms to:
- Track single and multiple particles through time
- Estimate diffusion coefficients from particle trajectories
- Calculate particle radii using the Stokes-Einstein equation

## Files

- `helpers.py` - Core functions for generating synthetic kymographs, particle tracking, and diffusion analysis
- `hackathon_demo.ipynb` - Tutorial notebook with examples and challenge datasets

## Getting Started

The demo notebook includes:
- Single particle tracking with basic algorithms
- Multi-particle scenarios requiring advanced tracking methods

Your goal: Replace the naive `find_max_subpixel` tracker with smarter algorithms to accurately estimate particle sizes!

### Installation

- Clone this repo: git clone https://github.com/Jonade80/NucleateHackathonNSM.git
- Create virtual environment: python -m venv .venv
- Install dependencies: pip install -r ./requirements.txt
- copy the challenge data (link below) into the /data folder

## Literature and links

- Website of NSM inventor Envue: https://www.envue-technologies.com/technology
- Nature Paper: https://www.nature.com/articles/s41592-022-01491-6
- Challenge data: https://nanotemper-my.sharepoint.com/:f:/g/personal/jonathan_derix_nanotempertech_com/EhjK_Zb7FTBJn2_K2SapgE0B9G3NcQJ_-elbG_3iylfElQ?e=MQR6ai 