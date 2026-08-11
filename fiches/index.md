# Fiches · MYSTANCE

**Statut : proposé.** La fiche explique, illustre et borne ; elle ne redéfinit pas : le normatif vit dans la [SPEC](../SPEC.md). Une fiche qui contredit la SPEC est elle-même une dérive.

**Deux classes de fiche, et elles ne suivent pas la même forme.**

- **Fiche de mécanisme** : elle explique une famille de règles de la SPEC, et le déclare par son code *(règles N, L, V, C, P)*. Elle suit **l'arc en six sections** : `Le problème, en trois phrases` → `L'idée, en une image` (avec un diagramme) → `N questions que la pratique a posées, et les réponses` → `Les règles (SPEC § N)` → `Les pièges` → `Ce que ça change`. Cinq fiches, cinq familles de règles.
- **Fiche transverse** : synthèse, glossaire, bornes, pratique candidate. **Elle ne suit pas l'arc, et c'est délibéré** : l'arc explique un mécanisme, et ces fiches n'en expliquent aucun. Leur forme suit leur objet.

*Le gabarit des fiches de mécanisme est celui de [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE) ; les deux couches partagent la même discipline d'écriture. Les régimes du corpus sont déclarés au [CONTRIBUTING](../CONTRIBUTING.md).*

**Principe de registre.** Une fiche peut dire à l'indicatif ce que la règle *exige* : c'est du normatif. Elle ne dit pas à l'indicatif ce que le mécanisme *obtient* tant que son rang de preuve est inférieur à « mesuré » ([SPEC § 10](../SPEC.md#10-rangs-de-preuve)) : l'effet attendu se dit au conditionnel, ou comme un pari daté et exposé à la réfutation ([SPEC § 9](../SPEC.md#9-falsification)). « La règle interdit ceci » : oui. « Le mécanisme rend l'utilisateur autonome » : pas avant le terrain.

**Convention de lecture : les codes de règles.** Les codes (N3, C2, DM1…) sont les ancres de la [SPEC](../SPEC.md) : ils servent au vérificateur, pas au lecteur. Dans les fiches du parcours utilisateur, chaque phrase se suffit sans son code ; le code, quand il est utile, se tient en fin de phrase entre parenthèses, *(SPEC : N3)*, ou dans le bloc « Ce que ça borne » en fin de fiche. Un code ne porte jamais la phrase : si la suppression de la parenthèse rend la phrase incompréhensible, la phrase est à réécrire.

## Parcours utilisateur (l'ordre de la relation)

1. [`NOMMAGE-DU-COMPAGNON`](NOMMAGE-DU-COMPAGNON.md) : le premier geste, proposé jamais imposé : vous nommez votre compagnon (règles C).
2. [`NIVEAU-D-ASSISTANCE`](NIVEAU-D-ASSISTANCE.md) : le paramètre cardinal (le réglage principal) : combien l'IA propose, sur quatre niveaux nommés (règles N).
3. [`POSTURE-DE-LA-RELATION`](POSTURE-DE-LA-RELATION.md) : le second paramètre : comment elle se tient (règles P).
4. [`TROIS-PROPOSITIONS-CHAMP-LIBRE`](TROIS-PROPOSITIONS-CHAMP-LIBRE.md) : la forme canonique (la forme de référence) de tout choix échafaudé, c'est-à-dire appuyé par des propositions de l'assistant (règles L).
5. [`TEMPLATE-VERROUILLE`](TEMPLATE-VERROUILLE.md) : le mécanisme central : structure à la doctrine, contenu à vous (règles V).
6. [`ASSISTANT-DE-REFERENCE`](ASSISTANT-DE-REFERENCE.md) : ce qu'un assistant conforme fait, et ne fait jamais, dont l'accueil de référence, de bout en bout.

En appui du parcours : [`GLOSSAIRE`](GLOSSAIRE.md), les termes en langage courant, et les trois questions à poser à tout assistant qu'on vous vend · [`VOS-DONNEES-ET-VOS-RESPONSABILITES`](VOS-DONNEES-ET-VOS-RESPONSABILITES.md), ce que la doctrine ne couvre pas, dit honnêtement ; cette fiche touche à des questions juridiques et n'a pas encore été relue par un professionnel du droit.

En marge du parcours : [`SOLLICITATION`](SOLLICITATION.md), pratique de la lignée, **candidate** à la norme (la règle des trois temps) ; elle ne norme rien tant que le socle ne l'a pas admise.

## Templates versés

[`TEMPLATE-DE-LA-RELATION`](../templates/TEMPLATE-DE-LA-RELATION.md), v0.1 : la structure de la relation (profil, nom, niveau, posture, limites, registre). Verrouillé au sens de V1 ; libre au remplissage (V2).

## Parcours normatif

[`SPEC.md`](../SPEC.md) d'abord, puis le [whitepaper](../WHITEPAPER.md) pour le pourquoi.
