# Final Pool

This directory contains tasks that have been verified as "implemented" in the
Notion Task Tracker.

## Current Status

As of the latest verification, **no tasks have been marked as implemented**.

All 116 tasks across 14 developer branches were checked against the requirements
defined in `tasks/examples/example-task`. The requirements include:

- `docs/agent_system_prompt.md` must exist, be non-empty, and all English (no Chinese)
- `docs/task.md` must exist, be non-empty, and all English (no Chinese)
- `task_config.json` must exist with a non-empty `needed_mcp_servers` field and a
  non-empty `needed_local_tools` field containing `claim_done`
- `docs/user_system_prompt.md` is optional, but if non-empty must be all English

All tasks currently lack `task_config.json`, so they are marked as "implementing"
in the Notion Task Tracker.
