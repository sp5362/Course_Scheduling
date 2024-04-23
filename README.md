Course Scheduling Problem Solver with Genetic Algorithm

Introduction

The Course Timetabling Problem (CTP) is a well-known NP-hard problem in the field of scheduling. It involves creating a course timetable while satisfying various constraints such as professor availability, course prerequisites, and student preferences. The goal is to generate a schedule that maximizes an objective function, typically minimizing conflicts and optimizing resource utilization.

This project aims to provide a solution to the CTP using Genetic Algorithm (GA), a powerful optimization technique inspired by natural selection and genetics. By evolving a population of potential timetables over multiple generations, the GA iteratively improves the solutions until satisfactory schedules are obtained.

Features

Genetic Algorithm Implementation: Utilizes a Genetic Algorithm to iteratively evolve and improve course timetables.

Customizable Parameters: Users can adjust parameters such as population size, mutation rate, and crossover methods to fine-tune the optimization process.

Constraint Satisfaction: Ensures that generated timetables adhere to constraints such as professor availability, course prerequisites, and avoiding overlapping time slots.

Objective Function Evaluation: Measures the quality of generated schedules based on predefined objectives, such as minimizing conflicts and optimizing resource utilization.

Visualization: Provides visualizations of timetables for easy interpretation and analysis.

Running Instructions

To run the Course Timetabling Problem Solver:

Setup Environment: Ensure that Python and required libraries such as NumPy, Matplotlib, and any additional dependencies are installed.

Dataset Preparation: Prepare input data including sets of courses, professors, and time slots. Data should include constraints such as professor availability and course prerequisites.

Configuration: Adjust algorithm parameters and constraints as needed in the configuration file.

Run the Solver: Execute the main script to start the optimization process using Genetic Algorithm.

Analysis: Analyze the generated timetables and performance metrics to evaluate the effectiveness of the solution.
