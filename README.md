# TestDashboard

a monitoring framework based on tests and statuses. meant to be flexible / agnostic to systems, and extensible.

## Tests

Tests can be small jobs like pings or queries to a DB or scripts.

Anything that is not a quick little script that can be called directly from the framework can add records to a DB directly or through a simple API. These need to report status such as "started" and "completed" so that hung jobs can be recognized.

## UI

Primarily a status view of failed tests for a timeframe, interactive to see history relationships and other information

## Prerequisites

Node.js latest long term support version
MySQL Community version

## Getting started

