# Impact environnemental — les volumes, le mécanisme et les hypothèses

TicTag facilite la suppression des emails devenus inutiles. L’objectif est de réduire leur accumulation et les besoins de stockage associés. Les volumes mondiaux donnent la mesure du sujet ; le bénéfice obtenu dépend ensuite des usages et des infrastructures.

## Des centaines de milliards d’emails chaque jour

L’étude d’impact TicTag de juillet 2026 retient **361,6 milliards d’emails échangés par jour en 2024**, d’après le rapport *Email Statistics Report, 2024–2028* de The Radicati Group.

| Indicateur | Ordre de grandeur | Nature |
| --- | --- | --- |
| Trafic quotidien en 2024 | 361,6 milliards d’emails | Estimation sectorielle reprise dans l’étude TicTag |
| Trafic annualisé sur 365 jours | 131 984 milliards, soit environ 132 000 milliards d’emails | Calcul : 361,6 × 365 |
| Trafic cumulé sur cinq années au même rythme | Environ 660 000 milliards d’emails | Illustration à trafic constant, sans prévision de croissance |

La base de 365 jours sert à annualiser le rythme quotidien ; il ne s’agit pas d’un décompte exact de l’année civile 2024, qui comptait 366 jours. Un volume de trafic n’est pas un volume de messages effectivement conservés.

Référence bibliographique reprise de l’étude fournie : The Radicati Group, *Email Statistics Report, 2024–2028*, communiqué référencé sur [EIN Presswire](https://www.einpresswire.com/article/751597875) ; série également référencée chez [Statista](https://www.statista.com/statistics/456500/daily-number-of-e-mails-worldwide/). Ces pages n’ont pas pu être revérifiées lors de cette mise à jour ; le rapport payant n’a pas été consulté intégralement. Les chiffres sont conservés comme base datée de l’étude, sans les présenter comme une mesure du trafic actuel.

## Pourquoi le stockage compte

Un email conservé occupe de l’espace sur une infrastructure physique. Les copies, la redondance et les sauvegardes peuvent augmenter le volume associé. Le stockage mobilise des équipements et de l’électricité.

Supprimer un message ne coupe pas instantanément un serveur. Le bénéfice recherché est de réduire le stock inutile et, à l’échelle collective et dans le temps, les besoins de capacité. Les délais des corbeilles, des sauvegardes et de réallocation du stockage influencent ce résultat.

La suppression n’annule pas l’énergie déjà utilisée pour envoyer ou consulter le message.

## Ce que montre le scénario de l’étude TicTag

L’étude fournie propose un scénario de calcul. Les paramètres suivants sont des **hypothèses de travail**, pas des moyennes mondiales mesurées :

| Paramètre | Hypothèse |
| --- | --- |
| Part du trafic devenant inutile et restant conservée | 10 % |
| Taille moyenne d’un message | 80 ko, en unités décimales |
| Facteur de copies | ×3 |
| Intensité énergétique du stockage physique | 35 kWh par To et par an |

La part de 10 % n’est pas issue d’une mesure spécifique aux emails. Le poids moyen dépend fortement des pièces jointes. Le facteur ×3 n’est pas une règle commune à toutes les messageries. Les 35 kWh/To/an constituent un choix de modélisation de l’étude, pas un facteur officiel du stockage email ; le calcul suppose qu’ils s’appliquent aux To physiques après copies, pour éviter de compter la réplication deux fois.

En conservant la base non arrondie, le calcul donne :

| Étape | Résultat |
| --- | --- |
| 361,6 milliards × 365 × 10 % | 13 198,4 milliards de messages |
| Messages × 80 ko | 1 055 872 To, soit environ 1,06 Eo |
| Volume ×3 | 3 167 616 To, soit environ 3,17 Eo |
| Volume physique × 35 kWh/To/an | Environ 111 GWh pour conserver ce lot pendant une année entière |

**Ce résultat décrit le stockage pendant un an d’un lot équivalent à une année d’accumulation hypothétique.** Il ne mesure ni tout le stock historique mondial, ni l’énergie consommée pendant la constitution progressive du lot, ni l’économie effectivement obtenue grâce à TicTag.

### Sensibilité du résultat

Avec les mêmes hypothèses de nombre de messages, de taille et de copies :

| Intensité énergétique supposée | Énergie annuelle du lot |
| --- | --- |
| 30 kWh/To/an | Environ 95 GWh |
| 35 kWh/To/an | Environ 111 GWh |
| 50 kWh/To/an | Environ 158 GWh |
| 70 kWh/To/an | Environ 222 GWh |

Ces variantes illustrent la sensibilité à un paramètre, sans constituer un intervalle de confiance.

## Et le carbone ?

L’Agence internationale de l’énergie indique une intensité mondiale de production électrique de **445 g CO₂/kWh en 2024** dans [Electricity 2025 — Emissions](https://www.iea.org/reports/electricity-2025/emissions).

Appliquée au scénario de 110,87 GWh, cette valeur donne environ **49 300 tonnes de CO₂ pour une année de stockage du lot hypothétique**.

Ce facteur représente la moyenne mondiale de production électrique, pas le mix propre aux messageries ou aux centres de données. Il ne s’agit pas d’un facteur complet d’analyse de cycle de vie des équipements. Le résultat n’est donc pas une annonce d’émissions évitées par TicTag.

L’étude initiale alternait entre 105 et 111 GWh. Ce document conserve le calcul cohérent de 110,87 GWh, arrondi à 111, et recalcule le carbone sur cette même base.

## Mesurer le bénéfice de TicTag

Les indicateurs utiles sont les volumes d’emails balisés, les suppressions supplémentaires attribuables à leur balisage et les octets effectivement retirés du stockage. Une évaluation énergétique exige ensuite des données sur les infrastructures concernées.

Un clic vers le site mesure la découverte du projet ; il ne mesure pas une suppression. La balise est un texte statique sans pixel de suivi. Les éventuelles statistiques du site sont distinctes.

La convention peut être utilisée dès aujourd’hui. La quantification de son bénéfice environnemental est une question de mesure, distincte de son fonctionnement.
