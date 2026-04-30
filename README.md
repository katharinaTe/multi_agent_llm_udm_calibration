# multi_agent_llm_udm_calibration
multi_agent_llm_udm_calibration

# Agent-Based Calibration of a Sewer Model Using SWMM and LLMs
## Overview

This repository contains a Jupyter notebook demonstrating an agent-based approach to calibrating a sewer/detention pond model. The workflow integrates the Storm Water Management Model (SWMM) with parameter optimization and large language model (LLM)-driven agents.

The notebook explores how autonomous agents can support model calibration by interacting with simulation and evaluation tools.

## Authors
This code has been created by Katharina Teuber at Jade Hochschule (University of Applied Sciences)
## Contents
.
├── sewer_calibration_agentic_generic_detention_pond-WST.ipynb
├── README.md

## Methodology

The workflow consists of the following steps:

### Model Setup
A SWMM model is loaded and configured programmatically.
Synthetic Observations
Simulation outputs are used to generate synthetic observation data for calibration.
Parameter Calibration
The SPOTPY library is used to perform parameter sampling and optimization based on an objective function.
Agent-Based Interaction
LLM-based agents interact with tools to:
run simulations
adjust model parameters
evaluate calibration performance
Requirements

### The following Python packages are required:

numpy
pandas
matplotlib
spotpy
swmm-api
langchain
langchain-core
langchain-ollama

A working SWMM installation is also required.

### License
This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

You are free to use, share, and adapt this material for non-commercial purposes, provided that appropriate credit is given.

For commercial use, please contact the author.
