# Credits

This is the **Off by One fork** of Quick Settings Tweaks – a consolidation of
open community pull requests (most importantly GNOME 50 support) that the
upstream maintainer has not merged.

## Authorship

- **Original author:** qwreey (`me@qwreey.moe`, <https://github.com/qwreey>).
  qwreey created Quick Settings Tweaks and wrote the overwhelming majority of
  the code in this repository. Upstream: <https://github.com/qwreey/quick-settings-tweaks>.
- **Fork maintainer:** John Stockdale, **Off by One, Inc.**
  (<https://github.com/jstockdale>, <https://offx1.com>).

Original commit authorship for every integrated change is preserved in the git
history (`git log`). This file is the human-readable summary; the history is the
authoritative record.

## Integrated contributions

Each change below was taken from an open upstream pull request and cherry-picked
with its author intact. Numbers link to the upstream PRs.

| Upstream PR | Author | Change |
|---|---|---|
| [#245](https://github.com/qwreey/quick-settings-tweaks/pull/245) | Tymoteusz Lango ([@tymek805](https://github.com/tymek805)) | GNOME 50 support; overlay menu X-coordinate offset fix |
| [#231](https://github.com/qwreey/quick-settings-tweaks/pull/231) | sfnemis ([@sfnemis](https://github.com/sfnemis)) | GNOME 49 compatibility: replace `DoNotDisturbSwitch` with GSettings; DND toggle as `St.Button`; overlay negative-offsetY clamp; media `addEventStop` fix |
| [#236](https://github.com/qwreey/quick-settings-tweaks/pull/236) | Giuseppe Carboni ([@giuseppe-carboni](https://github.com/giuseppe-carboni)) | Volume mixer can now be disabled (fixes upstream #177) |
| [#235](https://github.com/qwreey/quick-settings-tweaks/pull/235) | Giuseppe Carboni ([@giuseppe-carboni](https://github.com/giuseppe-carboni)) | Detect scroll end on touchpads via zero-delta check |
| [#239](https://github.com/qwreey/quick-settings-tweaks/pull/239) | nixxo ([@nixxo](https://github.com/nixxo)) | Italian translation |
| [#232](https://github.com/qwreey/quick-settings-tweaks/pull/232) | Skartorion De Pier ([@Skartorion](https://github.com/Skartorion)) | Updated Russian translation |

Feature PRs not (yet) included in this base: upstream
[#228](https://github.com/qwreey/quick-settings-tweaks/pull/228) (notification
widget on the left, Maruf Bepary) and
[#229](https://github.com/qwreey/quick-settings-tweaks/pull/229) (pagination,
Maruf Bepary).

## Copyright & license

- Original work © 2022–2026 qwreey and contributors.
- Fork modifications © 2026 Off by One, Inc.
- Integrated contributions © their respective authors, as listed above.

Licensed under the **GNU Lesser General Public License v3.0 or later**
(`LGPL-3.0-or-later`), the same license as upstream. See [LICENSE](LICENSE).
