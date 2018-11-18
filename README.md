
# AppSync GraphQL API -> Resolvers -> DynamoDB

## Description

This is a serverless component consisting of:

- an AppSync GraphQL API
- several resolvers to save, delete, get one, get all items from a DynamoDB Table
- a DynamoDB table, where all your data is stored.

Aside from this main functionality, its important features are:

- Access is provided with an API Key
- No language runtime, everything done through the resolves
- Easily composable into your other app components by adding triggers to its DynamoDB table

It's a Nuts & Bolts application component for AWS Serverless Application Repository.

## Latest Release - 1.0.0

Initial release.

## Roadmap - Upcoming changes

Here are the upcoming changes that I'll add to this serverless component:

- ESLint
- Tests
- Conditional DynamoDB table creation