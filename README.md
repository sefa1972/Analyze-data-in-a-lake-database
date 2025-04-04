Analysis of Lake Database with Azure Synapse Analytics

This project focuses on creating a lake database using Azure Synapse Analytics, defining table schemas, loading data, and querying with SQL. Azure Synapse Analytics provides a scalable and flexible solution for big data analytics, combining both relational database capabilities and data lake flexibility.

Project Steps

1. Provisioning Azure Synapse Analytics Workspace

I used a PowerShell script and an ARM template to create an Azure Synapse Analytics workspace.

2. Modifying Container Permissions

I assigned appropriate access permissions to the data lake containers and made the necessary authorizations.

3. Creating a Lake Database

I created a lake database, defined a relational schema, and integrated it into the data lake file store.

4. Creating Tables and Defining Schemas

I created tables within the data lake and defined their schemas.

5. Loading Data

I loaded data into the storage paths of the defined tables.

6. Creating a Table from a Database Template

I used an existing database template to create new tables.

7. Querying with SQL

I queried tables in the data lake using SQL within Azure Synapse Analytics.

8. Adding Data Using Spark

I performed data manipulation and insertion using Synapse Spark.

Technologies Used

Azure Synapse Analytics

Azure Data Lake Storage

SQL (T-SQL)

Apache Spark

PowerShell

ARM Templates

How to Use?

Create an Azure Synapse Analytics workspace.

Configure data lake container permissions.

Create a lake database and define its schema.

Load data into the appropriate paths.

Perform SQL queries and analyze data using Spark.

