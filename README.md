# Splunk + Cribl local test setup

This repo is a simple local playground for testing log flow through Cribl into Splunk using Docker.

## What is included

- `docker-compose.yml` to start the local stack
- sample log files:
  - `logs.jsonl`
  - `attack_logs.jsonl`
- `cribl-config/` for the local Cribl setup

## Prerequisites

Make sure you have:

- Docker Desktop installed
- Docker Compose available
- enough Docker memory to run Splunk and Cribl comfortably

## Files

Expected structure:

```text
.
├── docker-compose.yml
├── logs.jsonl
├── attack_logs.jsonl
└── cribl-config/