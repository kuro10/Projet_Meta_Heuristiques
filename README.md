# Projet Meta Heuristiques

## About the project 

This program was a project assignement of the course Meta Heuristic at INSA Toulouse. The aim of this project is to famaliarize with mmeta heuristic methods to solve the a combinatorial optimization problem. 

The precise problem was a evacuation plan in case of wildfire. "A good evacuation plan must not only minimize the evacuation time of all the population but also maximize the spatial and temporal safety between the evacuees and the actual or potential wildfire front". Read this [article](https://homepages.laas.fr/huguet/drupal/sites/homepages.laas.fr.huguet/files/u78/paper-author-GeoSafe-Workshop-2018_0.pdf) 
 for more information.
 
In this project we just focus on minmizing the total evacuation time, also respecting all the capacity constraints and due date constraints with the given instances.

## Documentation

Our report is also available on this git. Read our report for more information about the programs.

## Instruction

We show some examples for generating solutions with given instances in `Solution_Generator.ipynb`. You can also apply it for other instances and generate a correspond solution by using our functionality included in `DataProcess.py`, `LocalSearch.py`.

To verify if this solution is valid or not, you can use our functionality in `SolutionChecker.py`. Some examples are demonstrated in `wildfire_main.ipynb`.

Some solutions are generated by us and they are also available in the folder `Solutions_040619`. 

## Discussion & Extension

Our project just stops at generating a solution that verifies all capacity constraints and evacuation rate constraints, but we didn't respect the due date constraints. This problem may be upgraded in the future. 







