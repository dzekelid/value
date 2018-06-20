---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 1
info:
  title: Apigee Edge
  description: restful-management-api-to-create-configure-and-manage-api-proxies-and-api-products-create-and-manage-apps-and-app-developers-and-more-
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
    delete:
      summary: Delete Organizations Name Keyvaluemaps Map Name Entries Entry Name
      description: Deletes a single entry by name.
      operationId: deleteOrganizationsOrgNameKeyvaluemapsMapNameEntriesEntryName
      x-api-path-slug: organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-delete
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
  /organizations/{org_name}/keyvaluemaps/{map_name}:
    get:
      summary: Get Organizations Name Keyvaluemaps Map Name
      description: Gets a KeyValueMap by name, along with associated entries.
      operationId: getOrganizationsOrgNameKeyvaluemapsMapName
      x-api-path-slug: organizationsorg-namekeyvaluemapsmap-name-get
      parameters:
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
    put:
      summary: Put Organizations Name Keyvaluemaps Map Name
      description: Updates an existing KeyValueMap.
      operationId: putOrganizationsOrgNameKeyvaluemapsMapName
      x-api-path-slug: organizationsorg-namekeyvaluemapsmap-name-put
      parameters:
      - in: query
        name: Content-Type
        description: Specify the Content Type
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
    delete:
      summary: Delete Organizations Name Keyvaluemaps Map Name
      description: Deletes a KeyValueMap and all associated entries.
      operationId: deleteOrganizationsOrgNameKeyvaluemapsMapName
      x-api-path-slug: organizationsorg-namekeyvaluemapsmap-name-delete
      parameters:
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
---