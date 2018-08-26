# Exploring Redis Repository

This is a repository to store notes from Redis University Course

## Redis

Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker. It supports data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs and geospatial indexes with radius queries.

## Setup Course Using Docker
  - docker run --name redis -p 6379:6379 redis
  - docker exec -it redis redis-cli