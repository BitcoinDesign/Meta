# Bitcoin Design - Meta
`community`, `project-management`, `process`

Activity in the Bitcoin Design community largely happens in the Slack workspace and here on Github, but also in the various projects our contributors are involved in.

This repository is used for organizing calls, group consensus and coordination. The [Guide](https://github.com/BitcoinDesign/Guide) repository is for the Bitcoin Design Guide we are working on, which is a design reference for anyone building open-source bitcoin products.

Community activity is fluid, but here are a few important starting points:

## How to get involved in the community

1. [Join the community on Slack](https://join.slack.com/t/bitcoindesign/shared_invite/zt-gytq2snl-4TEWJOTKrXRCB4YLBoDunA)
2. [Subscribe to the newsletter](https://bitcoindesign.substack.com) to stay up-to-date
2. Read up on our [project life cycle](Projects.md)
3. Browse [issues](https://github.com/BitcoinDesign/Meta/issues) for upcoming calls and discussions around processes and coordination
4. Subscribe to our [calendar](webcal://raw.githubusercontent.com/BitcoinDesign/Meta/calendar/events.ical) to stay up-to-date with calls and events we organize

## How to get involved in projects

1. Browse [issues labelled as projects](https://github.com/BitcoinDesign/Meta/issues?q=is%3Aopen+is%3Aissue+label%3Aproject)
2. Browse and post ideas in the [#project-ideas](https://bitcoindesign.slack.com/archives/C0174N5KUF9) Slack channel
1. See [projects](Projects.md) for a few project ideas
3. Contribute to the [Bitcoin Design Guide](https://github.com/BitcoinDesign/Guide)

## Bitcoin Design Guide

- Project Intro — [Doc v2.0.0](https://docs.google.com/document/d/1YiYeRIybGmxmErCOI4Jc8Qajz3JGM1JYVfUtpzyCzSk/edit?usp=sharing)
- Slack Channel — [#bitcoin-design-guide](https://bitcoindesign.slack.com/archives/C015856BDME)
- Github Repository — [Guide](https://github.com/BitcoinDesign/Guide)
- Github Project Board — [Guide/Content](https://github.com/BitcoinDesign/Guide/projects/1)

## Further Slack channels

- [#open-design](https://bitcoindesign.slack.com/archives/C015GFYSJNA)
- [#research](https://bitcoindesign.slack.com/archives/C015DQEPCHJ)
- [#ux](https://bitcoindesign.slack.com/archives/C015DQEPCHJ)
- [#design-review](https://bitcoindesign.slack.com/archives/C015DQEPCHJ)
- [#art](https://bitcoindesign.slack.com/archives/C015DQEPCHJ)

## The Bitcoin Design calendar

Our [calendar](webcal://raw.githubusercontent.com/BitcoinDesign/Meta/calendar/events.ical) (an .iCal file) includes upcoming calls (community calls, design review calls, etc). Qualified issues are automatically added to the calendar, which you can then subscribe to via your favorite calendar tool.

- Copy this URL: [https://raw.githubusercontent.com/BitcoinDesign/Meta/calendar/events.ical](https://raw.githubusercontent.com/BitcoinDesign/Meta/calendar/events.ical)
- In Apple Calendar (desktop), use `File -> New calendar subscriptions`
- In Google Calendar (web), click the small `+` icon next to `Other calendars` in the sidebar and select `From URL`
- Paste the URL and save. New events (if there are any scheduled) should show up right away
- In Thunderbird (desktop), `New Calendar` > `On my network` > `iCalendar (ICS)` and paste the [calendar link](https://raw.githubusercontent.com/BitcoinDesign/Meta/calendar/events.ical) in the location field.
- Calendar tools regularly reload subscribed calendars for updates. How often this happens varies by tool

There are two requirements for an issue to be included:

- The issue needs to include a `UTCTime` meta property following this format: `UTCTime: 2020-10-14 9:00 UTC -7`. You can seen an example [here](https://github.com/BitcoinDesign/Meta/issues/27)
- A maintainer needs to add the `call` label to the issue (this prevents spam)
- The calendar auto-updates whenever a new issue is created, or an existing issue is edited