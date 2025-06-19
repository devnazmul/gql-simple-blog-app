# Blog APP

A simple MERN Application to practice GQL

## Requirement

- Authentication
- User can create post
- User can view others the post
- User can delete the post
- Post draft system
- User can see their profile

## Tables

- user
  - id
  - name
  - email
  - password
  - createdAt
  - updatedAt
  - profile
- profile
  - id
  - bio
  - createdAt
  - updatedAt
  - userId
- post
  - id
  - title
  - content
  - authorId
  - createdAt
  - updatedAt
  - isPublished
  - publishAt

## Tech Stack

- GraphQL
- TypeScript
- PostgreSQL
- Prisma
- NextJS
