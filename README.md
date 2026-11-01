# GradePath

A Java command-line application that helps students calculate their grades, explore hypothetical outcomes, and determine what scores they need to achieve their academic goals.

## The Problem

College students often struggle to calculate their current grades and determine what scores they need on future assignments or exams to achieve their desired final grades, especially when courses use weighted grading categories. GradePath aims to simplify these calculations and help students make informed academic decisions.

## MVP Features (Version 1.0)

GradePath will provide the following core functionality:

- Enter grading components and their percentage weights.
- Record completed assessment scores and identify remaining assessments.
- Calculate current weighted grades.
- Calculate projected final grades using hypothetical scores.
- Determine the average score required on remaining assessments to achieve a desired final grade, including identifying unattainable targets.

## Tech Stack

- **Programming Language:** Java, Bash + RegEx.
- **Development Environment:** Visual Studio Code, IntelliJ IDEA, Ed Workspaces.
- **User Interface:** Basic menu with possible dropdowns.
- **Libraries:** Java's built-in classes and libraries.
- **Data Storage:** In-memory using Java objects.
- **External Data Sources / APIs:** None; all input is done manually by the user.
- **Version Control:** Git and GitHub for tracking progress and maintaining the repository.

## System Design

The application will collect grading information through a menu-based interface, validate the entered weights, and allow users to select from three calculation options: current grade, projected final grade, or required future average.

The system diagram and Eisenhower Matrix are located in the docs/ directory.

## Future Plans (Version 2.0+)

- Save and load grading information using local files.
- Support multiple courses.
- Track individual assignments within grading categories.
- Support customizable letter-grade thresholds.

## Setup and Usage

GradePath is currently in the planning stage. Installation instructions, compilation commands, and usage examples will be added as development progresses.

The completed application will provide a menu-based interface for entering grading information and performing calculations.

## Development

Development will follow incremental milestones, with separate Git commits for repository setup, user input, grade calculations, hypothetical predictions, target-grade calculations, and testing.

## Author

Surjosnato Dhar

Purdue University — Computer Science
