---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- hdr-changelog.md v1.0.0.1
New Shepard (NSHPD)
created: 13 May 2022
updated: 05 Nov 2022
CC BY-ND 4.0 by zer0Kerbal -->  
# Changelog  
  
| modName    | New Shepard (NSHPD)                                               |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | Matheo G and zer0Kerbal                                           |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/210741-*/) |
| github     | (https://github.com/zer0Kerbal/NewShepard)                        |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/NewShepard)           |
| spacedock  | (https://spacedock.info/mod/2181)                                 |
| ckan       | NewShepard                                                        |

## Version 1.2.99.0-adoption - `<Thank you Matheo G>` edition

* Released
  * on 25 Nov 2022
  * for Kerbal Space Program 1.12.4
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 1.2.99.0

* Combined the two versions of this parts addon into just one:
  * base is meant for stock
  * includes RSS patch (see below)
* booster/capsule stats need polish/overhaul
* Real Solar System patch needs much refinement
* models (.mu) need someone more skilled than me to update
  * Booster: animations interfering with each other, legs (stock leg modules)/airbrakes
  * Capsule: hatch, light(s), parachute
  * IVA is begging for a 'Transparent Pod' treatment and maybe some lovely curtains
* from 30mb release size down to just under 9mb

### Archival Releases

* 1.2.0.0-release - `<Archival>` edition
* 1.1.0.0-release - `<Archival>` edition
* 1.0.1.0-release - `<Archival>` edition
* 1.0.0.0-release - `<Archival>` edition

### Create Legal Mumbo Jumbo 1.2.99.0

* Create Legal Mumbo Jumbo
  * license check
  * offline documentation
  * _Legal
    * screenshots and pdfs
    * adoptionLetters
    * communications concerning
  * _Links/
    * link(s) saved
  * docs/LegalMumboJumbo
    * [License.md]
    * FORUM-##.png's
      * public documentation
  * GitHub: :octocat:
    * LICENSE
    * [license].txt
  * CurseForge
  * SpaceDock
  * CKAN

### Create 1.2.99.0

* Documentation
  * readme
  * deploy to:
    * CurseForge Description page 🤬
    * Forum Original Post 🐰
    * SpaceDock Information page 🌮
  * release notes
  * [changelog.md]
  * update /docs/
* HeroLogo.png
  * copy/convert to HeroLogo.jpg
* Agency
* closes #6 - Create HeroLogo.png
* closes #43 - Create Agency
* GitHub Pages
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #5 - Create GitHub Pages

### Update Parts 1.2.99.0

* linting
* modernizing
* and so much more

### Part Asset Updates 1.2.99.0

* create Assets/ folder
* Asset conversions
  * convert from mesh to MODEL {}
  * convert from .mbm/.tga to .png/.dds
  * <pieds1.1Couleur.mbm> 12.289mb --> .png 94kb = 12.195mb reduction
  * <reservoirCouleur 1.mbm> 12.289mb --> .png 594kb = 11.695mb reduction
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures (6.54mb reduction)
  * <int$Normal.png> 975kb reduction
  * <NormalMap.png> 2.351mb reduction
  * <solCouleur_de_Surface.png> 125kb reduction
  * <solNormal.png> 3.134mb reduction
  * <coussin_4Couleur.png> 21kb reduction
  * <coussin3Couleur.png> 21kb reduction
  * <int$Couleur.png> 77kb reduction
  * duplicate models
* relocate part.cfg to Parts/
* closes #9 - Part Asset Updates

### Localization 1.2.99.0

* Create
  * directory and contents
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Add localized tags to parts
* Create
  * <GhostParts.cfg> v1.3.0.0
    * part names have changed
  * <NewShepard.cfg> v1.0.0.0
    * adds localized tags to parts
* closes #24 - English <en-us.cfg>
* closes #41 - Part Localization
* closes #42 - Part Tags
* closes #8 - Create Localization directory and contents
* updates #23 - Localization - Master

### Compatibility 1.2.99.0

* Create
  * [RealSolarSystem.cfg] v1.0.0.0
  * [kOS.cfg] v1.0.0.0

### Update License 1.2.99.0

* Updated License:
  * to GPL-2.0
  * was: WTFPL

### Status 1.2.99.0

* Issues
  * closes #1 - New Shepard (NSHPD) 1.2.99.0-adoption `<Thank you Matheo G>` edition
  * closes #2 - 1.1.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 1.1.99.0 Create Documentation
  * closes #4 - 1.1.99.0 Create Social Media Presence

---

## Version 1.2.0.0-release - `<Archival>` edition

* Released
  * on 23 Jul 2019
  * for Kerbal Space Program 1.6.1
  * by [Matheo G](https://forum.kerbalspaceprogram.com/index.php?/profile/185325-*/)

* Kos processor added
* Command module added
* Compatibility with 1.6.1 added
* Transmitter added

### Status 1.2.0.0

* Issues
  * closes #7 - Archival Releases
  * closes #22 - 1.2.0.0-release - `<Archival>` edition

---

## Version 1.1.0.0-release - `<Archival>` edition

* Released
  * on 14 Jul 2019
  * for Kerbal Space Program 1.4.2
  * by [Matheo G](https://forum.kerbalspaceprogram.com/index.php?/profile/185325-*/)

* ejection system added

### Status 1.1.0.0

* Issues
  * updates #7 - Archival Releases
  * closes #21 - 1.1.0.0-release - `<Archival>` edition

---

## Version 1.0.1.0-release - `<Archival>` edition

* Released
  * on 14 Jul 2019
  * for Kerbal Space Program 1.4.2
  * by [Matheo G](https://forum.kerbalspaceprogram.com/index.php?/profile/185325-*/)

* Bug Fix

### Status 1.0.1.0

* Issues
  * updates #7 - Archival Releases
  * closes #20 - 1.0.1.0-release - `<Archival>` edition

---

## Version 1.0.0.0-release - `<Archival>` edition

* Released
  * on 14 Jul 2019
  * for Kerbal Space Program 1.4.2
  * by [Matheo G](https://forum.kerbalspaceprogram.com/index.php?/profile/185325-*/)

* Initial release
* Bug fix for stock version

### Status 1.0.0.0

* Issues
  * updates #7 - Archival Releases
  * closes #19 - 1.0.0.0-release - `<Archival>` edition

---
