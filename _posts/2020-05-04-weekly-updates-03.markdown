---
layout: post
title:  "Weekly Update #03"
date:   2020-05-04 10:00:00 -0400
categories: updates
excerpt: coronavirus quarantine is a good time to reorganize folders and filename. keep at home, if you will outside, use a mask! 
---

Coronavirus quarantine is a good time to reorganize folders and filename. keep at home, if you will outside, use a mask!


### Added
- Implemented [Loguru][link-loguru] for a better logging and diagnostics on debug mode: [#1042][pr-1042] by [Costallat][gh-costallat]
- Full Meriana Quest: [#1101][pr-1101] by [YohanAugusto][gh-yohanaugusto]
- Bestiary Monster Locations: [#1108][pr-1108] by [Ruiivo][gh-mvmgs]
- TalkAction /reload now has printing on console [#1122][pr-1122] by [dudantas][gh-dudantas]
- Added new build action: [#1127][pr-1127] by [Costallat][gh-costallat]
- Configurable Push Delay: [#1090][pr-1090] by [andersonfaaria][gh-andersonfaaria]

### Changed
- Creature Issue: [#1079][pr-1079] by [FearLucien][gh-fearlucien]
  - Skeleton Elite Warrior cannot be summoned
  - Hellgorak elements rework
  - Dreadbeast attacks, defenses, elements, immunities, and loot rework
- Organization Issue: [#1118][pr-1118] by [dudantas][gh-dudantas]
  - Directory and files were normalized using snake case and lowercase:
    - Actions
    - ChatChannels
    - CreatureScripts
    - GlobalEvents
    - Movements
    - NPCs
    - TalkActions
  - Reorganized indentations around the datapack
- Reward rewrote: [#1097][pr-1097] by [alisonjf][gh-alisonjf]

### Removed

- Nothing :)

### Fixed
- Bestiary reformated: [#1095][pr-1095] by [Oen44][gh-oen44]
- Crash Issue: [#1087][pr-1087] by [SaiyansKing][gh-saiyansking]
  - Remove regular expressions from houses invitation list
- Fixed **doSetCreatureOutfit** to use correct arguments: [#1066][pr-1066] by [Oen44][gh-oen44]
- Quest Issue: [#1130][pr-1130] by [dudantas][gh-dudantas]
  - Bigfoot's Burden Issue
- Lua Checker only trigger when changes some file on data directory: [#1124][pr-1124] by [DSpeichert][gh-dspeichert]
- Dumb Creatures: [#1092][pr-1092] by [marksamman][gh-marksamman]

---

If you like our project, feel free to pay us a coffee, pizza or something else. [Click here][donation-link] check donations methods.

[donation-link]: {{ '/donation' | relative_url }}
[logurus-link]: https://opentibiabr.github.io/loguru/

[pr-1042]: https://github.com/opentibiabr/otservbr-global/pull/1042
[pr-1066]: https://github.com/opentibiabr/otservbr-global/pull/1066
[pr-1079]: https://github.com/opentibiabr/otservbr-global/pull/1079
[pr-1087]: https://github.com/opentibiabr/otservbr-global/pull/1087
[pr-1090]: https://github.com/opentibiabr/otservbr-global/pull/1090
[pr-1092]: https://github.com/opentibiabr/otservbr-global/pull/1092
[pr-1095]: https://github.com/opentibiabr/otservbr-global/pull/1095
[pr-1097]: https://github.com/opentibiabr/otservbr-global/pull/1097
[pr-1101]: https://github.com/opentibiabr/otservbr-global/pull/1101
[pr-1108]: https://github.com/opentibiabr/otservbr-global/pull/1108
[pr-1118]: https://github.com/opentibiabr/otservbr-global/pull/1118
[pr-1122]: https://github.com/opentibiabr/otservbr-global/pull/1122
[pr-1124]: https://github.com/opentibiabr/otservbr-global/pull/1124
[pr-1127]: https://github.com/opentibiabr/otservbr-global/pull/1127
[pr-1130]: https://github.com/opentibiabr/otservbr-global/pull/1130

[gh-alisonjf]: https://github.com/alisonjf
[gh-andersonfaaria]: https://github.com/andersonfaaria
[gh-costallat]: https://github.com/costallat
[gh-dspeichert]: https://github.com/dspeichert
[gh-dudantas]: https://github.com/dudantas
[gh-fearlucien]: https://github.com/fearlucien
[gh-marksamman]: https://github.com/marksamman
[gh-mvmgs]: https://github.com/mvmgs
[gh-oen44]: https://github.com/oen44
[gh-saiyansking]: https://github.com/saiyansking
[gh-yohanaugusto]: https://github.com/yohanaugusto