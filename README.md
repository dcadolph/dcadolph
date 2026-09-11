## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I design and engineer platform software at infrastructure scale, focusing on systems that are simple to operate, deterministic, and resilient under pressure.

By day, I build backend platform infrastructure behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, and fleet operations. Outside work, I apply those same production standards across a wide technical range. That spans deep-systems tooling like custom JWT controllers and programmatic SOPS backends, down to specialized applications for history, calendar automation, and cinema data. Every project gets the same bar: self-contained binaries, real dependencies, and zero tolerance for hand-waving.

### Selected Work

A firm firewall separates my day job from my open-source work, so none of my enterprise code appears here. What I can show you here is my personal work, and it is held to the same rigorous standards: finished software, deterministic behavior, real dependencies, and zero reliance on hacks or shortcuts.

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

Beyond backend platform engineering and DevOps, I leverage a range of languages and tools to get the job done the right way, and the projects here are evidence of that. Go is my wheelhouse, but I do not stay parked in it. When a native Apple interface calls for Swift and SwiftUI, or a workflow calls for Python, I use the right tool for the job and build it to the same production standard as my backend services.

I treat LLMs as specialized components rather than foundational architecture, keeping models isolated to tasks where fuzzy outputs are actually acceptable. If a system requires deterministic correctness, speed, or auditability, I solve it with code, not a prompt.
