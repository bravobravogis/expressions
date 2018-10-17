# ha-expressions
Python-based ArcGIS label expressions

## Synopsis
A collection of label expressions designed to simplify routine labeling efforts, primarily displaying analytical results for environmental sampling locations. Each must be applied from within the label expressions window, by selecting the advanced checkbox and then selecting Python as the parser.

There are currently four (4) label expressions, grouped as follows:

1. Tabular Labels (Data Box)  
  +**multiple-analytes-multiple-depths**: data box with multiple analytes, multiple depths  
  +**multiple-analytes-single-date-recurring**: data box with multiple analytes, single date
  +**multiple-analytes-single-depth**: data box with multiple analytes, single depth  
  +**single-analyte-multiple-depths**: data box with single analyte, multiple depths

2. Stacked Labels (Standard)  
  +**gw-elev**: label with colored groundwater elevation beneath sample ID  

## Motivation
The ability to import a module, with a collection of custom functions, makes routine mapping activities more efficient. As with toolboxes, modules can be easily shared amongst members of an organization. Maps constructed using shared modules are consistent, and reliance upon Python will encourage further growth and learning.

With appropriate documentation and controls, modules can be updated to include routines specific to the needs of a client. Similarly, modules can include analysis and processing specific to the needs of a project. Once constructed, the module can be relied upon again and again.  

## Installation
Download the custom module and extract the .py file to the following folder:\
_C:\Users\<user name>\AppData\Roaming\ESRI\Desktop<version number>\ArcToolbox\My Toolboxes_

## Contributors
Ian Bruce (Haley & Aldrich, Inc.) is the sole contributor (as of *17 October 2018*).
