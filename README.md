# Creative Sound — bêta

Panneau pour parcourir, écouter et poser ta sonothèque dans **DaVinci Resolve Studio** (Windows). Projet jumeau de
Creative Look.

## En bref

- **Il te faut** : Windows 10 ou 11 et DaVinci Resolve **Studio**. La version gratuite n'a pas les Workflow
  Integrations.
- **À télécharger** : uniquement `CreativeSound-…-beta.zip`, dans **Releases** (colonne de droite).
- **À ignorer** : « Source code (zip) » et « Source code (tar.gz) ». GitHub les ajoute tout seul sous chaque
  version ; ils ne contiennent que cette page, pas le plugin.
- **À fournir toi-même** : tes sons. Aucun n'est livré : le panneau range ta sonothèque (WAV, MP3, AIFF, FLAC, OGG,
  M4A) sans rien copier ni déplacer.
- **Rien d'autre à installer** : ni Python ni autre logiciel. Creative Look est un plugin à part : installe-le
  seulement si tu veux aussi ses looks.

### Dans l'archive

| Fichier | À faire |
|---|---|
| `Installer Creative Sound.bat` | **le seul à double-cliquer**, pour installer comme pour mettre à jour |
| dossier `Creative Sound` | n'y touche pas : l'installeur le copie au bon endroit |
| `LISEZ-MOI.txt` | le mode d'emploi en version courte |
| `Désinstaller Creative Sound.bat` | seulement pour retirer le panneau |

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
- **Poignée ⠿** du lecteur : glisse le son, ou seulement le passage choisi, où tu veux dans la timeline.
- **Effets** (bouton curseurs du lecteur) : hauteur, grave, aigu, étouffé, écho, espace, inverser, et des préréglages
  (Sous l'eau, Derrière une porte, Téléphone, Radio, Lointain, Rêve). Tu entends le résultat ; Poser et la poignée
  utilisent ce son retouché, enregistré dans le dossier Sons modifiés (bouton Dossiers > Sons modifiés). L'original
  ne change pas.
- **Tempo des musiques** : estimé à la première écoute, affiché en BPM ; tri « Tempo » dans la famille Musique,
  recherche « 120 bpm ». Une estimation se corrige à la main dans la fiche du son.
- **≈ Sons proches** (dans le lecteur) : les sons qui ressemblent le plus à celui-ci, du plus proche au moins proche.
- **Kits** : les sons d'un projet ou d'un client. Bouton Kit du lecteur pour en ajouter, vue Kits pour les retrouver.
- **Clic sur le nom** dans le lecteur : renommer un son ou le changer de famille. Ta correction reste, même après une
  nouvelle lecture des dossiers.
- **Licence** : la capsule du pack, dans le lecteur, passe par Client OK, Perso, À vérifier. Le filtre « Client OK »
  ne montre que les sons utilisables pour un client, et poser un son Perso ou À vérifier affiche un avertissement.
- Dans Resolve, le son arrive dans un chutier « Creative Sound » avec un nom court ; le fichier garde son nom.

### Raccourcis

Dans le panneau : **Espace** écouter, **Entrée** poser, **↑ ↓** son précédent ou suivant, **L** boucle, **D** au
hasard, **T** temps fort, **E** effets, **F** favori, **0 à 6** piste (0 = Auto), **+ et −** volume.

Dans Resolve, même quand le panneau n'a pas la main, avec **Ctrl+Alt+Maj** :

| Touche | Action |
|---|---|
| J / L | son précédent / suivant (et écoute) |
| K | écouter ou arrêter |
| P | poser à la tête de lecture |
| D | un son au hasard |

Ils ne prennent aucune touche de Creative Look : les deux panneaux peuvent tourner ensemble.

## Un problème, une idée ?

Ouvre une **Issue** sur ce dépôt (modèles « Problème » et « Idée »). Pour un problème, joins le rapport : bouton
**Dossiers** (en bas) > **Rapport pour le support** : l'Explorateur s'ouvre sur un fichier texte. Il contient les versions,
les réglages du panneau et la fin du journal, aucun son ni aucune image ; les chemins des dossiers peuvent contenir ton
nom d'utilisateur Windows.
