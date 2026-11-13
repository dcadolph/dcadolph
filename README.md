## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I design and engineer platform software at infrastructure scale, focusing on systems that are simple to operate, deterministic, and resilient under pressure.

By day, I build backend platform infrastructure behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, and fleet operations. Outside work, I build and maintain independent software across infrastructure, security, developer tooling, and specialized applications. The common thread is deliberate engineering: self-contained binaries, real dependencies, deterministic behavior, and software built to run reliably anywhere.

### Projects

My enterprise work is proprietary, so none of it appears here. These public projects reflect my personal work, held to those same engineering standards.

| Project                                                      | Type                    | What it does                                                                                    |
| :----------------------------------------------------------- | :---------------------- | :---------------------------------------------------------------------------------------------- |
| **[kibble](https://github.com/dcadolph/kibble)**             | Go CLI, GitHub Action   | Runs your documented install steps in a clean container, so a broken install fails CI.          |
| **[slop-chop](https://github.com/dcadolph/slop-chop)**       | Go CLI                  | Strips the AI tells out of text in one deterministic local pass.                                |
| **[preen](https://github.com/dcadolph/preen)**               | Go CLI                  | Splits a messy working tree into ordered atomic commits, hash checked end to end.               |
| **[whotoask](https://github.com/dcadolph/whotoask)**         | Go CLI, macOS app       | Answers "who knows about this?" from your team's git, Slack, and Jira, with a reason for each.  |
| **[moorings](https://github.com/dcadolph/moorings)**         | macOS app, Swift        | Snap, tile, throw, stash and recall every window on any Mac, and pin apps to the edges.         |
| **[icelos](https://icelos.app)**                             | macOS app               | Converts video and audio between 40 formats on a Mac, using the Apple media engine when it can. |
| **[sheepdog](https://macsheepdog.com)**                      | macOS app, Swift        | A meeting alarm that escalates until you join, and stops on its own when your mic goes live.    |
| **[fleetsweeper](https://github.com/dcadolph/fleetsweeper)** | Go CLI, webhook         | Finds the Kubernetes cluster that drifted, using the fleet itself as the baseline.              |
| **[battlesight](https://github.com/dcadolph/battlesight)**   | Web app, Go, TypeScript | An interactive atlas of 13,000+ battles from 3000 BC, each tied to its sources.                 |
| **[jwtmint](https://github.com/dcadolph/jwtmint)**           | Go library              | A JWT library with a daemon, a controller, an admission webhook, and JWKS publishing.           |
| **[cipher](https://github.com/dcadolph/cipher)**             | Go library, CLI         | Programmatic SOPS for Go across six key backends, with rotation, editing, and audit.            |
| **[midden](https://github.com/dcadolph/midden)**             | Go CLI, iPhone app      | A personal journal kept as plain markdown you own, written from the terminal or your iPhone.    |
| **[fuginaut](https://github.com/dcadolph/fuginaut)**         | macOS app, Swift        | A free second clock at the center of the menu bar, for wide screens.                            |
| **[cinatlas](https://github.com/dcadolph/cinatlas)**         | Go CLI                  | Quick movie facts from the command line, with filming locations you can map.                    |
| **[depstamp](https://github.com/dcadolph/depstamp)**         | Claude Code skill       | Records which dependencies an agent actually used in work that built and its tests passed.      |

### Engineering

Go is my primary language, with a heavy bias toward standard library design, integration testing against real dependencies, and self-contained binaries that run predictably anywhere.

Go is my wheelhouse, not a constraint. I use Swift and SwiftUI for native Apple interfaces, Python where it fits the problem, and whatever other tools the system actually calls for. The language changes; the engineering standard does not.

I treat LLMs as specialized components rather than foundational architecture. Models are useful where fuzzy output is acceptable. Where a system requires deterministic correctness, speed, or auditability, I solve it with code, not a prompt.
