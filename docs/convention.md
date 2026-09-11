# Convention TicTag — documentation technique

TicTag est une convention textuelle opérationnelle. Elle utilise un mot-clé visible dans le corps de l’email pour indiquer sa durée de vie recommandée et faciliter son tri ultérieur. Elle ne nécessite aucune modification des protocoles ou des serveurs de messagerie.

## 1. Structure du mot-clé

| Mot-clé | Durée de vie recommandée |
| --- | --- |
| TicTag1Y | 1 an |
| TicTag3Y | 3 ans |
| TicTag5Y | 5 ans |

Chaque mot-clé forme un seul bloc, sans espace :

- **TicTag** identifie la convention. « Tic » évoque le temps qui passe et « Tag » désigne une balise.
- **1, 3 ou 5** indique la durée.
- **Y**, pour « Year », indique que cette durée est exprimée en années.

Reproduire exactement ces mots-clés. Ils ne sont jamais traduits, quelle que soit la langue de l’email. Ces trois durées constituent le cadre de la convention et permettent de garder un repère simple à mémoriser.

## 2. La ligne recommandée

```text
TicTag1Y – Ce mail est biodégradable. Cliquez ici pour en savoir plus : https://tictag.green/info
```

Remplacer uniquement TicTag1Y par TicTag3Y ou TicTag5Y selon le contenu. La phrase d’accompagnement peut être traduite.

Cette ligne remplit trois fonctions complémentaires :

| Élément | Fonction |
| --- | --- |
| Mot-clé TicTag1Y, TicTag3Y ou TicTag5Y | Retrouver les messages et connaître la durée recommandée |
| « Ce mail est biodégradable » | Attirer l’attention et susciter la curiosité |
| Lien vers https://tictag.green/info | Expliquer le principe et permettre au destinataire de l’adopter à son tour |

**Le lien est essentiel à la stratégie de diffusion.** Il transforme chaque email balisé en porte d’entrée vers l’explication de TicTag. Le destinataire découvre l’idée, comprend comment trier ses emails et peut ensuite baliser ses propres envois. C’est ainsi que la convention peut se diffuser de proche en proche.

Le mot-clé reste la clé de recherche : le lien sert à la compréhension et à la diffusion. Conserver les deux dans les modèles recommandés.

« Biodégradable » est une accroche imagée : le message ne se décompose pas et ne s’efface pas spontanément.

## 3. Intégration par l’expéditeur

Insérer la ligne dans le corps ou le pied de l’email, notamment dans un modèle automatisé. Elle doit rester du texte recherchable : une image de la balise ne la remplace pas.

Dans un email HTML, le lien peut être cliquable. Si une version texte brut est également envoyée, y conserver le mot-clé et l’adresse du site.

Une intégration dans un modèle s’applique à ses envois suivants. Il n’est pas nécessaire de baliser chaque envoi individuellement. La balise n’est pas ajoutée rétroactivement aux anciens messages.

Choisir une durée pour le contenu réel du message, y compris ses éventuelles pièces jointes. Une signature ajoutée à des messages très différents demande davantage d’attention qu’un modèle au contenu stable.

## 4. Réception et suppression

À la réception, aucune action n’est nécessaire.

Quand il souhaite nettoyer sa boîte, le destinataire traite chaque balise séparément :

| Recherche | Filtre d’ancienneté |
| --- | --- |
| TicTag1Y | Messages de plus d’un an |
| TicTag3Y | Messages de plus de trois ans |
| TicTag5Y | Messages de plus de cinq ans |

Il vérifie les résultats, sélectionne les messages devenus inutiles et les supprime. Les filtres et le tri par date de la messagerie permettent cette sélection.

La durée est une recommandation, pas une obligation de suppression. Le destinataire garde la main.

## 5. Situations particulières

Une réponse peut citer une ancienne balise ; celle-ci ne décrit pas nécessairement le nouveau contenu. Une conversation peut réunir des messages d’âges et de durées différents. Certaines messageries affichent ou sélectionnent des conversations entières : vérifier le périmètre sélectionné avant une suppression groupée.

Les pièces jointes, les dossiers actifs ou les besoins de conservation peuvent justifier de garder un message au-delà de la durée indiquée. En cas de doute sur un modèle, ne pas lui attribuer de balise avant arbitrage.

## 6. Texte statique et futurs outils

La balise n’exécute aucun code, ne contient aucun pixel de suivi et ne transmet pas le contenu de l’email à TicTag. Un clic sur le lien ouvre le site ; les éventuelles statistiques de fréquentation du site sont distinctes du balisage.

La convention fonctionne déjà sans plugin. Les futurs outils pourront automatiser la recherche et, avec l’accord du destinataire, la suppression. Ils devront définir précisément leurs règles de date et leur traitement des exceptions. Voir la [feuille de route](../ROADMAP.md).

Cette documentation reprend le fonctionnement décrit dans la documentation technique TicTag du porteur du projet.
