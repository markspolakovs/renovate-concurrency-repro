# Repro for renovatebot/renovate#40311

## Current behavior

Occasionally, JSONata expressions that use `$$` produce incorrect data because the `$` binding of their environment gets modified concurrently.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/40311
