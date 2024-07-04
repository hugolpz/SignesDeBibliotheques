# SignesDeBibliothèque
**SignesDeBibliothèque** ou **Lexique LSF pour des bibliothèques inclusives** est un lexique de vidéos en langues des signes, disponible en ligne, produite via l'outil d'enregistrement vidéo participatif LinguaLibre.org.

## Pourquoi SignesDeBibliothèque ?
Les bibliothèques publiques et les bibliothécaires cherchent à servir tous les usagers, incluant donc les usagers signants. Les bibliothécaires ont également manifesté leur intérêt pour langue des signes si des ressources d'apprentissage pertinentes leur sont fournies. Les technologies disponibles telles que le [studio d'enregistrement vidéo LinguaLibre](https://lingualibre.org/wiki/Special:RecordWizard) et les technologies web populaires rendent possible la création de systèmes d'apprentissage en ligne à faible coût pour satisfaire ce besoin.

## Solution
L'idée de SignesDeBibliothèque a été inspirée par la technologie LinguaLibre et d'un projet existant : 
* 64 [Signes de bibliothèque](https://bibliotheques-inclusives.fr/2019/08/signes-de-bibliotheque-repertoire-en-lsf-des-mots-et-expressions-utilises-en-bibliotheque), étudiants du lycée Marcel Sembat, Sotteville-en-Rouen, France.

En 2024, Amélie Barrio (co-responsable URFIST Occitanie) souligne la nécessité d'une liste en ligne, consultable et conviviale de signes pratiques pour les bibliothécaires.  Hugo Lopez, Wikimédien en résidence à l'URFIST et mainteneur de LinguaLibre/SignIt prend ce projet. L'URFIST Occitanie a donc :
- financé la réparation du studio d'enregistrement LinguaLibre SignIt
- identifié [92 expressions et signes pratiques](https://lingualibre.org/wiki/List:Fsl/Signes_de_bibliothèque) pour les bibliothécaires
- coordonné avec les associations toulousaines de langue des signes IRIS pour enregistrer cette liste lexicale plus large en vidéo
- créé l'applications web monopage pour visualiser et rechercher ces signes.

## Design
<img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/SignesDeBibliotheques-card.png" alt="Image" width="200" align="right">
Cette page présente la liste des mots et signes de SignesDeBibliothèque, avec :

- Bouton Contribuer : pointe vers notre studio d'enregistrement en ligne rapide.
- Mot en français
- Vidéo signée : enregistrée avec Lingualibre, stockée sur Wikimedia Commons
- Lien vers SpreadTheSign : un projet européen plus riche
- Lien vers les définitions de Wiktionary

<img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/SignesDeBibliotheques-gallery.png" alt="Image" align="center">
<br clear=all>

## Fonctionnalités avancées
- Rechercher et filtrer par expression française
- Partager une URL filtrée en ajoutant `?search=YourExpression` à l'URL

## Réutilisation des ensembles de données
Nos vidéos sont :
- stockées sur Wikimedia Commons dans [Category:Lingua_Libre_pronunciation-fsl](https://commons.wikimedia.org/wiki/Category:Lingua_Libre_pronunciation-fsl)
- comptées sur la [vignette LinguaLibre pour la LSF](https://hugolpz.github.io/LanguagesGallery/?search=French+sign+language#fsl)
- téléchargeable sur [Lingualibre datasets, via un zip](https://lingualibre.org/datasets/Q99628-fsl-French%20Sign%20Language.zip)

## Contribuer
Cette application web monopage fonctionne avec :
- HTML
- CSS
- VueJS

## Crédits
Classés par institutions : 
* URFIST Occitanie : Hugo Lopez, Amélie Barrio
* IRIS : Brigitte Dalle, Caroline.

## Licence
Voir le pied de page de [index.html](./index.html) et [LICENSE MPL](./LICENSE).
