Repository SOEN6611_TeamS contains Projects folder inside it. This folder contains all the Projects inside it.
This folder contains three projects: commons-collections, commons-configuration, commons-io and one configuration file.
The configuration file contains the plugins used for configuring jacoco and pitest in IntelliJ IDE.
Each of the commons folder contains Data collection folder inside it.
Now inside the commons-collections folder we have:
- bugs: It contains the excel sheets with all the bugs retrieved from Issue tracking system
- code_churn_defect_density: It contains an excel file with defect density and code churn calculated.
- jacoco: It contains the reports retrieved for branch and statement in csv, html, xml form for each of the version we have used in this project.
- pitest: It contains pit reports for all the versions of the project.

Similar structure is followed by commons-configuration and commons-io folders.


2. Instructions to run the CLOC tools –
•	Install the latest version of Node.js from https://nodejs.org/en
•	Download the CLOC python script by using command -  npm install -g cloc
•	CLOC is tool written in python. 
•	To run this tool the system should be python enabled
•	To make the system python enabled we need to install two python development kits.
•	Install “ActiveState Perl” – to recognize the perl.
•	Installation of Strawberry Perl – to make CLOC executable
•	This will make the CLOC executable.
3. Commands to obtain the results –
1. To get the total lines of code – cloc path\projectname
2. To get the code churn between different versions of project – cloc  - -diff path\Project_Name_Version_A path \Project_Name_Version_B

4. Instructions to run the SciPy script for spearman correlation –
•	Install the python IDE - Idle (Python GUI)
•	Download the python script file get-pip.py to install the pip library
•	This script will be used to run the scipy script which is used to run the spearman script
Commands to run the SciPy script –
•	Path\python get-pip.py
•	Path\python -m pip install scipy
To obtain the spearman coefficient results –
•	Stats.spearmanr([‘comma_separated_values_of_varibale_1’],[comma_separated_values_of_varibale_2])

