---
name: 7digital
x-slug: 7digital
description: Welcome to 7digital!    Choose from over 30 million high quality tracks
  in our store; download, sync and play your music on the go.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
x-kinRank: "7"
x-alexaRank: "55455"
tags: 7digital
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/apis.md
specificationVersion: "0.14"
apis:
- name: 7digital Basket API basket
  x-api-slug: 7digital-basket-api
  description: Basket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//basket
  tags: Basket
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basket-h4-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basket-h4-openapi.md
- name: 7digital Basket API
  x-api-slug: 7digital-basket-api
  description: The basket API allows creation of 7digital hosted baskets which can
    be populated with items (tracks and releases) from the 7digital catalogue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2/
  tags: 7digital
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/openapi.md
- name: 7digital Catalogue API artist/browse
  x-api-slug: 7digital-catalogue-api
  description: This method returns a list of artists from the 7digital catalogue whose
    names match the start letter(s) supplied.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: ://api.7digital.com/1.2//artist/browse
  tags: Artist,Browse
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/artistbrowse-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/artistbrowse-get-openapi.md
- name: 7digital Catalogue API release/chart
  x-api-slug: 7digital-catalogue-api
  description: This endpoint returns a chart of the most purchased releases for given
    week. Only albums are included in this chart. To retrieve the most recent charts
    as published on 7digital.com the toDate parameter should be omitted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: ://api.7digital.com/1.2//release/chart
  tags: Release,Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/releasechart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/releasechart-get-openapi.md
- name: 7digital Catalogue API tag
  x-api-slug: 7digital-catalogue-api
  description: This method returns a list of all available tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: ://api.7digital.com/1.2//tag
  tags: Tag
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/tag-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/tag-get-openapi.md
- name: 7digital Catalogue API track/chart
  x-api-slug: 7digital-catalogue-api
  description: This endpoint returns a chart of the most purchased tracks for given
    week. To retrieve the most recent charts as published on 7digital.com the toDate
    parameter should be omitted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: ://api.7digital.com/1.2//track/chart
  tags: Track,Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/trackchart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/trackchart-get-openapi.md
- name: 7digital Catalogue API
  x-api-slug: 7digital-catalogue-api
  description: Access to the 7digital catalogue API
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: ://api.7digital.com/1.2/
  tags: 7digital
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/openapi.md
- name: 7digital Playlist API playlists
  x-api-slug: 7digital-playlist-api
  description: Returns a list of all public playlists. If an oauth_token is provided
    then also given users private playlists will be included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlists-get-openapi.md
- name: 7digital Playlist API playlists/{playlistId}
  x-api-slug: 7digital-playlist-api
  description: Deletes the playlist at {playlistId}. The playlist can only be deleted
    by its owner, i.e. oauth_token representing the user has to be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-delete-openapi.md
- name: 7digital Playlist API playlists/{playlistId}
  x-api-slug: 7digital-playlist-api
  description: Returns playlist details and track listing. Access to private playlists
    is only allowed when an oauth_token of the playlist owner is provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-get-openapi.md
- name: 7digital Playlist API playlists/{playlistId}/details
  x-api-slug: 7digital-playlist-api
  description: Updates playlist details at {playlistId} with the supplied playlist
    details. It does not affect playlist tracks. Use this method e.g. for changing
    visibility of the playlist from private to public. The playlist details can only
    be updated by the playlist owner, i.e. oauth_token representing the user has to
    be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}/details
  tags: Playlists,Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistiddetails-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistiddetails-post-openapi.md
- name: 7digital Playlist API playlists/{playlistId}/tracks/{playlisttrackid}
  x-api-slug: 7digital-playlist-api
  description: Removes the specified track {playlisttrackid} from the specified playlist
    at {playlistId}.  Tracks can only be removed by the playlist owner, i.e. oauth_token
    representing the user has to be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}/tracks/{playlisttrackid}
  tags: Playlists,Tracks,Playlisttrackid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-openapi.md
