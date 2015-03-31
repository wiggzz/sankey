# sankey
App for displaying CSV files as a Sankey plot.

**Usage
It allows opening CSV files of the format:

    "Item A","Item A","Item A",10.0
    "Item B","Item B","Item A",5.0
    "Item A","Item A","Item B",2.0
    "Item C","Item A","Item C",4.0

Data in the columns is independent, so if a name exists in one column it will
correspond to its own data item in that column.
