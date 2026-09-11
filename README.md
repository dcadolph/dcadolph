## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I design and engineer platform software at infrastructure scale, focusing on systems that are simple to operate, deterministic, and resilient under pressure.

By day, I build backend platform infrastructure behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, and fleet operations. Outside work, I build and maintain independent software across infrastructure, security, developer tooling, and specialized applications. The common thread is deliberate engineering: self-contained binaries, real dependencies, deterministic behavior, and software built to run reliably anywhere.

### Selected Work

My enterprise work is proprietary, so none of it appears here. These public projects reflect my personal work, held to those same engineering standards.

| Project                                                      | What it is                                                                                                     |
| :----------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------- |
| **[slop-chop](https://github.com/dcadolph/slop-chop)**       | Deterministic local processing for stripping recognizable AI writing tells from text. No API or cloud service. |
| **[kibble](https://github.com/dcadolph/kibble)**             | Verifies that a project's installation instructions actually work from a completely clean environment.         |
| **[cipher](https://github.com/dcadolph/cipher)**             | Programmatic SOPS for Go, including encryption, decryption, rotation, and auditing across six KMS backends.    |
| **[jwtmint](https://github.com/dcadolph/jwtmint)**           | JWT library, daemon, controller, and JWKS tooling for minting, signing, verifying, and inspecting tokens.      |
| **[fleetsweeper](https://github.com/dcadolph/fleetsweeper)** | Multi cluster Kubernetes drift detection that finds the cluster that does not look like the rest of the fleet. |
| **[depstamp](https://github.com/dcadolph/depstamp)**         | Records which dependencies an agent actually used in work that passed.                                         |
| **[preen](https://github.com/dcadolph/preen)**               | Plans and executes clean Git history rewrites while preserving the actual work.                                |

### More Projects

| Project                                                    | What it is                                                                                        |
| :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| **[midden](https://github.com/dcadolph/midden)**           | A local first personal journal built around plain text, durable data, and simple tools.           |
| **[battlesight](https://github.com/dcadolph/battlesight)** | An interactive visual encyclopedia of warfare covering 13,000+ battles, each tied to its sources. |
| **[cinatlas](https://github.com/dcadolph/cinatlas)**       | A quick reference for films, filming locations, casts, and related work.                          |
| **[vamoose](https://github.com/dcadolph/vamoose)**         | Calendar workflow automation across Outlook, Google, iCloud, and CalDAV.                          |

### Engineering

Go is my primary language, with a heavy bias toward standard library design, integration testing against real dependencies, and self-contained binaries that run predictably anywhere.

Go is my wheelhouse, not a constraint. I use Swift and SwiftUI for native Apple interfaces, Python where it fits the problem, and whatever other tools the system actually calls for. The language changes; the engineering standard does not.

I treat LLMs as specialized components rather than foundational architecture. Models are useful where fuzzy output is acceptable. Where a system requires deterministic correctness, speed, or auditability, I solve it with code, not a prompt.
