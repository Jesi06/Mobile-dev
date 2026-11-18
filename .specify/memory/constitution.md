<!--
Sync Impact Report
Version change: unratified template → 1.0.0 (initial constitution)
Modified principles:
- Principe 1 (non défini) → I. Scan préalable à l'entrée
- Principe 2 (non défini) → II. Identification immédiate
- Principe 3 (non défini) → III. Interface en français
- Principe 4 (non défini) → IV. Actions minimales
- Principe 5 (non défini) → V. Périmètre centré sur la présence
Added sections: none
Removed sections: none
Follow-up TODO: confirm the original ratification date.
-->
# Gestion de présence des étudiants — Constitution

## Core Principles

### I. Scan préalable à l'entrée
L’application MUST permettre de scanner l’identifiant de chaque étudiant avant son entrée en classe. Le scan est le parcours central de l’enregistrement des présences.

### II. Identification immédiate
Après chaque scan reconnu, l’application MUST afficher automatiquement le nom, le prénom et l’identifiant de l’étudiant. Ces informations MUST être visibles sans action supplémentaire.

### III. Interface en français
Tous les textes destinés aux utilisateurs MUST être en français. Les libellés et les retours du parcours de scan MUST être clairs et faciles à comprendre.

### IV. Actions minimales
Le parcours courant MUST limiter les actions aux seules étapes nécessaires pour scanner l’identifiant et consulter l’identification affichée. L’interface MUST éviter les écrans et commandes complexes qui ne servent pas directement ce parcours.

### V. Périmètre centré sur la présence
Les fonctionnalités MUST servir la gestion de présence des étudiants. Toute fonctionnalité supplémentaire MUST être nécessaire à ce but et ne pas compliquer le parcours de scan.

## Exigences produit

L’application est un outil simple de gestion de présence des étudiants en classe. Le parcours de référence commence par le scan de l’identifiant avant l’entrée en classe et présente automatiquement l’identité correspondante après le scan.

## Qualité et validation

Les changements MUST être vérifiés au regard des cinq principes. La validation du parcours de scan MUST confirmer qu’un scan reconnu affiche automatiquement le nom, le prénom et l’identifiant, et que les textes du parcours sont en français. Les changements d’interface MUST préserver un parcours direct, sans actions superflues.

## Governance

Cette constitution est la référence pour les décisions produit et les revues de changements. Toute modification de ses principes ou exigences MUST être documentée et approuvée avant intégration.

Les versions suivent le versionnage sémantique MAJOR.MINOR.PATCH : MAJOR pour une modification incompatible des règles, MINOR pour l’ajout ou l’élargissement substantiel d’une règle, et PATCH pour une clarification sans changement de sens.

Les revues MUST vérifier la conformité des changements concernés aux principes et aux critères de validation. Toute exception MUST être justifiée et approuvée dans le cadre de la revue.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE): date d’adoption originale inconnue | **Last Amended**: 2026-11-18
