---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Machinetags Get Values
  description: Return a list of unique values for a namespace and predicate.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.machinetags.getRecentValues:
    get:
      summary: Machinetags Get Recent Values
      description: Fetch recently used (or created) machine tags values.
      operationId: getRestMethodFlickr.machinetags.getrecentvalues
      x-api-path-slug: restmethodflickr-machinetags-getrecentvalues-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: namespace
        description: A namespace that all values should be restricted to
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of values to return per page
      - in: query
        name: predicate
        description: A predicate that all values should be restricted to
      responses:
        200:
          description: OK
      tags:
      - Machinetags
      - GetRecentValues
  /rest/?method=flickr.machinetags.getValues:
    get:
      summary: Machinetags Get Values
      description: Return a list of unique values for a namespace and predicate.
      operationId: getRestMethodFlickr.machinetags.getvalues
      x-api-path-slug: restmethodflickr-machinetags-getvalues-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: namespace
        description: A namespace that all values should be restricted to
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of values to return per page
      - in: query
        name: predicate
        description: A predicate that all values should be restricted to
      responses:
        200:
          description: OK
      tags:
      - Machinetags
      - GetValues
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