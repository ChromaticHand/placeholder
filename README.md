# Place Holder

## Database Sharding
- [Herding elephants: lessons learned from sharding Postgres at Notion](https://www.notion.com/blog/sharding-postgres-at-notion): This article details the process of sharding Notion's PostgreSQL monolith into a horizontally-partitioned database fleet. It covers the reasons for sharding, the architectural decisions made, the implementation process including double-writing and backfilling, and lessons learned. The goal was to improve performance and reliability for Notion users.