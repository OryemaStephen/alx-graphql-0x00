# GraphQL Character Queries

This directory contains GraphQL queries to fetch character details from the Rick and Morty API using the `character(id: ID!)` field. Each query retrieves the `id`, `name`, `status`, `species`, `type`, and `gender` fields for a specific character ID.

## Files
- `character-id-1.graphql`: Query for character ID 1 (Rick Sanchez)
- `character-id-1-output.json`: Expected output for character ID 1
- `character-id-2.graphql`: Query for character ID 2 (Morty Smith)
- `character-id-2-output.json`: Expected output for character ID 2
- `character-id-3.graphql`: Query for character ID 3 (Summer Smith)
- `character-id-3-output.json`: Expected output for character ID 3
- `character-id-4.graphql`: Query for character ID 4 (Beth Smith)
- `character-id-4-output.json`: Expected output for character ID 4

## Endpoint
The queries are designed to work with the Rick and Morty GraphQL API at `https://rickandmortyapi.com/graphql`.

## Usage
To run a query:
1. Use a GraphQL client (e.g., Postman, Insomnia, or a custom script).
2. Set the endpoint to `https://rickandmortyapi.com/graphql`.
3. Copy the query from the `.graphql` file.
4. Send the query and verify the response matches the corresponding `.json` output file.

## Example Query
```graphql
query GetCharacter {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}