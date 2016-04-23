# Transport
An opinionated RabbitMQ toolset.  Transport helps your teams to implement RabbitMQ messaging in a way that documents your integration points, and utilizes Git as a platform for collaborating.  This is especially useful if you have cross-team integrations in your organization.

## How it works
There are three parts at work here: a structured git repository that documents your architecture, a command-line client/webserver that manages that repository, and a gem that wraps RabbitMQ that you can use in your application.  

The repository provides a clear documentation of how your teams/applications pass data to each other.  At the same time, this repository is structured in such a way that it can provide a manifest to the RabbitMQ wrapper that will automatically configure usage of Rabbit to match the documentation.  Now you can collaborate on changes to your integration in a structured way rather than an error prone configuration where each app is responsible for "getting it right".  

**More info to come**
