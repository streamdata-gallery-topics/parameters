---
swagger: "2.0"
x-collection-name: TVmaze
x-complete: 0
info:
  title: TVmaze user Parameters User Follows Shows
  description: Parameters user follows shows.
  version: "1.0"
host: api.tvmaze.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/episodes/{episode_id}:
    parameters:
      summary: Parameters User Episodes
      description: Parameters user episodes.
      operationId: parametersUserEpisodesEpisode
      x-api-path-slug: userepisodesepisode-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Television
      - Parameters
      - User
      - Episodes
  /user/follows/networks/{network_id}:
    parameters:
      summary: Parameters User Follows Networks
      description: Parameters user follows networks.
      operationId: parametersUserFollowsNetworksNetwork
      x-api-path-slug: userfollowsnetworksnetwork-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Television
      - Parameters
      - User
      - Follows
      - Networks
  /user/follows/people/{person_id}:
    parameters:
      summary: Parameters User Follows People Person
      description: Parameters user follows people person.
      operationId: parametersUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Television
      - Parameters
      - User
      - Follows
      - People
      - Person
  /user/follows/shows/{show_id}:
    parameters:
      summary: Parameters User Follows Shows
      description: Parameters user follows shows.
      operationId: parametersUserFollowsShowsShow
      x-api-path-slug: userfollowsshowsshow-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Television
      - Parameters
      - User
      - Follows
      - Shows
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