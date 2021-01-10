---
layout: post
title:  "Fortnightly Update #06"
date:   2020-06-15 11:00:00 -0400
categories: updates
excerpt: breaking change: the map is now zip format instead of rar. feature: hirelings made by jlcvp
---

#### Special Thanks for our Donators
- Unfortunately, we did not have any donations in the period. If you like our project, feel free to pay us a coffee, pizza, or something else. [Click here][donation-link] check donations methods.

### Added
- Feat: dawnport revision and fixes: [#1134][pr-1134] by [dudantas][gh-dudantas]
- Feat: adding custom map (containing training room and npcs shop): [#1299][pr-1299] by [dudantas][gh-dudantas]
- Hirelings: [#1194][pr-1194] by [jlcvp][gh-jlcvp]
- Print duplicate storages: [#1158][pr-1158] by [andersonfaaria][gh-andersonfaaria]
- Add DB account refactor migration and fixes Windows warning: [#1312][pr-1312] by [costallat][gh-costallat]
- Support for countMin in loot: [#1218][pr-1218] by [andersonfaaria][gh-andersonfaaria]


### Changed
- Refactored npc Captain Dreadnought: [3fdc41f2e][commit-3fdc41f2e] by [dudantas][gh-dudantas]
- Convert the map from rar to zip file: [#1306][pr-1306] by [dudantas][gh-dudantas]
- Update map from rar to zip (docker+gha): [#1313][pr-1313] by [costallat][gh-costallat]
- Refactor account class: [#1259][pr-1259] by [costallat][gh-costallat]
- NPC trade ability fixes + other missing npc dialogs: [#1269][pr-1269] by [nickolasdeluca][gh-nickolasdeluca]
- Feat: OTC and 12.x only compatibility: [#1195][pr-1195] by [dudantas][gh-dudantas], [FakeShinoda][gh-FakeShinoda], [lgrossi][gh-lgrossi]
- Improvement - Npc Callback onRemove: [#1204][pr-1204] by [andersonfaaria][gh-andersonfaaria]
- Some very useful functions: [#1234][pr-1234] by [andersonfaaria][gh-andersonfaaria]
- chore: reorganization and cleaning of the datapack: [#1325][pr-1325] by [dudantas][gh-dudantas]


### Removed
- Nothing xD

### Fixed
- Fix on captain dreadnought NPC related to [#1134][pr-1134]: [e69199ab2][commit-e69199ab2] by [dudantas][gh-dudantas]
- Resolves [#1278][issue-1278] carpets issue: [#1292][pr-1292] by [CharlySample][gh-CharlySample]
- Resolves [#1253][issue-1253] add lastday to the account table when purchasing premium in store: [#1291][pr-1291] by [dudantas][gh-dudantas]
- Some fixes in dawnport: [#1293][pr-1293] by [dudantas][gh-dudantas]
- Fix imbuement not removing money and items: [#1251][pr-1251] by [gerotib][gh-gerotib]
- Fix Quest Reward (Mintwallin Cyclops and Mad Mage Room): [#1301][pr-1301] by [vinioliveirasilva][gh-vinioliveirasilva]
- Summon corrections: [#1248][pr-1248] by [gerotib][gh-gerotib]
- Several small datapack fixes: [#1307][pr-1307] by [dudantas][gh-dudantas]
- Fix getMinMaxValues attackSkill with distance weapons: [#1060][pr-1060] by [Oen44][gh-Oen44]
- Fix Hirelings (on store): [#1316][pr-1316] by [MajestyOTBR][gh-MajestyOTBR]
- Fix groups access bug (this gave access from adm to tutors): [#1321][pr-1321] by [dudantas][gh-dudantas]
- Fix migration from older db: [#1320][pr-1320] by [costallat][gh-costallat]
- Resolves [#1281][issue-1281] (imbue equiped items by hotkey): [#1327][pr-1327] by [YohanAugusto][gh-YohanAugusto]
- Fix aleta grav on closed door: [#1103][pr-1103] by [gpedro][gh-gpedro], [MillhioreBT][gh-MillhioreBT]
- Fix memory leak, fix build on Ubuntu 20.04 and Debian 10 and update GHA checks: [#1330][pr-1330] by [costallat][gh-costallat]
- Issue Fix Pack: [#1252][pr-1252] by [FakeShinoda][gh-FakeShinoda]
- Resolves [#1350][issue-1350] (wrong door id): [#1351][pr-1351] by [dudantas][gh-dudantas]
- Fix typo in the arena 10x10 script: [#1352][pr-1352] by [dudantas][gh-dudantas]
- Remove greetCallback from yaman and alesar, resolves [#1354][issue-1354]: [#1355][pr-1355] by [dudantas][gh-dudantas]
- Exhaustion fix (exevo gran mort): [#1324][pr-1324] by [Tazer89][gh-Tazer89]

---

If you like our project, feel free to pay us a coffee, pizza or something else. [Click here][donation-link] check donations methods.

[donation-link]: {{ '/donation' | relative_url }}

[commit-e69199ab2]: https://github.com/opentibiabr/otservbr-global/commit/e69199ab2
[commit-3fdc41f2e]: https://github.com/opentibiabr/otservbr-global/commit/3fdc41f2e

[pr-1060]: https://github.com/opentibiabr/otservbr-global/pull/1060
[pr-1103]: https://github.com/opentibiabr/otservbr-global/pull/1103
[pr-1134]: https://github.com/opentibiabr/otservbr-global/pull/1134
[pr-1158]: https://github.com/opentibiabr/otservbr-global/pull/1158
[pr-1194]: https://github.com/opentibiabr/otservbr-global/pull/1194
[pr-1195]: https://github.com/opentibiabr/otservbr-global/pull/1195
[pr-1204]: https://github.com/opentibiabr/otservbr-global/pull/1204
[pr-1218]: https://github.com/opentibiabr/otservbr-global/pull/1218
[pr-1234]: https://github.com/opentibiabr/otservbr-global/pull/1234
[pr-1248]: https://github.com/opentibiabr/otservbr-global/pull/1248
[pr-1251]: https://github.com/opentibiabr/otservbr-global/pull/1251
[pr-1252]: https://github.com/opentibiabr/otservbr-global/pull/1252
[pr-1259]: https://github.com/opentibiabr/otservbr-global/pull/1259
[pr-1269]: https://github.com/opentibiabr/otservbr-global/pull/1269
[pr-1291]: https://github.com/opentibiabr/otservbr-global/pull/1291
[pr-1292]: https://github.com/opentibiabr/otservbr-global/pull/1292
[pr-1293]: https://github.com/opentibiabr/otservbr-global/pull/1293
[pr-1299]: https://github.com/opentibiabr/otservbr-global/pull/1299
[pr-1301]: https://github.com/opentibiabr/otservbr-global/pull/1301
[pr-1306]: https://github.com/opentibiabr/otservbr-global/pull/1306
[pr-1307]: https://github.com/opentibiabr/otservbr-global/pull/1307
[pr-1312]: https://github.com/opentibiabr/otservbr-global/pull/1312
[pr-1313]: https://github.com/opentibiabr/otservbr-global/pull/1313
[pr-1316]: https://github.com/opentibiabr/otservbr-global/pull/1316
[pr-1320]: https://github.com/opentibiabr/otservbr-global/pull/1320
[pr-1321]: https://github.com/opentibiabr/otservbr-global/pull/1321
[pr-1324]: https://github.com/opentibiabr/otservbr-global/pull/1324
[pr-1325]: https://github.com/opentibiabr/otservbr-global/pull/1325
[pr-1327]: https://github.com/opentibiabr/otservbr-global/pull/1327
[pr-1330]: https://github.com/opentibiabr/otservbr-global/pull/1330
[pr-1351]: https://github.com/opentibiabr/otservbr-global/pull/1351
[pr-1352]: https://github.com/opentibiabr/otservbr-global/pull/1352
[pr-1355]: https://github.com/opentibiabr/otservbr-global/pull/1355

[issue-1278]: https://github.com/opentibiabr/otservbr-global/issues/1278
[issue-1253]: https://github.com/opentibiabr/otservbr-global/issues/1253
[issue-1281]: https://github.com/opentibiabr/otservbr-global/issues/1281
[issue-1350]: https://github.com/opentibiabr/otservbr-global/issues/1350
[issue-1354]: https://github.com/opentibiabr/otservbr-global/issues/1354

[gh-dudantas]: https://github.com/dudantas
[gh-CharlySample]: https://github.com/CharlySample
[gh-costallat]: https://github.com/costallat
[gh-gerotib]: https://github.com/gerotib
[gh-nickolasdeluca]: https://github.com/nickolasdeluca
[gh-vinioliveirasilva]: https://github.com/vinioliveirasilva
[gh-Oen44]: https://github.com/Oen44
[gh-jlcvp]: https://github.com/jlcvp
[gh-andersonfaaria]: https://github.com/andersonfaaria
[gh-MajestyOTBR]: https://github.com/MajestyOTBR
[gh-YohanAugusto]: https://github.com/YohanAugusto
[gh-MillhioreBT]: https://github.com/MillhioreBT
[gh-Tazer89]: https://github.com/Tazer89
[gh-FakeShinoda]: https://github.com/FakeShinoda
[gh-lgrossi]: https://github.com/lgrossi
[gh-gpedro]: https://github.com/gpedro
