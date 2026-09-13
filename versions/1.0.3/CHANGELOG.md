# Changelog

## 1.0.3

- Ajout de **PapysLand Menu 0.4.0** comme dépendance officielle du modpack.
- Ajout de l'identité visuelle **PapysLand — Saison 1** au menu principal et à l'écran de sélection du personnage.
- Remplacement de **Build_Camera_Unofficial_Valheim_1_0_Fix 1.2.0** par **Stonaar ValheimBuildCamera 0.1.11**.
- **ValheimBuildCamera** s'active avec **F6** lorsque le marteau est équipé.
- Suppression de **Balrond Shipyard 1.6.7**, identifié pendant les tests comme source des erreurs Unity « Cannot instantiate objects with a parent which is persistent ».
- Le décor 3D animé, la caméra, les transitions et l'interface d'origine de Valheim restent inchangés par PapysLand Menu.
- Le **Grand Livre V8**, ses **2 500 quêtes**, **PapysLand VSG QoL 0.3.6**, le patch EpicLoot et les autres configurations PapysLand restent inchangés.
- Le nombre total de dépendances reste à **38** : 2 dépendances retirées et 2 ajoutées.

## 1.0.2

- Correction du README : suppression du titre resté en version 1.0.0.
- Mise à jour de la présentation, des instructions d'installation et des versions de référence.
- Documentation du patch EpicLoot introduit en 1.0.1 et des résultats des tests.
- Ajout du problème Unity connu et des limites de validation.
- Mise à jour documentaire uniquement : aucun changement des mods, de leurs versions, des configurations ou des quêtes par rapport à la 1.0.1.

## 1.0.1

- Remplacement du fichier EpicLoot adventuredata.json complet par un patch PapysLand utilisant les configurations de base d'EpicLoot 0.14.4.
- Ajout de 260 entrées GambleCosts personnalisées via ce patch.
- Suppression ciblée de l'entrée ArmorBerserkerLegs à 999 pièces ; conservation de celle à 400 pièces.
- Correction OUTDATED CONFIGS validée sur un profil vierge avec les 38 dépendances : deux démarrages sans popup, présence des ajouts PapysLand et une seule entrée ArmorBerserkerLegs à 400 pièces.
- PapysLand VSG QoL 0.3.6 chargé correctement ; Grand Livre accessible et deux quêtes testées avec succès.
- Aucun changement des 38 dépendances ni de leurs versions.
- Grand Livre V8 et PapysLand VSG QoL 0.3.6 inchangés.
- Problème connu : messages Unity « Cannot instantiate objects with a parent which is persistent » au chargement d'une partie, également reproduits en 1.0.0. Aucun blocage observé pendant les essais ; cause et impact complet non déterminés.

## 1.0.0

- Première publication publique de **PapysLand Modpack**.
- 37 mods sélectionnés + **PapysLand VSG QoL 0.3.6** comme dépendance officielle.
- Grand Livre PapysLand V8 : **2 500 quêtes** (150 principales + 2 350 secondaires).
- Configurations PapysLand essentielles intégrées.
- Configuration EpicLoot personnalisée conservée.
- Suppression des sauvegardes/progressions personnelles et des résidus connus de mods retirés ou incompatibles.
- PapysLand VSG QoL n'est plus embarqué en DLL dans le modpack : il est installé proprement via Thunderstore.