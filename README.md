# Aaron Sawit

Cybersecurity engineer in Singapore. GIAC Certified Incident Handler (GCIH). I build things, and I like explaining how they work.

By day I work in security. On the side I tutor special needs students, which is why I built [Versed](https://versedapps.com): four free learning tools for students, tutors and teachers, designed, built and run by me on Cloudflare's edge.

**Portfolio and write-ups:** [aaronsawit.com](https://aaronsawit.pages.dev) · **LinkedIn:** [neil-aaron-s](https://www.linkedin.com/in/neil-aaron-s-570411246/)

## Security work in the open

| Repo | What it is |
|---|---|
| [detections](https://github.com/aaronsawit/detections) | Sigma rules mapped to MITRE ATT&CK. Every rule has match and no-match fixtures, validated in CI and converted to Splunk and Elastic queries. |
| [blue-team-ai](https://github.com/aaronsawit/blue-team-ai) | Syslog triage in Python: deterministic rules and IOC matching first, an LLM classifier second, held to a strict output format. 36 offline tests. |
| [phising-analyser](https://github.com/aaronsawit/phising-analyser) | CLI that checks a URL against OpenPhish and URLhaus and catches lookalike brand domains such as `micros0ft-login.example.com`. |
| [custom-snort-rules](https://github.com/aaronsawit/custom-snort-rules) · [iptables-firewall-scripts](https://github.com/aaronsawit/iptables-firewall-scripts) | Study notes from 2024: first network detection rules and a default-deny host firewall. |

## Things I build

- **[Versed](https://versedapps.com)**: live classroom quizzes, quiet pixel-art study rooms, a progress tracker for tutors, and flashcards. TypeScript on Cloudflare Workers, Durable Objects, D1 and Pages. No sign-up to play, no tracking.
- **A home server on 2017 hardware**: 40+ self-hosted services behind a WireGuard mesh with no port open to the internet, nightly backups, monitoring and alerts. Every odd failure becomes a [root-cause write-up](https://aaronsawit.pages.dev/writing/).
- **Local LLM benchmarking**: a 35B model from 46 to 71 tokens a second on two GTX 1080 Tis, with the negative results written down.

## Background

- GIAC Certified Incident Handler (GCIH), SANS SEC504
- Hack The Box Academy, SOC Analyst path
- Tutoring primary and lower-secondary special needs students since 2020

Python · TypeScript · Linux · Docker · Cloudflare Workers · Elastic Stack · Sysmon · Sigma · MITRE ATT&CK

Outside of work: weightlifting, MMA and bouldering.
