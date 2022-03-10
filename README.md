# Calling Databricks SQL in an Azure Function

This is a sample project demonstrating how to:

* configure Azure Function app settings to set up Databricks SQL endpoint connection
* install and use Databricks' SQL Connector for Python
* pass a parameter to an Azure Function and then to a query executed by the SQL Connector

# Requirements

1. Add three app settings to your Function App: DATABRICKS_HOSTNAME, DATABRICKS_HTTP_PATH, and DATABRICKS_ACCESS_TOKEN. Fill these in with values from your SQL Endpoint you wish to connect to.

This has been tested on Azure Functions Runtime 4.x and Python 3.8, but as this is a simple example, it should be compatible back to 2.x/3.6.
