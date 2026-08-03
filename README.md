## Tools

Small, sharp tools for the problems that quietly eat an afternoon. Each one does a
single job, runs locally, and shows you what it will do before it does it.

| | What it kills |
|:--|:--|
| **[kibble](https://github.com/dcadolph/kibble)** | Your README says `go install`, then some setup, then a quickstart. Every step rots the moment the code moves, and your machine already has everything installed, so you are the last to find out. kibble runs the documented steps in a clean container from zero and fails CI instead of a new user's terminal. |
| **[preen](https://github.com/dcadolph/preen)** | You got in the zone and came out with forty changed files and no commits. preen splits the tree into clean, atomic commits with real messages, ordered so the history bisects. It shows the plan first and nothing moves until you approve. |
| **[slop-chop](https://github.com/dcadolph/slop-chop)** | AI writing leaves fingerprints: em-dashes, stock openers, and words like `comprehensive`. slop-chop removes them in one deterministic pass, with your own list of things to cut on top. Runs locally, and in the browser at [slop-chop.com](https://slop-chop.com). |
| **[whodar](https://github.com/dcadolph/whodar)** | Someone at your company already knows the answer. whodar tells you who, and which channel to ask in, with the reason and confidence behind each result. Points at the tools your org already uses. Local by default, with or without an LLM. |
| **[vamoose](https://github.com/dcadolph/vamoose)** | Booking time off is six chores across four systems: the hold, the manager, the Slack nudge, the team invite, the second blocked event, the HR portal. vamoose runs them as one workflow that advances itself in the background. |

### Try one in a minute

```sh
brew install dcadolph/tap/slop-chop     # then: slop-chop < anything.md
go install github.com/dcadolph/kibble@latest   # then: kibble ./yourrepo
brew install dcadolph/whodar/whodar     # then: whodar demo
```

### Also public

- [cipher](https://github.com/dcadolph/cipher), programmatic SOPS for Go: encrypt, decrypt, rotate, and audit secret files
- [fleetsweeper](https://github.com/dcadolph/fleetsweeper), multi-cluster Kubernetes comparison and drift detection
- [cinatlas](https://github.com/dcadolph/cinatlas), quick movie facts: where it was filmed, who is in it, what else they made
- [midden](https://github.com/dcadolph/midden), the plain and simple personal journal
- [jwtmint](https://github.com/dcadolph/jwtmint), JWT made easy
