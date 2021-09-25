# Incubyte-assessment
# Overview:
small_blue_diamondOverview:
This repository contains implementation of given assessment. The working of data pipeline is demonstarted using tools listed below. Also, a dummy database has been created to demonstarte a simple data flow in different formats from server to the local system, using country-based row filteration.

small_orange_diamondConcepts:

Data processing
Data visualization
ETL
small_orange_diamondTools & Technologies:

Python
MySQL Workbench
XAMPP Server
Pandas
Conda Environment
MySQL connector
small_blue_diamondWorking:
Firstly MySQL database has been created with specified schema.
connector.py python script, fetches database by establishing connection with MySQL server. (Note: Make sure the XAMMP server is running while executing the script)
The retrieved data is fitted into pandas dataframe for further table manipulation.
show_data() & getfile() functions are called to fetch the desired data rows and generating .csv and string file formats to specified path, accepting country names as parameters for filtering rows.
For example: get_file("IND") generates IND.csv to the specified local path. CLick here to see sample output files.
pushpinNote: This submission is sujected to further improvements.
small_orange_diamondInstallation Guide:

To install mysql.connector:
pip install mysql.connector
To install pandas:
pip install pandas
small_blue_diamondReferences:
MySQL Connector Python
Pandas docs
small_blue_diamondContribution:
Contributions are always welcomed. Make sure you read the Contribution info

small_blue_diamondScreenshots:
small_orange_diamondPyCharm console:
alt tag

small_orange_diamondMySQL Workbench:
alt tag



small_blue_diamondScreenshots:
PyCharm console:
![db2](https://user-images.githubusercontent.com/91366476/134764672-e58dd314-e031-4e03-808f-e71a1fa85f2c.png)

MySQL Workbench:
![db2](https://user-images.githubusercontent.com/91366476/134764674-843c18be-548b-416a-bb15-a797f68df217.png)





