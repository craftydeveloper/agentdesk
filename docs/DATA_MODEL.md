# Data model

## Proposed fields

Tasks need an identifier, title, context, tool or owner, priority, status, and timestamps.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.