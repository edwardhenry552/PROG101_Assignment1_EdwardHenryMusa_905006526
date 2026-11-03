# PROG101 Assignment 1: Flood Early Warning Alert System

**Student:** Edward Henry Musa  
**Student ID:** 905006526  
**Course:** PROG102 Principles of Programming Logic and Design  
**University:** Limkokwing University of Creative Technology, Sierra Leone  
**Examiner:** Elijah Fullah

## Project Overview
A logical design (no source code) for a system that turns rainfall and river-level readings into flood warnings and sends them by SMS to communities at risk in Sierra Leone.

## Problem
Flood warnings in flood-prone areas such as Freetown often arrive late or do not reach people without smartphones.

## Solution
1. Input location, rainfall (mm) and river level (m)
2. Validate the readings
3. Calculate risk: Low, Medium or High
4. Generate an alert message
5. Send an SMS to every registered contact in that location
6. Log every check

## Programming Logic Used
Computational thinking, algorithm design, variables, constants, data types, decision structures, Boolean logic, repetition structures, functions, modular design and problem decomposition.

## Modules
`getInput()`, `validateData()`, `calculateRisk()`, `generateAlert()`, `sendAlert()`, `logAlert()`

## SDGs Supported
- SDG 11: Sustainable Cities and Communities
- SDG 13: Climate Action
- SDG 3: Good Health and Well-being (indirect)

## Open Source and Digital Public Good
The design is intended to be open source so local developers and councils can adapt it, and it could become a Digital Public Good by being freely usable, accessible by basic phones, and open to community contribution.

##Repository Contents
- `PROG102_Assignment1_Report 10 1.pdf`: full report
- `Algorithm.md`: step-by-step algorithm
- `pseudocode.txt`: pseudocode
- `Flowchart1.jpeg.jpeg` to `Flowchart4.jpeg.jpeg`: flowchart images
- `README.md`: this file
