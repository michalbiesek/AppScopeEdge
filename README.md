# AppScopeEdge

This demo uses [Edge](https://cribl.io/edge/) to collect Redis data with [AppScope](https://github.com/criblio/appscope) using Unix domain socket connection and [AppScope source](https://docs.cribl.io/edge/sources-appscope).

## Overview

This demo environment uses:

- [Redis](https://redis.io/) as an instrumented application.
- [AppScope](https://appscope.dev/) as an observaiblity library.
- [Cribl Edge](https://cribl.io/edge/) as a agent.

By default, the service will be available at the following URLs:

|Service|URL|
|-------|---|
|Cribl Edge|[http://localhost:9420](http://localhost:9420)|

### Building

To build the demo:

```bash
./start.sh
```

## Cleaning up after a session

To clean up the demo environment:

```bash
./stop.sh
```
