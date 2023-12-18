# PGA Tour Analysis

## Overview

This repository contains an analysis of PGA tour data spanning the 2015-2022 seasons. The dataset provides insights into player performance, strokes gained metrics, and various aspects of the game.

## Background Information

The PGA tour is renowned as the premier professional golf tour, attracting elite players. The dataset includes information on player names, tournament details, course names, purse sizes, and player performance metrics such as strokes gained in different aspects of the game.

## Objective

The primary goal is to analyze player performance on the PGA tour and answer key questions related to strokes gained, purse sizes, seasons, and scoring categories. The analysis aims to provide insights into the factors influencing player success.

## Data Features

- **Player_inital_last**: Player name in the format (first name initial).(surname)
- **tournamentID**: Identifier for the tournament
- **hole_par**: Total par of the holes played
- **strokes**: Strokes made by the player
- ... (other variables not used in the analysis)

## Understanding Golf/Data/Problem

A basic understanding of golf is necessary to interpret the strokes gained metrics, scoring system, and tournament format. The README provides a brief overview of scoring in golf and explains the strokes gained metric used in the analysis.

## Data Cleaning

The dataset was transformed to focus on relevant data, removing unnecessary attributes. Cleaning involved handling missing values and outliers to ensure data integrity.

## Initial Questions Explored

### Q1: Is Strokes Gained a Good Metric for Evaluating Performance?

A scatter plot compares total strokes gained with finishing performance, suggesting that better finishing positions tend to gain more strokes.

### Q2: Does a larger purse size result in better player performance?

A bar plot investigates the relationship between purse size and average total strokes gained, revealing a drop in performance in the highest stake tournaments.

### Q3: Which seasons did players score the best?

A bar plot compares mean scores by season, identifying variations in player performance across seasons.

### Q4: What is the proportion of players who scored under par, even par, and over par?

A pie/donut chart visualizes the proportion of players in each scoring category across seasons.

## Further Questions Explored

### FQ1: Which is the most important part of the game to gain strokes to win tournaments?

A boxplot explores strokes gained by different aspects of the game for 1st place finishers, revealing "tee to green" as the most crucial aspect.

### FQ2: How do strokes gained in different shot categories compare between tournaments with the highest purse range and tournaments with other purse ranges?

A dodged bar plot compares strokes gained in different shot categories between high purse tournaments and others, highlighting a significant decrease in "tee to green" performance in high-stake tournaments.

## Reflection

The project successfully explores the PGA tour dataset, revealing insights into player performance and factors influencing success. While strokes gained proves to be a valuable metric, limitations include the absence of specific golf course data. The visualizations effectively communicate findings, ensuring clarity and expressiveness.

For detailed analysis and visualizations, refer to the Jupyter notebook in this repository.
```