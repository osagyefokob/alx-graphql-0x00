# Episode Queries

Endpoint: https://rickandmortyapi.com/graphql

This folder contains GraphQL queries that fetch episode details and character pages.

Files:
- episode-page-1.graphql
- episode-page-1-output.json
- characters-page-1.graphql
- characters-page-1-output.json
- characters-page-2.graphql
- characters-page-2-output.json
- characters-page-3.graphql
- characters-page-3-output.json
- characters-page-4.graphql
- characters-page-4-output.json

Each `.graphql` file contains a single GraphQL query.  
Episode queries request: id, name, air_date, episode.  
Character page queries request: id, name, status, image.

Each `-output.json` file contains a valid API response for the corresponding query.
