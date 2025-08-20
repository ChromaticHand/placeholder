# Place Holder

## Database Sharding
- [The Great Re-shard: adding Postgres capacity (again) with zero downtime](https://www.notion.com/blog/the-great-re-shard): This article details how Notion horizontally re-sharded its Postgres database cluster to accommodate increased traffic and maintain zero downtime. It covers the challenges faced, the solution implemented involving adding more machines and sharding the PgBouncer connection-pooling layer, and the testing and failover process.

- [Herding elephants: lessons learned from sharding Postgres at Notion](https://www.notion.com/blog/sharding-postgres-at-notion): This article details the process of sharding Notion's PostgreSQL monolith into a horizontally-partitioned database fleet. It covers the motivations for sharding, the design decisions involved, the implementation process including double-writing and backfilling, and lessons learned. The goal was to improve application performance and reliability.

## Software Architecture
- [Exploring Notion's Data Model: A Block-Based Architecture](https://www.notion.com/blog/data-model-behind-notion): This article explores Notion's data model, highlighting its block-based architecture and how it empowers users to customize information organization and sharing. It details the attributes of blocks, their relationships, and how they fit together to create a flexible and powerful user experience.