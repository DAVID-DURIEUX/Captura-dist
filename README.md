# Captura — Distribution

Ce repo héberge les binaires des releases de **Captura + Klipp** — suite de capture d'écran (image / vidéo / hotkeys globaux) et éditeur d'annotations pour Windows.

➡️ **[Télécharger la dernière version](../../releases/latest)**

## À propos

Le code source vit dans un repo privé séparé. Ce repo public existe uniquement pour distribuer les binaires.

À chaque tag `v*.*.*`, un workflow GitHub Actions builde Captura + Klipp.Editor avec `dotnet publish` et publie une release ici contenant `Captura.zip` (les deux exes et leurs dépendances dans le même archive).

## Mises à jour

Captura vérifie automatiquement les mises à jour au démarrage. L'icône **↻** dans la titlebar, à côté du numéro de version, permet aussi de forcer un check manuel.

## Liens

- [Toutes les releases](../../releases)
