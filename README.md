# Place Holder

### Database Sharding
- [The Great Re-shard: adding Postgres capacity (again) with zero downtime](https://www.notion.com/blog/the-great-re-shard): This article details how Notion horizontally re-sharded its Postgres database cluster to accommodate increased traffic and maintain zero downtime. It covers the challenges faced, the solution implemented involving adding more machines and sharding the PgBouncer connection-pooling layer, and the testing and failover process.

- [Herding elephants: lessons learned from sharding Postgres at Notion](https://www.notion.com/blog/sharding-postgres-at-notion): This article details the process of sharding Notion's PostgreSQL monolith into a horizontally-partitioned database fleet. It covers the motivations for sharding, the design decisions involved, the implementation process including double-writing and backfilling, and lessons learned. The goal was to improve application performance and reliability.

### Software Architecture
- [Exploring Notion's Data Model: A Block-Based Architecture](https://www.notion.com/blog/data-model-behind-notion): This article explores Notion's data model, highlighting its block-based architecture and how it empowers users to customize information organization and sharing. It details the attributes of blocks, their relationships, and how they fit together to create a flexible and powerful user experience.

### Data Engineering
- [How Notion built and grew our data lake to keep up with rapid growth](https://www.notion.com/blog/building-and-scaling-notions-data-lake): This article details how Notion built and scaled its data lake to accommodate rapid growth, focusing on the technical challenges and solutions involved in managing a tenfold increase in data volume over three years. It covers the migration from a sharded Postgres architecture to an in-house data lake solution using technologies like Kafka, Apache Hudi, and Spark, highlighting the benefits of cost savings and improved performance for AI and other product features.

### Artificial Intelligence
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps): A curated collection of LLM apps featuring AI Agents and Retrieval-Augmented Generation (RAG), utilizing models from OpenAI, Anthropic, Google, and open-source alternatives. The repository showcases practical applications across various domains, encouraging learning and contribution to the open-source LLM ecosystem.