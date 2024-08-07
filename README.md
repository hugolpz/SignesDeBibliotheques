# SignesDeBibliothèque
**SignesDeBibliothèque** ou **Lexique LSF pour des bibliothèques inclusives** est un lexique de vidéos en langues des signes, disponible en ligne, produite via l'outil d'enregistrement vidéo participatif LinguaLibre.org.

## Pourquoi SignesDeBibliothèque ?
Les bibliothèques publiques et les bibliothécaires cherchent à servir tous les usagers, ce qui inclue les usagers signants. Les bibliothécaires ont également manifesté leur intérêt pour langue des signes si des ressources d'apprentissage pertinentes leur sont fournies. Les technologies disponibles telles que le [studio d'enregistrement vidéo LinguaLibre](https://lingualibre.org/wiki/Special:RecordWizard) et les technologies web populaires rendent possible la création de systèmes d'apprentissage en ligne à faible coût pour satisfaire ce besoin.

## Solution
L'idée de SignesDeBibliothèque a été inspirée par la technologie LinguaLibre et d'un projet existant : 
* 64 [Signes de bibliothèque](https://bibliotheques-inclusives.fr/2019/08/signes-de-bibliotheque-repertoire-en-lsf-des-mots-et-expressions-utilises-en-bibliotheque), étudiants du lycée Marcel Sembat, Sotteville-en-Rouen, France.

En 2024, Amélie Barrio (co-responsable URFIST Occitanie) souligne la nécessité d'une liste en ligne, consultable et conviviale de signes pratiques pour les bibliothécaires.  Hugo Lopez, Wikimédien en résidence à l'URFIST et mainteneur de LinguaLibre/SignIt prend ce projet. L'association toulousaine IRIS qui [promeut l'apprentissage de la LSF](https://iris-lsf.com/index.php/2024/06/18/pourquoi-apprendre-la-lsf/), a souhaité contribuer au développement de ce lexique (Brigitte Dalle).

L'URFIST Occitanie et IRIS ont donc :
- financé la réparation du studio d'enregistrement LinguaLibre SignIt (URFIST)
- identifié [92 expressions et signes pratiques](https://lingualibre.org/wiki/List:Fsl/Signes_de_bibliothèque) pour les bibliothécaires (URFIST + IRIS)
- coordonné avec l'association IRIS le vidéo enregistrement de cette liste lexicale (URFIST + IRIS)
- créé l'applications web monopage pour visualiser et rechercher ces signes (URFIST)

## Design
<img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/SignesDeBibliotheques-card.png" alt="Image" width="200" align="right">
Cette page présente la liste des mots et signes de SignesDeBibliothèque, avec :

- Mot en français
- Vidéo signée : enregistrée avec Lingualibre, stockée sur Wikimedia Commons
- Lien vers SpreadTheSign : un projet européen plus riche
- Lien vers les définitions de Wiktionary

La page contient également:
- Un bouton appelant à contribuer : pointe vers notre studio d'enregistrement video en ligne.
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
| URFIST Occitanie | IRIS
| --- | --- |
| Amélie Barrio<br>Hugo Lopez | Brigitte Dalle<br>Caroline
| <img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/URFIST_Occitanie-2023.png" alt="" height="80" align=""> <img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/SICD-UT.png" alt="" height="80" align=""> | <img src="https://raw.githubusercontent.com/hugolpz/SignesDeBibliotheques/main/assets/IRIS-banner.png" alt="" height="80" align="">

## Licence
Voir le pied de page de [index.html](./index.html) et [LICENSE MPL](./LICENSE).
