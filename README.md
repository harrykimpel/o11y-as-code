# Observability-as-Code

Observability is an integral part of operating a distributed and microservices architecture. We rely on different system outputs such as distributed tracing, aggregate logs and metrics to infer the internal state of the distributed components, diagnose where the problems are and get to the root cause. An important aspect of an observability ecosystem is monitoring, visualizing and analyzing the system's output — and alerting when unexpected conditions are detected. Traditionally, configuration of monitoring dashboards and setting up alerts is done through GUI-based point-and-click systems.

This repository is intended to help with setting up and getting up to speed with some observability concepts and techniques.

## Content

This repository contains the following folders:

- [Zero-day vulnerabilities](./zero-day-vulnerabilities/): here you'll find a sample New Relic alert policy and alert condition configuration for zero-day vulnerabilitiy alerts. It contains a [Terraform script](./zero-day-vulnerabilities/zero-day-vulnerability-alert.tf) along with a [NerdGraph](https://developer.newrelic.com/try-our-apis#graphql-api) (New Relic's GraphQL API) [query](./zero-day-vulnerabilities/zero-day-vulnerability-alert.gql) that you can use along with [New Relic's Graphiql Explorer](https://api.newrelic.com/graphiql).
