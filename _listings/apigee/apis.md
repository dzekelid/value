---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Value
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Keyvaluemaps
  x-api-slug: apigee-edge
  description: Returns an expanded view of all Maps scoped by organization, environment
    or API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps
  tags: Organizations,Keyvaluemaps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemaps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemaps-get-openapi.md
- name: Apigee Edge Post Organizations Name Keyvaluemaps
  x-api-slug: apigee-edge
  description: Creates a KeyValueMap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps
  tags: Organizations,Keyvaluemaps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemaps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemaps-post-openapi.md
- name: Apigee Edge Get Organizations Name Keyvaluemaps Map Name Entries Entry Name
  x-api-slug: apigee-edge
  description: Gets a specific entry details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps/{map_name}/entries/{entry_name}
  tags: Organizations,Keyvaluemaps,Map,Entries,Entry
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-get-openapi.md
- name: Apigee Edge Delete Organizations Name Keyvaluemaps Map Name Entries Entry
    Name
  x-api-slug: apigee-edge
  description: Deletes a single entry by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps/{map_name}/entries/{entry_name}
  tags: Organizations,Keyvaluemaps,Map,Entries,Entry
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-nameentriesentry-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Keyvaluemaps Map Name
  x-api-slug: apigee-edge
  description: Gets a KeyValueMap by name, along with associated entries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps/{map_name}
  tags: Organizations,Keyvaluemaps,Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-get-openapi.md
- name: Apigee Edge Put Organizations Name Keyvaluemaps Map Name
  x-api-slug: apigee-edge
  description: Updates an existing KeyValueMap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps/{map_name}
  tags: Organizations,Keyvaluemaps,Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-put-openapi.md
- name: Apigee Edge Delete Organizations Name Keyvaluemaps Map Name
  x-api-slug: apigee-edge
  description: Deletes a KeyValueMap and all associated entries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/keyvaluemaps/{map_name}
  tags: Organizations,Keyvaluemaps,Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/organizationsorg-namekeyvaluemapsmap-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Value
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/value/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---