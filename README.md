# Adaptive Difficulty Through Bayesian Opponent Modelling in ISMCTS-Based Card Game Agents

This project explores whether adding an adaptive Bayesian opponent-modelling layer
to a standard Information Set Monte Carlo Tree Search (ISMCTS) agent changes how a
card-game opponent plays and how players perceive it. Instead of sampling hidden
game states uniformly, the agent maintains beliefs about the cards it cannot see,
updates those beliefs from the opponent's observed play, and uses them to bias its
search toward the states the evidence makes more likely. The approach is
implemented and evaluated in the card game Cambio, tested both against a baseline
ISMCTS agent and through playtesting with human participants.

## The dissertation

The complete dissertation is included in this repository:

**Gonzalez_Pablo_2507739_MSc_Dissertation.pdf**

The full LaTeX source for the dissertation is also provided, so the document can be
inspected or rebuilt in full.

## What this repository contains

In the interest of full transparency and reproducibility, this repository includes
everything needed to replicate the project and its results:

- The complete Unity project source.
- A standalone Windows build, in the `cambio_windows_build` folder.
- All raw data collected during the study (the telemetry CSV files and the
  questionnaire responses).
- The complete dissertation, both as a PDF and as its full LaTeX source.

## Analysis scripts

The statistical analysis and all graphs in the dissertation were produced in Google
Colab. The notebooks used are available here:

https://drive.google.com/drive/folders/1YvgwJNKEzCyNHrKkyMfTOF9dO_jWFIk9?usp=sharing

## Running the project

The Unity version used for development was **6000.3.10f1**. I encourage using this
version, or a closely matching one, to avoid compatibility issues when opening the
project.

To try the game without opening Unity, use the standalone build in the
`cambio_windows_build` folder. Instructions for playtesters are included inside that
folder, so it should be ready to go.

## Thanks

Thank you for taking the time to look through this project. I hope you enjoy my work.
