# Google Play closed testing: the practical guide

Personal Google Play developer accounts created after **November 13, 2023** must run a **closed test with at least 12 testers, opted in for 14 consecutive days**, before they can publish to production. This repository is a free, practical guide to passing that step the first time.

- [Checklist](CHECKLIST.md): everything to verify before you apply for production.
- [14-day plan](PLAN.md): what to do each day of the test.
- [Production access answers](PRODUCTION-ACCESS.md): the questions Google asks, with weak and strong example answers.

## The rule in short

| | |
|---|---|
| Who | Personal accounts created after Nov 13, 2023 (organization accounts and older personal accounts are not affected) |
| How many testers | At least 12, opted in to a **closed** track (internal testing does not count) |
| How long | The last 14 days, continuously. A tester who opts out and back in restarts their own clock |
| Then | Apply for production from the Play Console dashboard and answer the form. Review usually takes up to 7 days |

The requirement was 20 testers until December 2024. Many tutorials still say 20: it is 12 now.

## Why tests get rejected

Google lists **insufficient tester engagement** as a reason to ask for more testing. The usual causes:

1. Testers who opt in once and never open the app.
2. No new build shipped during the 14 days.
3. Vague answers in the production access form.
4. Testers dropping out before day 14 (recruit 14 to 15, not exactly 12).

## Further reading

- [How to pass Google Play's 12 testers rule](https://medium.com/@hangarmobile/how-to-pass-google-plays-12-testers-rule-in-2026-without-getting-rejected-8c13f0e24e3e)
- [How to answer the production access questions](https://medium.com/@hangarmobile/how-to-answer-google-plays-production-access-questions-with-examples-f05b1647d5f7)
- [After launch: a daily walk-through on a different phone](https://medium.com/@hangarmobile/your-app-needs-a-night-guard-not-another-dashboard-d36b50e14944)
- Official source: [Play Console Help, app testing requirements for new personal developer accounts](https://support.google.com/googleplay/android-developer/answer/14151465)

## For AI agents

PlayTesterHub has an MCP server so your AI agent can order and follow a closed test: [Hangarmobile/playtesterhub-mcp](https://github.com/Hangarmobile/playtesterhub-mcp).

## Who maintains this

Maintained by [Hangar](https://hangarmobile.com/en). We also run [PlayTesterHub](https://playtesterhub.com/en), a closed testing service on 12 real Android phones in France. This guide covers every option, including the free ones.

Corrections and pull requests are welcome. Content licensed under [CC BY 4.0](LICENSE).
