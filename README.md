# ores-otel-log-gleam-test

Exact-head conformance harness for **gleam**.

This repository tests both `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts` using explicit commit SHAs.
The required native command is recorded in `conformance.json`: `gleam format --check src test && gleam test`.
