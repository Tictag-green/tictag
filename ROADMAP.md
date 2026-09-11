# Feuille de route — développer les outils autour de TicTag

La convention TicTag est définie et opérationnelle : trois balises, une durée recommandée et un lien explicatif. Son utilisation manuelle est déjà possible avec les fonctions des messageries. Les travaux à venir concernent les outils qui pourront s’appuyer sur elle.

## Priorité 1 — Un assistant de nettoyage

- Développer un premier plugin ou une extension capable de repérer les emails balisés et de calculer leur ancienneté.
- Présenter les messages ayant dépassé la durée indiquée, avec leur nombre et leur volume lorsque la messagerie le permet.
- Permettre une suppression groupée après validation du destinataire.
- Prévoir des exclusions pour les messages à conserver et traiter les conversations sans supprimer des messages récents par association.

Ce premier outil facilitera le passage du tri manuel à un nettoyage assisté.

## Priorité 2 — La suppression automatique, sur activation volontaire

- Permettre au destinataire d’activer un nettoyage périodique des messages arrivés à échéance.
- Proposer des règles configurables : périmètre des dossiers, exclusions, fréquence et délai de grâce.
- Prévoir un passage par la corbeille et une possibilité de récupération selon les capacités de la messagerie.
- Rendre les actions consultables et permettre de suspendre l’automatisation à tout moment.
- Prendre en compte les balises citées dans une réponse, les durées multiples, les pièces jointes et les règles de conservation du compte.

L’expéditeur recommande une durée ; le destinataire autorise l’outil à agir. La balise seule continue de ne déclencher aucune suppression.

## Priorité 3 — Les intégrations

- Développer des connecteurs ou modules pour les principales messageries, selon leurs interfaces et permissions disponibles.
- Proposer des modules pour les plateformes e-commerce et d’emailing afin de faciliter l’ajout des balises aux modèles.
- Faciliter l’administration des choix de balisage dans les organisations.
- Encourager la prise en charge de TicTag par les éditeurs de logiciels.

## Diffuser la convention en parallèle

La vidéo, les illustrations et les améliorations du site servent à faire connaître une idée déjà aboutie. Ce sont des supports de présentation, indépendants du fonctionnement de la convention.

La diffusion passe aussi par les liens présents dans les emails, les relais professionnels, associatifs et publics, et les intégrations dans les outils existants.

Cette feuille de route présente des axes de développement, sans date de livraison annoncée. Ce dépôt fournit actuellement la documentation et les exemples de balisage ; les plugins et la suppression automatique décrits ici restent à développer.
