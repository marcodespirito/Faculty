# Faculty

This code allows you to obtain information on articles published by UCSC faculty staff (RTDAs, RTDBs, Researchers, First and Second Professors) from Scopus API.
The file "main.py" contains the code in Python language.
The "Researchers.xlsx" file contains the list of all UCSC Medical School structured staff, updated to the end of 2022, and their Scopus IDs. Some researchers have more than one associated Scopus profile, and therefore the database was checked manually. It is therefore possible that some discrepancies may exist, which please report.

To use the code you need to install the library "pybliometrics" (https://pypi.org/project/pybliometrics/) and obtain a Scopus key ().
It is alsonecessary to indicate in the main.py file the specific path to access the file "Ricercatori.xlsx" and to save the following resulting files:

1. a file in ".xlsl" format with the basic metrics of the UCSC faculty members contained in the file Researchers.xlsx
2. a file with the list of all published papers in the chosen time interval. 

It is necessary to indicate in the main.py file the specific path to access the file "Ricercatori.xlsx" and to save the two resulting files.
