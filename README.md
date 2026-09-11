## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I design and engineer platform software at infrastructure scale, focusing on systems that are simple to operate, deterministic, and resilient under pressure.

By day, I build backend platform infrastructure behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, and fleet operations. Outside work, I apply those same production standards across a wide technical range. That spans deep-systems tooling like custom JWT controllers and programmatic SOPS backends, down to specialized applications for history, calendar automation, and cinema data. Every project gets the same bar: self-contained binaries, real dependencies, and zero tolerance for hand-waving.

### Selected work

| Project                                                      | What it is                                                                                                     |
| :----------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------- |
| **[slop-chop](https://github.com/dcadolph/slop-chop)**       | Deterministic local processing for stripping recognizable AI writing tells from text. No API or cloud service. |
| **[kibble](https://github.com/dcadolph/kibble)**             | Verifies that a project's installation instructions actually work from a completely clean environment.         |
| **[cipher](https://github.com/dcadolph/cipher)**             | Programmatic SOPS for Go, including encryption, decryption, rotation, and auditing across six KMS backends.    |
| **[jwtmint](https://github.com/dcadolph/jwtmint)**           | JWT library, daemon, controller, and JWKS tooling for minting, signing, verifying, and inspecting tokens.      |
| **[fleetsweeper](https://github.com/dcadolph/fleetsweeper)** | Multi cluster Kubernetes drift detection that finds the cluster that does not look like the rest of the fleet. |
| **[depstamp](https://github.com/dcadolph/depstamp)**         | Records which dependencies an agent actually used in work that passed.                                         |
| **[preen](https://github.com/dcadolph/preen)**               | Plans and executes clean Git history rewrites while preserving the actual work.                                |

### More projects

| Project                                                    | What it is                                                                                        |
| :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| **[midden](https://github.com/dcadolph/midden)**           | A local first personal journal built around plain text, durable data, and simple tools.           |
| **[battlesight](https://github.com/dcadolph/battlesight)** | An interactive visual encyclopedia of warfare covering 13,000+ battles, each tied to its sources. |
| **[cinatlas](https://github.com/dcadolph/cinatlas)**       | A quick reference for films, filming locations, casts, and related work.                          |
| **[vamoose](https://github.com/dcadolph/vamoose)**         | Calendar workflow automation across Outlook, Google, iCloud, and CalDAV.                          |

### Engineering

Go is my primary language. I favor the standard library, real dependencies over mocks, reproducible tests, and software that can be inspected and run on its own machine.

I also build AI and agent tooling, but I am deliberately selective about where a model belongs. When correctness needs to be reproducible, I prefer a deterministic system over a probabilistic one.
