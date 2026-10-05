<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · fr · no clinical/professional/rights approval -->

# Fraction d’éjection (Teichholz) et fraction de raccourcissement

[conditions, sources et autorisations](https://elucenia.org/fr/outils/fracao-de-ejecao-teichholz)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Diamètre diastolique du ventricule gauche

`ddve`

cm · intervalle: 2–9

### Diamètre systolique du ventricule gauche

`dsve`

cm · intervalle: 1–8

## Édition de la méthode

Teichholz 1976 : 7 D³/(2,4+D) ; FE et volumes linéaires ; contexte ASE/EACVI 2015 et limites géométriques

## Formule documentée

Volume (Teichholz) = 7 ÷ (2,4 + D) × D³ (D en cm, volume en mL)

Fraction d’éjection = (VTD − VTS) ÷ VTD × 100

Fraction de raccourcissement = (DTDVG − DTSVG) ÷ DTDVG × 100

## Limites et population

L’estimation de Teichholz dépend de la relation géométrique entre le diamètre et le volume ventriculaires. Dans l’étude originale, la concordance était bonne sans asynergie et mauvaise en présence d’asynergie. Une maladie coronarienne avec une possible anomalie régionale nécessite de la prudence ; la fraction calculée à partir d’un diamètre ne remplace pas les méthodes adaptées à la géométrie ventriculaire.

## Références

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
