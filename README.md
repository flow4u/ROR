# ROR

ROR is a community-led project to develop an open, sustainable, usable, and unique identifier for every research organization in the world.

https://ror.org/

on myDRE.org:

*Install aiohttp via:*
1. In VM open prompt as admin
2. conda install -c conda-forge aiohttp


don't forget to open up the port
176.34.147.46:80


Possible:
34.252.177.86:80




Either notebook will create a CSV with:

['id','name', 'types', 'country', 'aliases', 'addresses', 'email_address']


**getRORdataAsync.ipynb**

This Jupyter Lab fetches from ROR database all the organisations of a **list of countries** and creates a CSV file that can be used for replacing the names of the institute with the unique ROR-ID, and vice versa. The method is async fetching, so about 2-3 times faster than method in getRORdata.ipynb



**getRORdata.ipynb**

This Jupyter Lab fetches from ROR database all the organisations of a specific country and creates a CSV file that can be used for replacing the names of the institute with the unique ROR-ID, and vice versa.