---
layout: post
title:  "Fortnightly Update #07"
date:   2020-06-30 11:00:00 -0400
categories: updates
excerpt: "A lot of issues resolved on the map and minor issues on the store, monsters, and quests"
---

#### Special Thanks for our Donators
- Draconic Otserver
- Michael Williams

### Added
- Re add lua include check: [#1361][pr-1361] by [costallat][gh-costallat]


### Changed
- Close connection from exceeding packet per second: [#1366][pr-1366] by [lBaah][gh-lbaah]


### Removed
- Removes log: [#1412][pr-1412] by [costallat][gh-costallat]


### Fixed
- Fix spawn hireling name (linux case sensitive): [#1359][pr-1359] by [dudantas][gh-dudantas]
- Access cobra bastion and fix feyrist shrines entrance: [#1376][pr-1376] by [Heitortadeu][gh-heitortadeu]
- Golden prision key script fix and Prince Drazzak loot table small fix: [#1383][pr-1383] by [nickolasdeluca][gh-nickolasdeluca]
- Tournament carpet doesn't work, resolves [#1377][issue-1377]: [#1389][pr-1389] by [MajestyOTBR][gh-majestyotbr]
- Fixed problemm with Grimvale spawn: [#1385][pr-1385] by [FRReinert][gh-frreinert]
- Fixes in dawnport and action creation at server startup: [#1371][pr-1371] by [dudantas][gh-dudantas]
- Fix Glooth Brigand looktype, resolves [#1356][issue-1356]: [#1401][pr-1401] by [gpedro][gh-gpedro]
- Fix Crackler Transform, resolves [#1388][issue-1388]: [#1404][pr-1404] by [lBaah][gh-lbaah]
- Fix mount clientid on store table, resolves [#1391][issue-1391]: [#1406][pr-1406] by [lBaah][gh-lbaah]
- Force secure mode, resolves [#1255][issue-1255]: [#1407][pr-1407] by [lBaah][gh-lbaah]
- Allow walkthrough on non-pvp, resolves [#1277][issue-1277]: [#1408][pr-1408] by [lBaah][gh-lbaah]
- Map fixes [#1410][pr-1410] by [gpedro][gh-gpedro]:
  - Resolves [#1239][issue-1239]
  - Resolves [#1333][issue-1333]
  - Resolves [#1334][issue-1334]
  - Resolves [#1335][issue-1335]
  - Resolves [#1363][issue-1363]
  - Resolves [#1375][issue-1375]
  - Resolves [#1386][issue-1386]
  - Resolves [#1392][issue-1392]
- Fix greeting Atrad requires Assassin Outfit: [#1405][pr-1405] by [lBaah][gh-lbaah]
- Fix bow of Cataclysm skill, resolves [#1390][issue-1390]: [#1413][pr-1413] by [lBaah][gh-lbaah]
- Fix event name typo in creaturescripts.xml: [#1374][pr-1374] by [dudantas][gh-dudantas]
- Small fixes on the datapack [#1384][pr-1384] by [dudantas][gh-dudantas]:
  - Oberon lever correction
  - Correction in the boss levers system, added GlobalStorage to check if the room cleaning event has already been executed or not, thus preventing the boss from cleaning before the scheduled time, while a team is inside
  - Also fixed a bug that allows players to enter monsters / summons instead of other players, now only players will enter the boss rooms
  - Added heal magic on trainers
  - Added a Game.setGlobalStorage in the clearRoom function
  - Fixed bug in the corpses' unique range (from the startup folder)

---

If you like our project, feel free to pay us a coffee, pizza or something else. [Click here][donation-link] check donations methods.

[donation-link]: {{ '/donation' | relative_url }}

[commit-e69199ab2]: https://github.com/opentibiabr/otservbr-global/commit/e69199ab2
[commit-3fdc41f2e]: https://github.com/opentibiabr/otservbr-global/commit/3fdc41f2e

[pr-1359]: https://github.com/opentibiabr/otservbr-global/pull/1359
[pr-1361]: https://github.com/opentibiabr/otservbr-global/pull/1361
[pr-1366]: https://github.com/opentibiabr/otservbr-global/pull/1366
[pr-1371]: https://github.com/opentibiabr/otservbr-global/pull/1371
[pr-1374]: https://github.com/opentibiabr/otservbr-global/pull/1374
[pr-1376]: https://github.com/opentibiabr/otservbr-global/pull/1376
[pr-1383]: https://github.com/opentibiabr/otservbr-global/pull/1383
[pr-1384]: https://github.com/opentibiabr/otservbr-global/pull/1384
[pr-1385]: https://github.com/opentibiabr/otservbr-global/pull/1385
[pr-1389]: https://github.com/opentibiabr/otservbr-global/pull/1389
[pr-1401]: https://github.com/opentibiabr/otservbr-global/pull/1401
[pr-1404]: https://github.com/opentibiabr/otservbr-global/pull/1404
[pr-1405]: https://github.com/opentibiabr/otservbr-global/pull/1405
[pr-1406]: https://github.com/opentibiabr/otservbr-global/pull/1406
[pr-1407]: https://github.com/opentibiabr/otservbr-global/pull/1407
[pr-1408]: https://github.com/opentibiabr/otservbr-global/pull/1408
[pr-1410]: https://github.com/opentibiabr/otservbr-global/pull/1410
[pr-1412]: https://github.com/opentibiabr/otservbr-global/pull/1412
[pr-1413]: https://github.com/opentibiabr/otservbr-global/pull/1413

[issue-1239]: https://github.com/opentibiabr/otservbr-global/issues/1239
[issue-1255]: https://github.com/opentibiabr/otservbr-global/issues/1255
[issue-1277]: https://github.com/opentibiabr/otservbr-global/issues/1277
[issue-1333]: https://github.com/opentibiabr/otservbr-global/issues/1333
[issue-1334]: https://github.com/opentibiabr/otservbr-global/issues/1334
[issue-1335]: https://github.com/opentibiabr/otservbr-global/issues/1335
[issue-1356]: https://github.com/opentibiabr/otservbr-global/issues/1356
[issue-1363]: https://github.com/opentibiabr/otservbr-global/issues/1363
[issue-1375]: https://github.com/opentibiabr/otservbr-global/issues/1375
[issue-1377]: https://github.com/opentibiabr/otservbr-global/issues/1377
[issue-1386]: https://github.com/opentibiabr/otservbr-global/issues/1386
[issue-1388]: https://github.com/opentibiabr/otservbr-global/issues/1388
[issue-1390]: https://github.com/opentibiabr/otservbr-global/issues/1390
[issue-1391]: https://github.com/opentibiabr/otservbr-global/issues/1391
[issue-1392]: https://github.com/opentibiabr/otservbr-global/issues/1392

[gh-dudantas]: https://github.com/dudantas
[gh-costallat]: https://github.com/costallat
[gh-lbaah]: https://github.com/lBaah
[gh-nickolasdeluca]: https://github.com/nickolasdeluca
[gh-majestyotbr]: https://github.com/MajestyOTBR
[gh-frreinert]: https://github.com/FRReinert
[gh-heitortadeu]: https://github.com/Heitortadeu
[gh-gpedro]: https://github.com/gpedro
