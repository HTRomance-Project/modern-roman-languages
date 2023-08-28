HTRomance, Modern language corpus of ground-truth for Handwritten Text Recognition and Layout Segmentation
==========================================================================================================
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

<!-- Custom Zone -->

## Introduction

TBD

## Credits

- Transcriptions: Jade Norindr.
- Supervision and manuscript selection: Alix Chagué.
- Project management: Thibault Clérice, Alix Chagué.

<!-- Rien ne doit être modifié manuellement après la balise Start Auto -->

<!-- Start Auto -->

## Transcription guidelines

The transcription guidelines are described in a paper available on [HAL](https://hal-enc.archives-ouvertes.fr/hal-03828353) and published at the Journal for Open Humanities Data. It provides specific details about the selection process, the transcription methods and choices, as well as details about output (mainly the [Generic CREMMA Model for Medieval Manuscripts (Latin and Old French)](https://zenodo.org/record/7234166#.Y7f69afMJhE) for [Kraken](https://kraken.re))

## Data

ALTO and images can be found in the directory data. Each subfolder of data corresponds to a 
single manuscript, identified by its bookshelf.

<!-- BeginTable -->

| Shelfmark                                                                      | Folder                                                          | Biblissima   | Range   | Type   |   Century | Color   |   Main Zones |   Lines |   Characters | Genre             | Content                                                                                                                                                                                                                                                                                                                                                                            |
|--------------------------------------------------------------------------------|-----------------------------------------------------------------|--------------|---------|--------|-----------|---------|--------------|---------|--------------|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [BnF Français 8204](https://gallica.bnf.fr/ark:/12148/btv1b8551123b)           | [🔗](modern-roman-languages/data/bnf-français-8204)             |              | 1r-77v  | prose  |        17 | ✓       |            7 |      45 |         1871 | armorial          | « Les noms et surnoms, qualitez, armes et seigneuries de tous les cardinaux, prelats et commandeurs de l'Ordre du St -Esprit, qui ont esté faicts par le très crestien roy de France et de Navarre, Louis treiziesme du nom... » (1610-1621).                                                                                                                                      |
| [BnF Ms-3561](https://gallica.bnf.fr/ark:/12148/btv1b52507329r)                | [🔗](modern-roman-languages/data/bnf-ms-3561)                   |              | xr-yv   | prose  |        17 | ✓       |            5 |      91 |         2393 | Traité            | « Testament politique de l'éminantissime Armand, cardinal duc de Richelieu, pair et grand admiral de France. ». « Testament politique de l'éminantissime Armand, cardinal duc de Richelieu, pair et grand admiral de France. » Tome Ier.                                                                                                                                           |
| [BnF NAF 1103](https://gallica.bnf.fr/ark:/12148/btv1b525110430)               | [🔗](modern-roman-languages/data/bnf-naf-1103)                  |              | 1-NP    | prose  |        18 | ✓       |            4 |      88 |         3274 | traité d'histoire | Abrégé de l'histoire de Marseille, depuis sa fondation jusqu'en 1733, par F. M[ALLAVAL], l'an 1733 ».                                                                                                                                                                                                                                                                              |
| [BnF Français 15148](https://gallica.bnf.fr/ark:/12148/btv1b525025055)         | [🔗](modern-roman-languages/data/bnf-français-15148)            |              | 1-484   | mixed  |        18 | ✓       |            4 |      81 |         1803 | prose             | « Pièces critiques et satyriques pour servir à l'histoire du tems. — A Pantin, chez Jean Satire, rue des Mauvaises Pensées, à la Sotise ».                                                                                                                                                                                                                                         |
| [BnF RESERVE 8-YA3-27 (4,52)](https://gallica.bnf.fr/ark:/12148/btv1b8442824z) | [🔗](modern-roman-languages/data/bnf-reserve-8-ya3-27-(-4,-52)) |              | NP-NP   | prose  |        18 | ✓       |            5 |     113 |         3509 | prose             | [Article CXX des Memoires pour l'histoire des Sciences et des Beaux arts. Jugemens sur les principaux ouvrages exposés au Louvre en 1751.]                                                                                                                                                                                                                                         |
| [BnF RESERVE QB-370 (2)-FT 4](https://gallica.bnf.fr/ark:/12148/btv1b6940199f) | [🔗](modern-roman-languages/data/bnf-reserve-qb-370-(-2)-ft-4)  |              | NP-NP   | prose  |        18 | ✓       |            2 |      22 |          538 | ordre royal       | Autographe de Louis XVI. Paris, 15 avril 1791                                                                                                                                                                                                                                                                                                                                      |
| [BnF 2011/091/ACM05-20](https://gallica.bnf.fr/ark:/12148/btv1b10466041s)      | [🔗](modern-roman-languages/data/bnf-2011/-091/-acm05-20)       |              | NP      | prose  |        18 | ✓       |            4 |      16 |          576 | lettre            | Archives du cabinet des médailles, série chronologique. Archives du cabinet des médailles (1794-an IX). Acquisitions provenant de la Monnaie, du Garde-meuble. Lettre de Capperonier au directeur général de l'Instruction publique, demandant la remise au Cabinet de la bordure contenant les miniatures de Louis XIV et sa famille par Antoine Benoist (Paris, 13 nivôse an V). |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Regions

- MainZone (31)
- NumberingZone (21)
- MarginTextZone (6)
- GraphicZone (7)
- StampZone (2)
- TitlePageZone (2)

### Lines

- HeadingLine (25)
- DefaultLine (430)
- InterlinearLine (1)

<!-- EndMetric -->

## Funding

This project was funded by the Bibliothèque nationale de France through the 2022 project calls from
[Datalab](https://www.bnf.fr/fr/bnf-datalab).

## Cite the project

> Clérice, T., Chagué, A., Gille-Levenson, M., Brisville-Fertin, O., Pinche, A., Camps, J., Fischer, F., Boschetti, F., Guadagnini, E., Guilhem Couffignal, G., Canteaut, O., Romary, L., Reboul, M., Perreaux, N., Poibeau, T., Smith, M., Norindr, J., Glaise, A., Navas Farré, M., Bordier, J., Leroy, N., Alba, R., & Rubin, G. *HTRomance* [Data set]. https://htromance-project.github.io/
```
@misc{Clerice_HTRomance,
author = {Clérice, Thibault and Chagué, Alix and Gille-Levenson, Matthias and Brisville-Fertin, Olivier and Pinche, Ariane and Camps, Jean-Baptiste and Fischer, Franz and Boschetti, Federico and Guadagnini, Elisa  and Guilhem Couffignal, Gilles and Canteaut, Olivier and Romary, Laurent and Reboul, Marianne and Perreaux, Nicolas and Poibeau, Thierry and Smith, Marc and Norindr, Jade and Glaise, Anthony and Navas Farré, Marina and Bordier, Julie and Leroy, Noé and Alba, Rachele and Rubin, Giorgia},
title = {{HTRomance}},
url = {https://htromance-project.github.io/}
}
```

## Infrastructure

This project relied on the [CREMMA infrastructure](https://www.dim-map.fr/projets-soutenus/cremma/).



