Most of what I build comes down to one question: did it actually happen, or did
we just assume it did? Passing tests, plausible docs, green workflows, and
matching clusters all invite the assumption. Each of these projects replaces
one of those assumptions with a check.

| | What it establishes |
|:--|:--|
| **[kibble](https://github.com/dcadolph/kibble)** | Your README's install steps actually work, because they ran from zero in a clean container instead of on a machine that already had everything. Fails CI, not a new user's terminal. |
| **[fleetsweeper](https://github.com/dcadolph/fleetsweeper)** | A Kubernetes cluster really is the odd one out, measured against the rest of its fleet instead of eyeballed. |
| **[battlesight](https://github.com/dcadolph/battlesight)** | A historical claim is only as strong as its sourcing. 13,000+ battles from 3000 BC to today, on an interactive map, each tied to where it came from. |
| **[preen](https://github.com/dcadolph/preen)** | A rewritten git history still holds exactly the work you did. Atomic commits with real messages, and the plan shown before anything moves. |

### Also public

- [slop-chop](https://github.com/dcadolph/slop-chop), strip AI tells from text in one deterministic local pass
- [vamoose](https://github.com/dcadolph/vamoose), calendar workflows that advance themselves, across Outlook, Google, iCloud, and CalDAV
- [cipher](https://github.com/dcadolph/cipher), programmatic SOPS for Go: encrypt, decrypt, rotate, and audit secret files
- [jwtmint](https://github.com/dcadolph/jwtmint), mint, sign, verify, and inspect JWTs from the command line
- [midden](https://github.com/dcadolph/midden), the plain and simple local-first personal journal
- [cinatlas](https://github.com/dcadolph/cinatlas), quick movie facts: where it was filmed, who is in it, what else they made
- [depstamp](https://github.com/dcadolph/depstamp), record which dependencies an agent actually used in work that passed
