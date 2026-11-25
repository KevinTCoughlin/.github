# KevinTCoughlin/.github

Default community health files for every public repository in the `KevinTCoughlin` account.
GitHub uses each of these for any repository that doesn't have its own copy:

- [`FUNDING.yml`](FUNDING.yml): the Sponsor button
- [`SECURITY.md`](SECURITY.md): how to report a vulnerability privately
- [`CONTRIBUTING.md`](CONTRIBUTING.md): DCO sign-off and contribution licensing
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md): Contributor Covenant 2.1
- [`SUPPORT.md`](SUPPORT.md): where to ask a question, and that replies are best effort
- [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md): summary, test plan, and checkboxes for publishing and breaking changes
- [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE): bug and feature forms. Blank issues stay available, and the chooser links to Discussions and SECURITY.md

A repository's own file always wins over these defaults. The override can live in that
repository's root, its `.github/` folder, or its `docs/` folder. Issue templates are the
exception: if a repository has anything in `.github/ISSUE_TEMPLATE/`, GitHub ignores this whole
set.

These repositories already have a code of conduct, so they keep theirs:

- [godot-device-power](https://github.com/KevinTCoughlin/godot-device-power)
- [godot-xdg-portals](https://github.com/KevinTCoughlin/godot-xdg-portals)
- [lazydeck](https://github.com/KevinTCoughlin/lazydeck)

Any other file above is overridden the same way, one file at a time, wherever a repository
already has its own copy.

Organization repositories get theirs
from [cascadiacollections/.github](https://github.com/cascadiacollections/.github).
This account is a user, so it has no Actions workflow templates.
