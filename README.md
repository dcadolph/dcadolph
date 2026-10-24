## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I design and engineer platform software at infrastructure scale, focusing on systems that are simple to operate, deterministic, and resilient under pressure.

By day, I build backend platform infrastructure behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, and fleet operations. Outside work, I build and maintain independent software across infrastructure, security, developer tooling, and specialized applications. The common thread is deliberate engineering: self-contained binaries, real dependencies, deterministic behavior, and software built to run reliably anywhere.

### Projects

My enterprise work is proprietary, so none of it appears here. These public projects reflect my personal work, held to those same engineering standards.

| Project                                                                                | Form                  | What it does                                                                                 |
| :------------------------------------------------------------------------------------- | :-------------------- | :------------------------------------------------------------------------------------------- |
| **[kibble](https://github.com/dcadolph/kibble)**                                       | Go CLI, GitHub Action | Runs your documented install steps in a clean container, so a broken install fails CI.       |
| **[slop-chop](https://github.com/dcadolph/slop-chop)**<br>[slop-chop.com](https://slop-chop.com) | Go CLI                | Strips the AI tells out of text in one deterministic local pass.                             |
| **[preen](https://github.com/dcadolph/preen)**                                         | Go CLI                | Splits a messy working tree into ordered atomic commits, hash checked end to end.            |
| **[sheepdog](https://github.com/dcadolph/sheepdog)**<br>[macsheepdog.com](https://macsheepdog.com) | macOS, Swift          | A meeting alarm that barks until you join, and hands back what you were doing after.         |
| **[cipher](https://github.com/dcadolph/cipher)**                                       | Go library, CLI       | Programmatic SOPS for Go across six key backends, with rotation, editing, and audit.         |
| **[moorings](https://github.com/dcadolph/moorings)**<br>[macmoorings.com](https://macmoorings.com) | macOS, Lua            | Rectangle's shortcuts, drag snapping and tiling, plus apps parked on the screen edges.       |
| **[skua](https://github.com/dcadolph/skua)**<br>[skuaweather.com](https://skuaweather.com) | Go, web               | Free weather with a bird that reads your day, built on open forecast data.                   |
| **[skerry](https://github.com/dcadolph/skerry)**<br>[skerrynotes.com](https://skerrynotes.com) | macOS, iOS, Swift     | Encrypted Markdown notes that stay on your devices, with sync to storage you control.        |
| **[fleetsweeper](https://github.com/dcadolph/fleetsweeper)**                           | Go CLI, webhook       | Finds the Kubernetes cluster that drifted, using the fleet itself as the baseline.           |
| **[midden](https://github.com/dcadolph/midden)**                                       | Go CLI, iPhone app    | A personal journal kept as plain markdown you own, written from the terminal or your iPhone. |
| **[cinatlas](https://github.com/dcadolph/cinatlas)**                                   | Go CLI                | Quick movie facts from the command line, with filming locations you can map.                 |
| **[battlesight](https://github.com/dcadolph/battlesight)**                             | Web, Go, TypeScript   | An interactive atlas of 13,000+ battles from 3000 BC, each tied to its sources.              |
| **[jwtmint](https://github.com/dcadolph/jwtmint)**                                     | Go library            | A JWT library with a daemon, a controller, an admission webhook, and JWKS publishing.        |

### Engineering

Go is my primary language, with a heavy bias toward standard library design, integration testing against real dependencies, and self-contained binaries that run predictably anywhere.

Go is my wheelhouse, not a constraint. I use Swift and SwiftUI for native Apple interfaces, Python where it fits the problem, and whatever other tools the system actually calls for. The language changes; the engineering standard does not.

I treat LLMs as specialized components rather than foundational architecture. Models are useful where fuzzy output is acceptable. Where a system requires deterministic correctness, speed, or auditability, I solve it with code, not a prompt.
