# Captura — Distribution

Ce repo héberge les binaires des releases de **Captura + Klipp** — suite de capture d'écran et éditeur d'annotations pour Windows.

➡️ **[Télécharger la dernière version](../../releases/latest)**

## Ce que fait l'application

**Captura** capture l'écran en un geste :

- **Image** — d'une zone, d'une fenêtre (au survol) ou de l'écran entier, avec **Impr. écran** depuis n'importe quelle application. Les captures de pages trop longues pour l'écran se font en **zone défilante**, assemblées automatiquement.
- **Vidéo** — enregistrement MP4 d'une zone ou d'un écran, avec le micro et le son système, décompte optionnel avant le départ.
- La capture est copiée dans le presse-papier et ouverte dans Klipp si vous le souhaitez. Captura reste discret dans la zone de notification et peut démarrer avec Windows.

**Klipp** retrouve et annote vos captures :

- **Bibliothèque** classée par date, avec recherche et filtres images / vidéos.
- **Annotations** : flèches, lignes, rectangles, cercles, surlignage, texte, légendes, étapes numérotées, timbres (✔ ✘ ⚠…) et flou pour masquer des données sensibles. Elles restent modifiables à tout moment, et l'enregistrement est automatique.
- **Retouches** : recadrage, rotation et retournement.
- **Extraction du texte** d'une capture (OCR), pour le copier au lieu de le retaper.
- Copie de l'image annotée ou export en PNG. Lecture des vidéos enregistrées.

## À propos

Le code source vit dans un repo privé séparé. Ce repo public existe uniquement pour distribuer les binaires.

À chaque tag `v*.*.*`, un workflow GitHub Actions builde Captura + Klipp.Editor avec `dotnet publish` et publie une release ici contenant `Captura.zip` (les deux exes et leurs dépendances dans le même archive).

## Mises à jour

Captura vérifie automatiquement les mises à jour au démarrage. L'icône **↻** dans la titlebar, à côté du numéro de version, permet aussi de forcer un check manuel.

## Liens

- [Toutes les releases](../../releases)
