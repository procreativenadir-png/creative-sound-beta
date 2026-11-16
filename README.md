# Creative Sound — bêta privée

Panneau pour parcourir, écouter et poser ta sonothèque dans **DaVinci Resolve Studio** (Windows). Projet jumeau de
Creative Look.

## Installer

1. Télécharge l'archive de la dernière version dans **Releases** (à droite de cette page).
2. Décompresse-la, ferme DaVinci Resolve, puis double-clique sur **Installer Creative Sound.bat**.
3. Ouvre Resolve Studio : Workspace > Workflow Integrations > **Creative Sound**.

Les Workflow Integrations n'existent que dans Resolve Studio, pas dans la version gratuite.

## Premier lancement

Bouton **Dossiers** (en bas) > **Ajouter un dossier…** : choisis le ou les dossiers où sont tes sons. Rien n'est
copié ni déplacé. Le panneau lit les noms et les durées, puis range les sons par familles (whooshs, impacts,
risers, ambiances, bruitages, musique…). Sur une grosse sonothèque, la première lecture prend quelques minutes.

## L'essentiel

- **Survol** d'un son : écoute. **Clic** : lecteur avec forme d'onde. **Double-clic** : posé à la tête de lecture.
- **Lecteur** : clic = aller à un endroit, glisser = choisir un passage (« Poser le passage »), L = boucle.
- **Piste** : « Auto » pose sur la première piste audio libre ; A1 à A6 forcent une piste.
- **Temps fort** : un riser, un impact ou un whoosh est calé pour que son moment fort tombe sur la tête de lecture.
- **Recherche** en français ou en anglais (pluie = rain), fautes de frappe pardonnées.
- **Court / Moyen / Long**, tri par durée, et le dé **Surprends-moi**.
- Dans Resolve, le son arrive dans un chutier « Creative Sound » avec un nom court ; le fichier garde son nom.

## Un problème, une idée ?

Ouvre une **Issue** sur ce dépôt (modèles « Problème » et « Idée »). Pour un problème, joins le fichier
`%APPDATA%\Creative Sound\debug.log`.
