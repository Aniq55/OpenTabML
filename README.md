# OpenTabML

OpenTabML is a chrome extension which predicts the address to be opened in a tab at the current time with the help of Machine Learning algorithms.

## Requirements
* Javascript (for building the Chrome Extension)
* Python (for implementing Machine Learning algorithm)

## Chrome Extension functionalities
* It should collect data about the tabs opened in chrome, as soon as a tab is opened and a new page loads, that information is stored as: `DAY`-`TIME`-`ADDRESS`
* `DAY`: {'Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'}
* `TIME`: [0:00,24:00) with time step of 15 minutes
* `ADDRESS`: The current webpage opened in the tab

## Machine Learning Problem Statement
"We need to find an algorithm which predicts the address to be opened in a tab on a given day, at a given time of day with more than 70% accuracy."