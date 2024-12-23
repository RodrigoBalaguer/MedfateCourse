Course on the medfate modelling framework
================
Miquel De Cáceres, Rodrigo Balaguer-Romano

## Introduction

This repository contains a course devoted to use simulation models in
**medfate** and **medfateland** packages. The course is presented as a
set of Quarto markdown (`*.qmd`) files, which can be easily deployed
into html format.

Course sessions are updated to the most recent course edition and
package versions.

## Usage

The course slides are made using [Quarto](https://quarto.org/). This
publishing system should be installed in order to recreate and modify
course slides.

## Course sessions

Code for course sessions is in `sessions/*.qmd` files. Printed
`sessions/pdf/*.pdf` files can also be found.

1.  Introduction
    - 1.1 Introduction to process-based forest modelling
    - 1.2 Introduction to **medfate** modelling framework
2.  Forest water and energy balance
    - 2.1 Design and formulation of forest water/energy balance (theory)
    - 2.2 Running forest water energy balance (practice)
3.  Forest carbon balance and forest dynamics
    - 3.1 Design and formulation of forest carbon balance and forest
      dynamics (theory)
    - 3.2 Running forest growth and forest dynamics (practice)
4.  Large-scale features of the modelling framework
    - 4.1 Large-scale simulations using package **medfateland**
    - 4.2 Species parameter estimation using **traits4models**

## Ancillary files

These are required to recreate slide presentations from `*.qmd` files.

- `sessions/resources/scss` contains style sheets that customize slide
  appearance.
- `sessions/resources/img` contains figures in PNG, SVG or JPG format
  used in slides.

## Exercises

Exercises are included in a separate folder.

- `exercises/guidelines/Exercise_*.Rmd` are guidelines for exercises
- `exercises/solutions/Exercise_*_solution.Rmd` are solutions for
  exercises
- `exercises/StudentRdata/*.rds` are data sets required for exercises
- `exercises/R/*.R` are files to prepare data for exercises

The proposed exercises are the following:

| Exercise | Purpose |
|----|----|
| 1 | Create inputs (forest, soil, weather). |
| 2a | Run basic and advanced water balance. Learn evaluation. |
| 2b | Water balance simulations under different bulk soil water sub-models. |
| 2c | Live fuel moisture content and fire hazard simulation. |
| 3 | Run growth and forest dynamics, including management. |
| 4a | Landscape initialization with medfateland. |
| 4b | Simulate forest dynamics under a demand-based management scenario. |
| 4c | Watershed-level hydrological simulations. |

## Additional data (not in this repository)

A set of additional data sets are required to follow the course:

- Digital Elevation Model for Catalonia.
- SoilGrids layers for the Iberian Peninsula.

## Course editions

Three different course editions have been held so far:

#### First edition (June 2022)

- *Dates*: 13-16 June 2022
- *Location*: CREAF (Barcelona, Spain)
- *Organizer*: CREAF (Watering Talents program)
- *Lecturers*: Miquel De Cáceres, Víctor Granda & Aitor Améztegui

#### Second edition (December 2022)

- *Dates*: 30 November, 1-2 December 2022
- *Location*: University of Eastern Finland (Joensuu, Finland)
- *Organizer*: Blas Mola (UEF)
- *Lecturers*: Miquel De Cáceres & Víctor Granda

#### Third edition (November 2024)

- *Dates*: 19-21 November 2024
- *Location*: Universidad de Valladolid, Campus de Soria (Soria, Spain)
- *Organizer*: Francisco Mauro (UVa)
- *Lecturers*: Miquel De Cáceres & Rodrigo Balaguer-Romano
