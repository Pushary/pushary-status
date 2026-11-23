# Pushary service status

[![Public service checks](https://github.com/Pushary/pushary-status/actions/workflows/status.yml/badge.svg)](https://github.com/Pushary/pushary-status/actions/workflows/status.yml)

Open the [latest check and its timestamp](https://github.com/Pushary/pushary-status/actions/workflows/status.yml) to see what responded from outside Pushary. The badge shows the last completed result. If the latest observation is more than 45 minutes old, treat current status as unknown. The workflow requests a check every 15 minutes, and GitHub can delay or skip scheduled runs.

| Component | What the check measures |
| --- | --- |
| API | The public health endpoint reports healthy. |
| Hosted MCP | The server completes an anonymous MCP initialization and identifies itself. |
| Phone delivery | Device delivery is currently unmeasured by this monitor. |
| Answer return | Returning a phone answer to the original agent is currently unmeasured by this monitor. |

[Open incidents](https://github.com/Pushary/pushary-status/issues?q=is%3Aissue+is%3Aopen+label%3Aincident) · [Incident history](https://github.com/Pushary/pushary-status/issues?q=is%3Aissue+label%3Aincident) · [Customer support](https://pushary.com/support)

Pushary maintainers use incident issues for confirmed service interruptions and recovery updates. Please use support for individual delivery failures and the [private reporting channel](https://github.com/Pushary/pushary-skill/blob/main/SECURITY.md) for security concerns. The checks show observations over time. Service availability terms are in [section 7 of the Terms of Service](https://pushary.com/terms).
