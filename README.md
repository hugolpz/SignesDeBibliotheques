# SignesDeBibliothèque
**SignesDeBibliothèque** is searchable gallery of sign languages videos produced via crowd sourcing video recording tool LinguaLibre.org.

## Why SignDeBibliothèque ?
Public libraries and librarians are looking to serve all citizens, incluging the significant part of the population is hearing issues. Librarians also manifested interest to lear basic sign language if provided with relevant learning resources. Available technologies such as LinguaLibre video recording studios and popular web technologies makes the creation of low cost e-learning system possible, in order to satisfy this need.


## Solution
The idea of SignDeBibliothèque was inspired by LinguaLibre technology and existing project: 
* 64 [Signes de bibliothèque](https://bibliotheques-inclusives.fr/2019/08/signes-de-bibliotheque-repertoire-en-lsf-des-mots-et-expressions-utilises-en-bibliotheque), students from the Marcel Sembat high school, Sotteville-en-Rouen, France.In 2024, Amélie Barrio, co-responsable URFIST Occitanie and working with libraries of Occitanie region, pointed out the need for an human friendly, online, searchable base of practical signs for Librarians. URFIST Occitanie therefore :
- funded LinguaLibre SignIt recording studio repare
- created [a 92 signs list](https://lingualibre.org/wiki/List:Fsl/Signes_de_bibliothèque) for librarians
- coordinated with Toulousean signing associations to video record a larger and video lexicon
- created the single page apps to visualize and search those.


## Design
<img src="https://github.com/hugolpz/LanguagesGallery/assets/1420189/3a81cdbc-ccdd-4f98-8896-64a4d7d0cca3" alt="Image" width="300" align="right">
This page presents Lingualibre.org's statistics on a per languages basis with:

- Language name (Wikidata)
- Unique words vs recordings ratio. (Lingualibre)
- Contribute button: points to our online rapid recording studio.
- Download button: download access to all open licence audios in this language.

![Screenshot from 2023-06-04 21-59-20](https://github.com/hugolpz/LanguagesGallery/assets/1420189/c26bc81e-299c-4126-acdc-95d06c3052f4)
<br clear=all>

## Advanced features
- Search and filter by French expression
- Share a filtered url by appending `?search=YourExpression` to the url

## Datasets reuse
Each language's card has a download button to get a zip of all our open licence files. Their filenames should be used to point to the rightful Wikimedia file page, containing the file's licence.

## Contribute
This Single Page Web Application works with:
- HTML
- CSS
- VueJS

## Credits
Sorted by involvement: URFIST Occitanie : Hugo Lopez, Améle Barrio ; IRIS : Brigitte Dalle, Caroline.

## License
See [index.html](./index.html)'s footer and [LICENSE MPL](./LICENSE).
