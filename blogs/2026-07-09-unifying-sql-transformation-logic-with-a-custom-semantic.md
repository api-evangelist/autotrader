---
title: "Unifying SQL Transformation Logic with a Custom Semantic Model"
url: "https://medium.com/autotrader-engineering/unifying-sql-transformation-logic-with-a-custom-semantic-model-ec570a2c741d?source=rss----80bebb18e37c---4"
date: "2026-07-09"
author: "Connor Charles"
feed_url: "https://medium.com/feed/autotrader-engineering"
---
Photo by Lucas van Oort on Unsplash In this post, I will discuss how we leveraged a custom semantic model and sqlglot to unify a complex transformation over our raw Snowplow data across Spark and BigQuery. At Autotrader, we collect a lot of consumer and customer behavioural data, which is then used to power personalisation product features and allow our customers to know more about their potential buyers . A major cross-functional concern for our tracking platform is defining opinionated governance for determining whether a Snowplow event came from a ‘valid consumer’.
