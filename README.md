# duplicate-detection-algorithm
This project contains a notebook with a duplicate detection algorithm that can detect duplicates for a given event log. It uses a distance function, that computes the euclidean distance between two events, using different difference functions for each attribute type(string, numerical, timestamp). For each attribute, weights can be added. 

## Setup & execution
This is tested to run on jupyter-notebook and google-colaboratory. As an example run we recommend using the Road Traffic Fine Management Process Data Set ([LINK](
https://data.4tu.nl/articles/dataset/Road_Traffic_Fine_Management_Process/12683249)). The file can be run e.g. in google collab by simply importing the notebook and loading the .xes event log in your own drive. The files should also work with other .xes event logs which are structured in the same fashion.

## context
This project is part of the lecture Challenges in BPM held at the Hasso-Plattner-Institut in Potsdam. Where @ma-ro and I investigated how duplicate events in an event log can be classified and identified.
