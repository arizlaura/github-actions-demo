# GitHub Actions Demo

A collection of GitHub Actions workflows demonstrating common CI/CD patterns.

## Workflows

| Workflow | Trigger | Description |
|----------|---------|-------------|
| CI | push / PR to main | Lint and test across Python 3.10, 3.11, 3.12 (matrix build) |
| Docker | push to main | Build and push image to GHCR with `latest` and SHA tags |
| Scheduled Healthcheck | Every Monday 8am UTC | Runs the app and validates output |
| Manual Deploy | Manual (workflow_dispatch) | Simulates deploy to staging or production |

## CI Pipeline