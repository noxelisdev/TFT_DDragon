# _Teamfight Tactics_ - Data Dragon

Do you want to use DDragon for an another game from _Riot Games_? Check the _Data Dragon_ repository for [_2XKO_](https://github.com/noxelisdev/2XKO_DDragon), [_League of Legends_](https://github.com/noxelisdev/LoL_DDragon), or [_Legends of Runeterra_](https://github.com/noxelisdev/LoR_DDragon), or [_Valorant_](https://github.com/noxelisdev/Valorant_DDragon).

## Introduction
_Data Dragon_ is a package of files you can use for your projects about [_Teamfight Tactics_](https://teamfighttactics.leagueoflegends.com), distributed by Riot Games. A new version of Data Dragon is released some days after each new set release. This repository allows you to update automatically all files more easily.

Don't forget that new patchs will be added right after their release on Riot Games' Developers website, but it takes often many days to come.

Since patch 13.1 of _League of Legends_, data from _Teamfight Tactics_ was included with _League_ ones, in the same DDragon bundle. This repository was stopped when patch 13.12 (and set 9) was released, and only the _LoL_ one was updated since then. On June 12th 2026, Riot Games annonced that [_TFT_ is moving to Unreal Engine](https://teamfighttactics.leagueoflegends.com/en-us/news/game-updates/faq-tft-unreal-migration/) with the release of set 18 on August 12th 2026. This repository has been reactivated, and all data from _TFT_ has been moved from the _League_ DDragon to this one, including additional content and past content.

Note that, even if _Teamfight Tactics_ has it own patch naming scheme since the third patch of set 13, this change isn't reflected in this repository before set 16 to avoid any conflict with the _League of Legends_ patch naming scheme.

## Additional contents in this repository
This repository contains some additional files, not included in Data Dragon :

- Icons of all turbo badges (used for _Hyper Roll_ game mode)
- Icons of all _Double Up_ badges (used for _Double Up_ game mode)

## Patchs added to this repository for the current set
This list contains patchs from actual set. For all previous patchs of all previous sets, you can check [OLDPATCHS.md](OLDPATCHS.md).

The date in front of each patch represents the date when the patch was pushed to this repository, not the date when it was released by Riot Games. Corresponding sets releases will be explicitly written next to the patch number. Here's a list of all patchs of current sets included in this repository :

- (June 13th, 2026) 15.10
- (June 13th, 2026) 15.9
- (June 13th, 2026) 15.8
- (June 13th, 2026) 15.7 - Set 14 (Cyber City)

## Missing patchs for the current set
There is currently no missing patch for the current set.

## Note about Sets 6 and 7
Set 6 has been added with some assets available on the [Set 6 Promo Assets Page](https://express.adobe.com/page/ficXgtBZ0f3xd/) (published by _Riot Games_) or/and on [_CommunityDragon_](https://raw.communitydragon.org/latest/cdragon/tft/). Set 7 used the same process, but only with _CommunityDragon_.

This was needed because _Riot Games_ didn't release at all an official version of _Data Dragon_ for these sets of _Teamfight Tactics_. Keep in mind that they are partially complete, and it can contains some mistakes. Feel free to help me to improve these sets if you can (issues are open if you want to)!

Due to what I said just above, keep in mind that `items.json`, `champions.json` and `traits.json` files can contains some elements from previous sets, which are not used anymore. Some items pictures can be missing or incorrect too.

There is also some differences between official _Data Dragon_ files and the temporary reconstructed folder:
- In `traits.json`, `type` doesn't exist.
- In `traits.json`, `style` (in `sets` array) is a number (like 1), and not a string (like `silver`).
- In `traits.json`, the `description` contains some variables strings (like `@Duration@`), which are not included.
- In `items.json`, the `description` contains some variables strings (like `@Duration@`), which are not included.
- In `items.json`, `isElusive` and `isRadiant` doesn't exists.

Sets 6 and 7 have been recreated, but their corresponding mid-sets will not be available in this repository.