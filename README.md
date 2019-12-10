# 1976 U.S. Standard Atmosphere Model
# r/dataisbeautiful's DataViz Battle for December 2019

## Background
December 2019 Reddit's r/dataisbeautiful's DataViz Battle deals with the 1976 version of the U.S. Standard Atmosphere Model. While the dataset itself is small (about 50 datapoints total, and some say the same things but in different units.) what it describes is incredibly complex. More background research is required here to understand what claims are reasonable. 

Some isualizations are also right below the dataset provided, and it seems silly just to re-create one of those. Therefore a second dataset or model should be included here. (perhaps something about aircraft or rocket preformance, or total amounts of molecular mass in each atmospheric level?) 

## Gameplan
The ideal gas law (PV = *n*RT) states that if one knows three out of four values, one can determine the fourth value.  
Variable | Definition
---------|-----------
V|The radius of the Earth is a known value, with this information one can determine volume.
T| Temperature is a listed value on the U.S. Standard Atmosphere 1976 table.
P| The Barometric Formula will provide pressure. (This also uses information from the U.S. Standard Atmosphere 1976 table)
R| R is a constant value called the gas constant.

Entering the required values into the table provides the mols of atmosphere in each subscript. Knowing the atmospheric composition breakdown allows one to determine the mass of each element and compound in each subscipt, and those values will be entered into a table for visualization.

## Links
[r/dataisbeautiful Dataviz Battle for December 2019](https://www.reddit.com/r/dataisbeautiful/comments/e7squa/battle_dataviz_battle_for_the_month_of_december/)  
[U.S. Standard Atmosphere 1976 Version](https://en.wikipedia.org/wiki/U.S._Standard_Atmosphere#1976_version)  
[CSV for periodic table of elements](https://gist.github.com/GoodmanSciences/c2dd862cd38f21b0ad36b8f96b4bf1ee)  
[Barometric Formula](https://en.wikipedia.org/wiki/Barometric_formula)