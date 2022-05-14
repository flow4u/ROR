# ROR

ROR is a community-led project to develop an open, sustainable, usable, and unique identifier for every research organization in the world.

https://ror.org/


**getRORdataAsync.ipynb**
This Jupyter Lab fetches from ROR database all the institutes of a **list of countries** and creates a CSV file that can be used for replacing the names of the institute with the unique ROR-ID, and vice versa. The method is async fetching, so about 2-3 times faster than method in getRORdata.ipynb


**getRORdata.ipynb**
This Jupyter Lab fetches from ROR database all the institutes of a specific country and creates a CSV file that can be used for replacing the names of the institute with the unique ROR-ID, and vice versa.