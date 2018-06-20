---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Keyvaluemaps Map Name Entries Entry Name
  description: Gets a specific entry details.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/keyvaluemaps:
    get:
      summary: Get Organizations Name Keyvaluemaps
      description: Returns an expanded view of all Maps scoped by organization, environment
        or API.
      operationId: getOrganizationsOrgNameKeyvaluemaps
      x-api-path-slug: organizationsorg-namekeyvaluemaps-get
      parameters:
      - in: query
        name: expand
        description: Set expand value to true
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Keyvaluemaps
    post:
      summary: Post Organizations Name Keyvaluemaps
      description: Creates a KeyValueMap.
      operationId: postOrganizationsOrgNameKeyvaluemaps
      x-api-path-slug: organizationsorg-namekeyvaluemaps-post
      parameters:
      - in: query
        name: Content-Type
        description: Specify the Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Keyvaluemaps
  /organizations/{org_name}/keyvaluemaps/{map_name}/entries/{entry_name}:
    get:
      summary: Get Organizations Name Keyvaluemaps Map Name Entries Entry Name
      description: Gets a specific entry details.
      operationId: getOrganizationsOrgNameKeyvaluemapsMapNameEntriesEntryName
      x-api-path-slug: organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-get
      parameters:
      - in: path
        name: entry_name
        description: Mention the entry name
      - in: path
        name: map_name
        description: Mention the map name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Keyvaluemaps
      - Map
      - Entries
      - Entry
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