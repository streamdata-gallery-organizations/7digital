---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 0
info:
  title: 7digital Purchasing API basket/addpriceditem
  description: This method allows an item to be added to a basket with a specified
    price. The specified price can be higher or lower than the 7digital catalogue
    price, including a price of 0.00 to make an item free.
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
  basket:
    '<h4 ':
      summary: basket
      description: Basket.
      operationId: basket
      x-api-path-slug: basket-h4
      parameters:
      - ~
      - in: query
        name: amountDue
      - in: query
        name: artistName
      - in: query
        name: basket id
      - in: query
        name: basketId
        description: nttttttttThe unique identifier of the basket as acquired by basket/create
          methodnttttttt
      - in: query
        name: basketItem id
      - in: query
        name: basketItems
      - in: query
        name: country
        description: The code of the country the end user resides in
      - in: query
        name: discount
      - in: query
        name: itemCount
      - in: query
        name: itemName
      - in: query
        name: package
      - in: query
        name: price
      - in: query
        name: releaseId
      - in: query
        name: trackId
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Basket
  basket/addpriceditem:
    'get ':
      summary: basket/addpriceditem
      description: This method allows an item to be added to a basket with a specified
        price. The specified price can be higher or lower than the 7digital catalogue
        price, including a price of 0.00 to make an item free.
      operationId: basketaddpriceditem
      x-api-path-slug: basketaddpriceditem-get
      parameters:
      - ~
      - in: query
        name: basketId
        description: The unique identifier of the basket generated by the basket/create
          method
      - in: query
        name: country
        description: nttttttttThe country that all basket items were selected from
      - in: query
        name: country/shopId
        description: nttttttttA Country Code needs to be provided if you are delivering
          content from a 7digital international shop
      - in: query
        name: emailAddress
        description: The email address of the User
      - in: query
        name: oauth_token
        description: users OAuth accesstoken
      - in: query
        name: price
        description: nttttttttThe custom price for the item to add to the basket e
      - in: query
        name: purchaseid
        description: purchase id identifying the transaction at 7digitals end that
          the refunded item belongs to
      - in: query
        name: releaseId
        description: The unique identifier of the release
      - in: query
        name: retailPrice
        description: Compulsory if you are charging your users different prices than
          7digital RRP
      - in: query
        name: shopid
        description: nttttttttThe shop ID that all basket items were selected from
      - in: query
        name: trackId
        description: The unique identifier of the track
      - in: query
        name: transactionId
        description: The transaction ID provided will be stored along with a 7digital
          purchase ID in the 7digital transactions log
      responses:
        200:
          description: OK
      tags:
      - Basket
      - Addpriceditem
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