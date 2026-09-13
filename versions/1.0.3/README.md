# PapysLand Modpack

**PapysLand — made by PapyDiablo** est un modpack Valheim conçu pour enrichir l'aventure sans transformer le jeu en enfer artificiellement difficile.

## L'esprit PapysLand

Construction, exploration, immersion, qualité de vie et aventures. Le pack conserve une progression jouable, avec davantage de lieux à découvrir, de possibilités de construction et de systèmes RPG, sans chercher la difficulté pour la difficulté.

## Contenu principal

- **Grand Livre PapysLand V8 : 2 500 quêtes narratives et progressives** (150 principales + 2 350 secondaires).
- Exploration enrichie avec de nombreux lieux et donjons.
- Construction et décoration largement étendues.
- EpicLoot, Warfare et progression RPG intégrés.
- Plongée et exploration sous-marine.
- Plantation, terrassement et préparation du terrain améliorés.
- Améliorations de qualité de vie pour limiter les tâches répétitives sans supprimer la progression.
- **PapysLand VSG QoL 0.3.6 LOOP GUARD**, distribué comme dépendance officielle Thunderstore.
- **PapysLand Menu 0.4.0 — Saison 1**, avec identité visuelle PapysLand sur le menu principal et la sélection du personnage.
- **ValheimBuildCamera 0.1.11** remplace l'ancienne Build Camera non officielle ; activation avec **F6** lorsque le marteau est équipé.

## Installation

Créez un profil dédié dans r2modman, puis installez **PapysLand_Modpack** par **PapyDiablo** avec **Download with dependencies**.

La version **1.0.3** déclare **38 dépendances**, soit **39 packages au total** en comptant le modpack lui-même.

Lancez ensuite le jeu avec **Start modded** depuis ce profil.

Pour conserver la combinaison testée, utilisez les versions indiquées par le modpack. Une mise à jour individuelle des dépendances peut modifier son fonctionnement.

## Configuration EpicLoot

Depuis la version **1.0.1**, les personnalisations PapysLand sont distribuées sous forme de patch dans :

`BepInEx/config/EpicLoot/patches/`

Le modpack ne fournit plus de fichier complet :

`BepInEx/config/EpicLoot/baseconfig/adventuredata.json`

Cette migration permet de conserver les ajouts PapysLand tout en utilisant la configuration de base d'EpicLoot 0.14.4.

La correction a été testée sur un profil vierge avec le modpack complet : deux démarrages sans fenêtre **OUTDATED CONFIGS** et présence des ajouts personnalisés.

Ces essais concernent une installation propre ; la mise à jour d'un profil existant depuis la version 1.0.0 n'a pas encore été validée.

## Versions de référence

- Valheim **1.0.12**
- BepInExPack Valheim **5.4.2350**
- Jötunn **2.30.0**
- EpicLoot **0.14.4**
- ValheimServerGuide **0.16.1**
- PapysLand VSG QoL **0.3.6**
- PapysLand Menu **0.4.0**
- ValheimBuildCamera **0.1.11**

La liste complète des dépendances et de leurs versions figure dans le manifeste du modpack.

## Grand Livre

Le fichier de quêtes est fourni dans :

`BepInEx/config/ValheimServerGuide/guidance.yaml`

Il contient **150 quêtes principales** et **2 350 quêtes secondaires**.

PapysLand n'inclut aucune progression personnelle de joueur : chacun commence sa propre aventure.

## Correction 1.0.3

Les messages Unity **Cannot instantiate objects with a parent which is persistent** observés lors des tests ont été isolés sur **Balrond Shipyard 1.6.7**. Ce mod a donc été retiré de PapysLand 1.0.3.

L'ancienne **Build Camera Unofficial Valheim 1.0 Fix 1.2.0** a également été retirée et remplacée par **ValheimBuildCamera 0.1.11**.

Le décor 3D animé, les transitions, la caméra de menu et les boutons d'origine de Valheim sont conservés par **PapysLand Menu 0.4.0**.

## Historique des versions

Consultez l'onglet **Changelog** pour connaître les changements et l'onglet **Versions** pour identifier les versions publiées.

## Identité

**PapysLand — Plus qu'un jeu… un monde à notre image.**

**Made by PapyDiablo.**