- name: 7digital Playlist API
  x-api-slug: 7digital-playlist-api
  description: Welcome to 7digital!    Choose from over 30 million high quality tracks
    in our store; download, sync and play your music on the go.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2/
  tags: 7digital
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/openapi.md
- name: 7digital Purchasing API artist/browse
  x-api-slug: 7digital-purchasing-api
  description: This method returns a list of artists from the 7digital catalogue whose
    names match the start letter(s) supplied.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//artist/browse
  tags: Artist,Browse
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/artistbrowse-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/artistbrowse-get-openapi.md
- name: 7digital Purchasing API basket
  x-api-slug: 7digital-purchasing-api
  description: Basket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//basket
  tags: Basket
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basket-h4-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basket-h4-openapi.md
- name: 7digital Purchasing API basket/addpriceditem
  x-api-slug: 7digital-purchasing-api
  description: This method allows an item to be added to a basket with a specified
    price. The specified price can be higher or lower than the 7digital catalogue
    price, including a price of 0.00 to make an item free.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//basket/addpriceditem
  tags: Basket,Addpriceditem
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basketaddpriceditem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/basketaddpriceditem-get-openapi.md
- name: 7digital Purchasing API playlists
  x-api-slug: 7digital-purchasing-api
  description: Returns a list of all public playlists. If an oauth_token is provided
    then also given users private playlists will be included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlists-get-openapi.md
- name: 7digital Purchasing API playlists/{playlistId}
  x-api-slug: 7digital-purchasing-api
  description: Returns playlist details and track listing. Access to private playlists
    is only allowed when an oauth_token of the playlist owner is provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistid-get-openapi.md
- name: 7digital Purchasing API playlists/{playlistId}/details
  x-api-slug: 7digital-purchasing-api
  description: Updates playlist details at {playlistId} with the supplied playlist
    details. It does not affect playlist tracks. Use this method e.g. for changing
    visibility of the playlist from private to public. The playlist details can only
    be updated by the playlist owner, i.e. oauth_token representing the user has to
    be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}/details
  tags: Playlists,Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistiddetails-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistiddetails-post-openapi.md
- name: 7digital Purchasing API playlists/{playlistId}/tracks/{playlisttrackid}
  x-api-slug: 7digital-purchasing-api
  description: Removes the specified track {playlisttrackid} from the specified playlist
    at {playlistId}.  Tracks can only be removed by the playlist owner, i.e. oauth_token
    representing the user has to be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//playlists/{playlistId}/tracks/{playlisttrackid}
  tags: Playlists,Tracks,Playlisttrackid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-openapi.md
- name: 7digital Purchasing API release/chart
  x-api-slug: 7digital-purchasing-api
  description: This endpoint returns a chart of the most purchased releases for given
    week. Only albums are included in this chart. To retrieve the most recent charts
    as published on 7digital.com the toDate parameter should be omitted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//release/chart
  tags: Release,Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/releasechart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/releasechart-get-openapi.md
