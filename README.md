## Chinh Hoang

Engineer in Hanoi, Vietnam (UTC+7). For seven years at [Stringee](https://stringee.com) I built and ran contact center software: SIP (Kamailio, FreeSWITCH), WebRTC, TURN, call recording, and on-premise deployments for banks and insurers. Today I build integrations and AI agents in Go, TypeScript and Python, and I work with the customers who run them.

### Public work

| Project | What it does |
|---|---|
| [vidiq-creator-copilot](https://github.com/hiimchinh/vidiq-creator-copilot) | Checks AI answers over vidIQ MCP tool results: every number links back to the tool call and field it came from. |
| [proof-qc-agent](https://github.com/hiimchinh/proof-qc-agent) | Go agent that triages sticker artwork before proofing, with a multi-model eval that retires models that don't deliver. |
| [metabase-ci-health](https://github.com/hiimchinh/metabase-ci-health) | Weekly CI health report for metabase/metabase from public GitHub Actions data: flaky jobs, p95 run time, runner wait. |
| [buck](https://github.com/hiimchinh/buck) | Go CLI for multi-repo work on Bitbucket Cloud, with a [Claude Code skill](https://github.com/hiimchinh/buck-skill). |
| [thue-ho](https://github.com/hiimchinh/thue-ho) | Vietnamese household-business tax rules as code, each rule linked to its legal source. |

### Private work I can walk you through

- **Voice Desk**: a self-hosted LiveKit SFU with a SIP gateway, an embeddable webphone and a Go SDK. A Python worker answers calls with Deepgram STT, Claude and ElevenLabs TTS.
- **ERP for a manufacturer**: Go, PostgreSQL and React, with carrier, e-invoice and bank-feed integrations. Releases went from 17 seconds of dropped requests to 0 of 897 failed in a load test.

[hiimchinh.com](https://hiimchinh.com) · [LinkedIn](https://www.linkedin.com/in/hiimchinh)
