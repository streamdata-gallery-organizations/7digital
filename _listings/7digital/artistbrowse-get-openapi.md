---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 0
info:
  title: 7digital Purchasing API artist/browse
  description: This method returns a list of artists from the 7digital catalogue whose
    names match the start letter(s) supplied.
  version: "1.2"
host: api.7digital.com
basePath: 1.2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  artist/browse:
    'get ':
      summary: artist/browse
      description: This method returns a list of artists from the 7digital catalogue
        whose names match the start letter(s) supplied.
      operationId: artistbrowse
      x-api-path-slug: artistbrowse-get
      parameters:
      - ~
      - in: query
        name: artistId
        description: unique identifier of the artist
      - in: query
        name: country
        description: nttttttt 2 letter ISO country code of the country whose releases
          you would like to searchntttttt
      - in: query
        name: imageSize
        description: nttttttt The requested width of the image in pixelsntttttt
      - in: query
        name: letter
        description: The first letter(s) of the artist name to browse
      - in: query
        name: page
        description: Page number of the result set
      - in: query
        name: pageSize
        description: Number of items to be returned per page
      - in: query
        name: period
        description: The time period for which the chart is generated
      - in: query
        name: streamable
        description: If provided search results will contain only releases that can/cannot
          be streamed
      - in: query
        name: toDate
        description: The last day the chart should include data for
      - in: query
        name: type
        description: Releases can be of type album, single or video
      responses:
        200:
          description: OK
      tags:
      - Artist
      - Browse
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