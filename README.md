# Patterns

## Retry Specific Step

Here, we are trying to re-try a specific step (e.g., deploy) when the first execution of that step failed.

Given that most tools today should have auto-retry built-in, or retry flags provided, for deployment steps, I think many customers may not need this.

A next-step would be to convert this to a loop or so, possibly with exponential backoff, so that we can retry N > 1 times.
