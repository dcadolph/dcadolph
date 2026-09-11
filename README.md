## Douglas Adolph

Go, Kubernetes, distributed systems, developer tooling.

I build and operate software at infrastructure scale, and spend my time outside work building tools that I would actually want to use.

My day job is backend and platform engineering behind thousands of production Kubernetes clusters: deployment systems, controllers, identity, secrets, fleet operations, and the abstractions that hold them together. The work I can show here is smaller in scale, but built with the same standards: finished software, real dependencies, reproducible behavior, and very little tolerance for hand waving.

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
