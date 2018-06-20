---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Catalog List Table Valued Functions By Database
  description: Retrieves the list of all table valued functions in a database from
    the Data Lake Analytics catalog.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions/{tableValuedFunctionName}:
    get:
      summary: Catalog Get Table Valued Function
      description: Retrieves the specified table valued function from the Data Lake
        Analytics catalog.
      operationId: Catalog_GetTableValuedFunction
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctionstablevaluedfunctionname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the table valued function
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table valued function
      - in: path
        name: tableValuedFunctionName
        description: The name of the tableValuedFunction
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Function
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions:
    get:
      summary: Catalog List Table Valued Functions
      description: Retrieves the list of table valued functions from the Data Lake
        Analytics catalog.
      operationId: Catalog_ListTableValuedFunctions
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table valued functions
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table valued functions
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Functions
  /catalog/usql/databases/{databaseName}/tablevaluedfunctions:
    get:
      summary: Catalog List Table Valued Functions By Database
      description: Retrieves the list of all table valued functions in a database
        from the Data Lake Analytics catalog.
      operationId: Catalog_ListTableValuedFunctionsByDatabase
      x-api-path-slug: catalogusqldatabasesdatabasenametablevaluedfunctions-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table valued functions
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Function Database
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---