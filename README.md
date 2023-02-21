# Faculty

This code allows you to obtain information on articles published by UCSC faculty staff (RTDAs, RTDBs, Researchers, First and Second Professors) from Scopus API.
The file "main.py" contains the code in Python language.
The "Researchers.xlsx" file contains the list of all UCSC Medical School structured staff, updated to the end of 2022, and their Scopus IDs. Some researchers have more than one associated Scopus profile, and therefore the database was checked manually. It is therefore possible that some discrepancies may exist, which please report.

To use the code you need to install the "pybliometrics" library (https://pypi.org/project/pybliometrics/) and obtain a Scopus key ().

The main.py code creates for the researchers contained in the file "Researchers.xlsx" :
1. a file in ".xlsl" format with the basic metrics of the UCSC faculty members contained in the file Researchers.xlsx
2. a file with the list of all published articles. 

It is necessary to indicate in the main.py file the specific path to access the file Ricercatori.xlsx and to save the two resulting files.
