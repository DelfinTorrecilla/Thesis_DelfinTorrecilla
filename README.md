# Master-Thesis 
Title: Entscheidungsorientiertes adaptives Testen auf Basis von Arbeitsbedingungen für arbeitsbezogene Entscheidungen
R code for the master's thesis on DEcision-Oriented aDAPTIVE (DOAT)
Used for thesis.

**Decision-Oriented Adaptive Testing Based on Working Conditions for Work-Related Decisions**

## Author

Delfin Torrecilla

University of Applied Sciences and Arts Northwestern Switzerland (FHNW)
School of Applied Psychology
2026

## Description

This repository contains the R scripts used for the data preparation, model estimation, adaptive simulations and result evaluation conducted as part of the master's thesis.

The thesis investigates the application of Decision-Oriented Adaptive Testing (DOAT) for the efficient use of work-related information. Using data from the Swiss Household Panel (SHP), the analyses examine whether future depressive symptoms and job satisfaction can be predicted based on adaptively selected working conditions.

## Repository Structure

### 01_prepareDataAndTraining.R

Preparation of the person-level dataset, implementation of inclusion and exclusion criteria, definition of predictors and outcomes, and creation of training and test datasets.

### 02_fitModels.R

Variable selection, prediction model estimation, multidimensional item response theory (MIRT) modelling, and preparation of models for adaptive testing.

### 03_predAndPerf.R

Execution of adaptive prediction simulations under varying measurement-cost conditions and evaluation of prediction performance.

### 04_ToyFileCheckOutput.R

Creation of tables and figures used in the empirical results section.

## Data

The analyses are based on data from the Swiss Household Panel (SHP). The original SHP data are not included in this repository and must be obtained separately from FORS.

## Note

Parts of the underlying adaptive testing framework were developed by Dr. Patric Wyss and collaborators.

The scripts in this repository document the application, adaptation and analysis workflow used for this master's thesis. The original adaptive testing framework is available at:

- [GitHub repository of Dr. Patric Wyss: dedaptive https://github.com/Statric/dedaptive]
- [GitHub repository of Dr. Patric Wyss: extended https://github.com/Statric/dedaptive_extended]

This repository focuses on the implementation and analyses conducted within the context of the present master's thesis.

06/2026
