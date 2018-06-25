---
name: Azure Data Lake Analytics
x-slug: azure-data-lake-analytics
description: The Data Lake analytics service is a new distributed analytics service
  built on Apache YARN that dynamically scales so you can focus on your business goals,
  not on distributed infrastructure. Instead of deploying, configuring and tuning
  hardware, you write queries to transform your data and extract valuable insights.
  The analytics service can handle jobs of any scale instantly by simply setting the
  dial for how much power you need. You only pay for your job when it is running making
  it cost-effective. The analytics service supports Azure Active Directory letting
  you simply manage access and roles, integrated with your on-premises identity system.
  It also includes U-SQL, a language that unifies the benefits of SQL with the expressive
  power of user code. U-SQL&rsquo;s scalable distributed runtime enables you to efficiently
  analyze data in the store and across SQL Servers in Azure, Azure SQL Database and
  Azure SQL Data Warehouse.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Value
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Data Lake Analytics API Catalog Get Table Valued Function
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the specified table valued function from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions/{tableValuedFunctionName}
  tags: Catalog Table Valued Function
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctionstablevaluedfunctionname-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Table Valued Functions
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of table valued functions from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions
  tags: Catalog Table Valued Functions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Table Valued Functions By Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all table valued functions in a database from
    the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/tablevaluedfunctions
  tags: Catalog Table Valued Function Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-openapi.md
- name: Azure Data Lake Analytics API
  x-api-slug: azure-data-lake-analytics-api
  description: The Data Lake analytics service is a new distributed analytics service
    built on Apache YARN that dynamically scales so you can focus on your business
    goals, not on distributed infrastructure. Instead of deploying, configuring and
    tuning hardware, you write queries to transform your data and extract valuable
    insights. The analytics service can handle jobs of any scale instantly by simply
    setting the dial for how much power you need. You only pay for your job when it
    is running making it cost-effective. The analytics service supports Azure Active
    Directory letting you simply manage access and roles, integrated with your on-premises
    identity system. It also includes U-SQL, a language that unifies the benefits
    of SQL with the expressive power of user code. U-SQL&rsquo;s scalable distributed
    runtime enables you to efficiently analyze data in the store and across SQL Servers
    in Azure, Azure SQL Database and Azure SQL Data Warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Value
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/azure-data-lake-analytics/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/data-lake-analytics/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/data-lake-analytics/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/data-lake-analytics/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/data-lake-analytics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---