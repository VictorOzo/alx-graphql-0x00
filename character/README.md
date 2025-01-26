# alx-graphql-0x00

## Directory: `character/`

This repository demonstrates how to query specific characters using GraphQL. 

### Instructions
1. Use the provided `.graphql` files to retrieve character information from the GraphQL endpoint.
2. Each query retrieves the following fields: `id`, `name`, `status`, `species`, `type`, `gender`.

### Queries
- **character-id-1.graphql:** Retrieves character with ID 1.
- **character-id-2.graphql:** Retrieves character with ID 2.
- **character-id-3.graphql:** Retrieves character with ID 3.
- **character-id-4.graphql:** Retrieves character with ID 4.

### Outputs
The results of the queries are stored in `.json` files, e.g., `character-id-1-output.json`.

#### Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