- name: 7digital Purchasing API tag
  x-api-slug: 7digital-purchasing-api
  description: This method returns a list of all available tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//tag
  tags: Tag
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/tag-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/tag-get-openapi.md
- name: 7digital Purchasing API track/chart
  x-api-slug: 7digital-purchasing-api
  description: This endpoint returns a chart of the most purchased tracks for given
    week. To retrieve the most recent charts as published on 7digital.com the toDate
    parameter should be omitted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//track/chart
  tags: Track,Chart
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/trackchart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/trackchart-get-openapi.md
- name: 7digital Purchasing API user/locker
  x-api-slug: 7digital-purchasing-api
  description: Returns a paged list of releases and tracks for a users locker (collection
    of all purchased tracks). This method must be OAuth signed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//user/locker
  tags: User,Locker
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userlocker-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userlocker-get-openapi.md
- name: 7digital Purchasing API user/purchase/basket
  x-api-slug: 7digital-purchasing-api
  description: This method allows a user to purchase a basket with items that have
    been added via basket/additem or basket/addpriceditem. It will return the download
    URL of each item purchased. For example, if a release consisting of multiple tracks
    was purchased, then the download URL of each item constituting the release will
    be returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//user/purchase/basket
  tags: User,Purchase,Basket
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchasebasket-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchasebasket-get-openapi.md
- name: 7digital Purchasing API user/purchase/item
  x-api-slug: 7digital-purchasing-api
  description: This method allows a user to purchase an item at the price as advertised
    on 7digital.com. It will return the download URL of each item purchased. For example,
    if a release consisting of multiple tracks was purchased, then the download URL
    of each item constituting the release will be returned.nttttttFor a user purchase
    to be processed, the user should already have a default debit or credit card set
    up for payments.ntttThis method allows users to take advantage of 7digital.com
    promotional offers and is only available to selected partners building 7digital
    branded integrations. For white-label integrations please use user/purchase/rrpItem
    or user/purchase/pricedItem.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//user/purchase/item
  tags: User,Purchase,Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchaseitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchaseitem-get-openapi.md
- name: 7digital Purchasing API user/purchase/rrpItem
  x-api-slug: 7digital-purchasing-api
  description: This method allows a user to purchase an item at 7digital recommended
    retail price (RRP). It will return the download URL of each item purchased. For
    example, if a release consisting of multiple tracks was purchased, then the download
    URL of each item constituting the release will be returned.nttttttFor a user purchase
    to be processed, the user should already have a default debit or credit card set
    up for payments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//user/purchase/rrpItem
  tags: User,Purchase,RrpItem
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchaserrpitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchaserrpitem-get-openapi.md
- name: 7digital Purchasing API user/purchase/{purchaseid}/track/{trackid}
  x-api-slug: 7digital-purchasing-api
  description: This method allows a user to remove a purchase of a track from the
    sales report when the purchase has been refunded.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2//user/purchase/{purchaseid}/track/{trackid}
  tags: User,Purchase,Purchaseid,Track,Trackid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchasepurchaseidtracktrackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/userpurchasepurchaseidtracktrackid-delete-openapi.md
- name: 7digital Purchasing API
  x-api-slug: 7digital-purchasing-api
  description: The Purchasing API allows 3rd parties to deliver digital content to
    individual users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2/
  tags: 7digital
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/7digital/master/_listings/7digital/openapi.md
x-common:
- type: x--net-sdk
  url: https://github.com/7digital/SevenDigital.Api.Wrapper
- type: x-android-sdk
  url: http://developer.7digital.com/7digital-android-sdk
- type: x-application-gallery
  url: http://developer.7digital.com/CaseStudies
- type: x-base
  url: http://api.7digital.com/
- type: x-blog
  url: http://developer.7digital.com/blog
- type: x-blog-rss
  url: http://blogs.7digital.com/dev/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/7digital
- type: x-crunchbase
  url: https://crunchbase.com/organization/7digital
- type: x-developer
  url: http://developer.7digital.net/
- type: x-email
  url: api@7digital.com
- type: x-email
  url: help@7digital.com
- type: x-email
  url: sales@7digital.com
- type: x-email
  url: legal@7digital.com
- type: x-email
  url: contention-queries@7digital.com
- type: x-github
  url: https://github.com/7digital
- type: x-ios-sdk
  url: https://github.com/7digital/7digital-iOS-SDK
- type: x-node-js-sdk
  url: https://github.com/raoulmillais/node-7digital-api
- type: x-php-sdk
  url: https://github.com/gquemener/7digital-client
- type: x-python-sdk
  url: https://github.com/jasonrubenstein/python-7Digital
- type: x-ruby-sdk
  url: http://github.com/filip7d/7digital
- type: x-selfservice-registration
  url: https://api-signup.7digital.com/
- type: x-twitter
  url: https://twitter.com/7digital
- type: x-website
  url: http://7digital.com
- type: x-website
  url: http://7digital.net/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---