# Integration test

Simple experiment that lets the `module` image try to
reach out to services directly connected to it,
e.g.,
RabbitMQ,
DGraph,
and
the Quartermaster Orchestrator.

## How to run

```bash
make --directory ../.. integration-test
```