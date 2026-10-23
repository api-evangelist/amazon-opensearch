---
title: "Amazon OpenSearch Service 101: How many shards do I need"
url: "https://aws.amazon.com/blogs/big-data/amazon-opensearch-service-101-how-many-shards-do-i-need/"
date: "2025-07-24"
author: "Tom Burns"
feed_url: "https://aws.amazon.com/blogs/big-data/category/analytics/amazon-opensearch-service/feed/"
---
Customers new to Amazon OpenSearch Service often ask how many shards their indexes need. An index is a collection of shards, and an index’s shard count can affect both indexing and search request efficiency. OpenSearch Service can take in large amounts of data, split it into smaller units called shards, and distribute those shards across a dynamically changing set of instances.
