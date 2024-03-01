# Python using Tableau API

Welcome to the "Python using Tableau API" repository! This collection of Jupyter Notebooks provides Python scripts leveraging the Tableau API for various tasks related to Tableau Online.

## 1. Download Datasource and Capture Calculated Fields.ipynb

This notebook, `Download Datasource and Capture Calculated Fields.ipynb`, demonstrates the capability to download Tableau datasources and capture calculated fields using Python and the Tableau API. It serves as a helpful resource for extracting valuable information from Tableau datasources.

## 2. Fetch Tableau Inactive Users and Remove Them from Tableau Online Platform All at Once.ipynb

In this notebook, `Fetch Tableau Inactive Users and Remove Them from Tableau Online Platform All at Once.ipynb`, Python scripts are provided to fetch inactive users from Tableau Online and efficiently remove them in bulk. This can be useful for managing user access and optimizing Tableau Online usage.

## 3. Get View Count for All the Views for PII.ipynb

The notebook `Get View Count for All the Views for PII.ipynb` showcases Python code to retrieve the view count for all views related to Personally Identifiable Information (PII) in Tableau. This can aid in monitoring and managing views that involve sensitive data.

## 4. Read PII Fields in All Datasources Published in Tableau Online.ipynb

In this notebook, `Read PII Fields in All Datasources Published in Tableau Online.ipynb`, Python scripts are provided to read and analyze Personally Identifiable Information (PII) fields within all datasources published in Tableau Online. This helps ensure compliance with data privacy regulations.

## 5. Workbook Permissions.ipynb

The notebook `Workbook Permissions.ipynb` demonstrates Python code for managing workbook permissions in Tableau. It provides a practical guide for handling permissions efficiently using the Tableau API.

## General information about Tableau API.

Tableau actually offers two main APIs for developers to interact with its platform:

### Tableau Server REST API: 
This API allows you to programmatically manage and interact with resources on Tableau Server, Tableau Cloud sites, and Prep Conductor. It utilizes HTTP requests and responses, making it familiar for developers with web development experience.
Here are some key functionalities of the REST API:
* __Manage Tableau resources:__ Create, update, and delete workbooks, data sources, users, groups, and more.
* __Automate tasks:__ Schedule data refreshes, manage permissions, and execute other administrative tasks programmatically.
* __Integrate with other applications:__ Embed Tableau visualizations within your own custom applications or leverage Tableau data within your workflows.


### Dashboard Extensions API: 
This API empowers developers to create custom extensions that integrate directly into Tableau dashboards. These extensions can provide additional functionality or data not natively available within Tableau, enhancing user experience and data exploration capabilities.


Here are some examples of what you can achieve with Dashboard Extensions:
* __Display real-time data:__ Integrate live data feeds from external sources alongside your visualizations.
* __Perform custom calculations:__ Add new calculations or transformations not supported by Tableau directly within the dashboard.
* __Interactive elements:__ Create custom buttons, menus, or other interactive elements to enhance user interaction with the data.
For further information and getting started with Tableau's APIs, you can refer to the official documentation:

REST API: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm
Dashboard Extensions API: https://www.tableau.com/developer/tools

Feel free to explore and utilize these notebooks based on your Tableau integration needs. Happy coding!
