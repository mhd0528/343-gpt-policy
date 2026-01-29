# Privacy Policy — Soccer Stats GPT
**Last updated:** 2026-01-29

This GPT connects to an external API (“343 Google API”) to answer questions about soccer statistics.

## Data sent to our API
When you use this GPT, your question text may be sent to our API to generate answers based on the dataset.

## Data we collect
We may collect basic service logs (timestamp, request status, error logs) for reliability and abuse prevention.

We do not sell your data and do not intentionally collect sensitive personal information.

## Contact
If you have questions, contact: 343-weibo

## Use cases
✅ Clear queries (auto-executed)
| User query                      | Interpretation             |
| ------------------------------- | -------------------------- |
| “Premier League teams by xG”    | Team-level                 |
| “Players at Arsenal by xG”      | Player-level (team filter) |
| “Best passers at Man City”      | Player-level               |
| “Bundesliga defensive rankings” | Team-level                 |

⚠️ Clarification required
| User query                              | Why                      |
| --------------------------------------- | ------------------------ |
| “Manchester United xG from midfielders” | Player vs team ambiguity |
| “Team defense vs player tackles”        | Two schemas mixed        |
| “Best buildup players and teams”        | Dual entity intent       |

Also, please be specific about aggregations like average and sum. 