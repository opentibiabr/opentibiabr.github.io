---
layout: post
title:  "Fortnightly Update #05" (from the 15th to the 31st of May.)
date:   2020-05-31 12:00:00 -0400
categories: updates
excerpt: this post was delayed a little bit but we have pretty good news! we are so happy with a lot of contributions and bug reports
---

This post was delayed a little bit but we have pretty good news! we are so happy with a lot of contributions and bug reports

#### Special Thanks for our Donators

### Added
- Missing NPC Iwar: [#1232][pr-1232] by [omarcopires][gh-omarcopires]
- Suppress MSVS warning about fopen_s, etc: [#1233][pr-1233] by [costallat][gh-costallat]
- Prepare monsters to work on change target strategy and NPC Kendra: [#1213][pr-1213] by [Heitortadeu][gh-Heitortadeu]
- Monster strategies: [#1238][pr-1238] by [andersonfaaria][gh-andersonfaaria]
- New control talkactions + spellbook: [#1236][pr-1236] by [andersonfaaria][gh-andersonfaaria]
- Show clientId in look: [#1247][pr-1247] by [andersonfaaria][gh-andersonfaaria]
- Fix doors cults of tibia and added actions to feyrist shrines: [#1246][pr-1246] by [dudantas][gh-dudantas]
- New method getDepotLocker: [#1235][pr-1235] by [andersonfaaria][gh-andersonfaaria]

### Changed
- Changing Imbuements formula: [#1146][pr-1146] by [andersonfaaria][gh-andersonfaaria]
- Monster Improvement (Distance Target Choice): [#1198][pr-1198] by [andersonfaaria][gh-andersonfaaria]
- Improving onDestroyItem: [#1237)][pr-1237)] by [andersonfaaria][gh-andersonfaaria]
- Improve onKill callback: [#1201)][pr-1201)] by [andersonfaaria][gh-andersonfaaria]

### Removed
- Duplicate monsters:
  - Cave Devourer, Diremaw, Tunnel Tyrant, on: [88d9f04a5][commit-88d9f04a5] by [dudantas][gh-dudantas]

### Fixed
- Jack to the future quest (Research and development): [#1199][pr-1199] by [YohanAugusto][gh-yohanaugusto]
- Somes typos:
  - Fix typos in cult of tibia quest: [#1205][pr-1205] by [oualid6496][gh-oualid6496]
  - Fix incorrect line break in blessings.lua: [#1214][pr-1214] by [omarcopires][gh-omarcopires]
- Fixed login/logout effects for gamemasters: [#1214][pr-1214] by [andersonfaaria][gh-andersonfaaria]
- Fix build in linux: [#1223][pr-1223] by [costallat][gh-costallat]
- Docker does not go up: [#1228][pr-1228] by [Riicksouzaa][gh-Riicksouzaa]
- Fix typo in NPC Hugo talks: [#1230][pr-1230] by [Riicksouzaa][gh-Riicksouzaa]
- Resolves [#1229][issue-1229] (Item description bug): [b92989e][commit-b92989e] by [dudantas][gh-dudantas]
- Fix pet death register method and fix missing space between in look: [#1241][pr-1241] by [oalbsilva][gh-oalbsilva]
- Fixing coin cloning: [#1243][pr-1243] by [andersonfaaria][gh-andersonfaaria]
- Possible fix to decay item: [#1231][pr-1231] by [costallat][gh-costallat]
- Blocking corpses to be deleted upon push (fix #1918): [#1200][pr-1200] by [andersonfaaria][gh-andersonfaaria]
- Fixing Sub type problems: [#1217][pr-1217] by [andersonfaaria][gh-andersonfaaria]
- Fix for not saving on shutdown and fix warnings: [#1271][pr-1271] by [dudantas][gh-dudantas]
- Healing Crit Fix: [#1268][pr-1268] by [hyresu][gh-hyresu]
- Stonerefiners shouldn't see invisible enemies: [#1280][pr-1280] by [nickolasdeluca][gh-nickolasdeluca]
- Door system:
  - Refactored the door system and resolves[#1279][issue-1279]: [0a4d241][commit-0a4d241] by [dudantas][gh-dudantas]
- Fix speed of monsters (warzone 5 and 6) and drop unused files: [88d9f04a5][commit-88d9f04a5] by [dudantas][gh-dudantas]
- Fix for the custom doors not opening: [15282fd6a][commit-15282fd6a] by [dudantas][gh-dudantas]


---

If you like our project, feel free to pay us a coffee, pizza or something else. [Click here][donation-link] check donations methods.

[donation-link]: {{ '/donation' | relative_url }}

[commit-b92989e]: https://github.com/opentibiabr/otservbr-global/commit/1d076d8 
[commit-0a4d241]: https://github.com/opentibiabr/otservbr-global/commit/0a4d241 
[commit-88d9f04a5]: https://github.com/opentibiabr/otservbr-global/commit/88d9f04a5 
[commit-15282fd6a]: https://github.com/opentibiabr/otservbr-global/commit/15282fd6a 

[pr-1146]: https://github.com/opentibiabr/otservbr-global/pull/1146
[pr-1198]: https://github.com/opentibiabr/otservbr-global/pull/1198
[pr-1199]: https://github.com/opentibiabr/otservbr-global/pull/1196
[pr-1201]: https://github.com/opentibiabr/otservbr-global/pull/1201
[pr-1200]: https://github.com/opentibiabr/otservbr-global/pull/1200
[pr-1213]: https://github.com/opentibiabr/otservbr-global/pull/1213
[pr-1214]: https://github.com/opentibiabr/otservbr-global/pull/1214
[pr-1217]: https://github.com/opentibiabr/otservbr-global/pull/1217
[pr-1222]: https://github.com/opentibiabr/otservbr-global/pull/1222
[pr-1223]: https://github.com/opentibiabr/otservbr-global/pull/1223
[pr-1228]: https://github.com/opentibiabr/otservbr-global/pull/1228
[pr-1230]: https://github.com/opentibiabr/otservbr-global/pull/1230
[pr-1231]: https://github.com/opentibiabr/otservbr-global/pull/1231
[pr-1232]: https://github.com/opentibiabr/otservbr-global/pull/1232
[pr-1233]: https://github.com/opentibiabr/otservbr-global/pull/1233
[pr-1236]: https://github.com/opentibiabr/otservbr-global/pull/1236
[pr-1237]: https://github.com/opentibiabr/otservbr-global/pull/1237
[pr-1238]: https://github.com/opentibiabr/otservbr-global/pull/1238
[pr-1241]: https://github.com/opentibiabr/otservbr-global/pull/1241
[pr-1243]: https://github.com/opentibiabr/otservbr-global/pull/1243
[pr-1246]: https://github.com/opentibiabr/otservbr-global/pull/1246
[pr-1247]: https://github.com/opentibiabr/otservbr-global/pull/1247
[pr-1268]: https://github.com/opentibiabr/otservbr-global/pull/1268
[pr-1271]: https://github.com/opentibiabr/otservbr-global/pull/1271
[pr-1280]: https://github.com/opentibiabr/otservbr-global/pull/1280
[pr-1282]: https://github.com/opentibiabr/otservbr-global/pull/1282

[issue-1229]: https://github.com/opentibiabr/otservbr-global/pull/1229
[issue-1279]: https://github.com/opentibiabr/otservbr-global/pull/1279

[gh-yohanaugusto]: https://github.com/yohanaugusto
[gh-omarcopires]: https://github.com/omarcopires
[gh-oualid6496]: https://github.com/oualid6496
[gh-andersonfaaria]: https://github.com/andersonfaaria
[gh-costallat]: https://github.com/costallat
[gh-Riicksouzaa]: https://github.com/Riicksouzaa
[gh-dudantas]: https://github.com/dudantas
[gh-oalbsilva]: https://github.com/oalbsilva
[gh-Heitortadeu]: https://github.com/Heitortadeu
[gh-Heitortadeu]: https://github.com/hyresu
[gh-Heitortadeu]: https://github.com/nickolasdeluca
