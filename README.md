# steam-monitor

Automated repository for tracking and publishing Steam client data.

This repository's `main` branch contains the automation workflow only. The data is maintained separately on orphan branches.

| Branch | Description |
| --- | --- |
| [`pattern`](../../tree/pattern) | Steam client pattern definitions |
| [`ipc`](../../tree/ipc) | Steam client IPC interface definitions |

Updates are triggered by new Steam client builds and published automatically. Branch updates use fast-forward operations to preserve the existing commit history.
