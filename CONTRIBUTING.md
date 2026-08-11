# Contributing

Ce dépôt est le domicile canonique de la doctrine MYSTANCE. Le corpus est français et le français fait foi ; les issues peuvent être ouvertes en français ou en anglais.

## Comment proposer

Les contributions se proposent par issue. Sont bienvenus, en particulier : les contre-exemples, les pièces d'antériorité, les critiques, les signalements de dérive (SPEC § 8) et les incohérences entre une fiche et la [SPEC](SPEC.md) ; en cas de divergence, la SPEC prévaut. Un contre-exemple nommé est un service rendu.

Les textes de la doctrine (SPEC, WHITEPAPER, fiches) ne se modifient que par décision de l'auteur, tracée au [CHANGELOG](CHANGELOG.md). Les profils tiers (déclinaisons par domaine) se proposent par issue ou pull request ; un profil déclare son domaine et ses valeurs sans redéfinir le socle ([profiles](profiles/index.md)).

## Régimes d'écriture

Chaque document du corpus est écrit dans un **régime** déclaré. Le régime dit ce que le texte fait et ce
qu'il ne fait pas ; il n'est pas une question de style mais de rôle. Un document qui sort de son régime est
une dérive au même titre qu'une fiche qui contredit la [SPEC](SPEC.md).

⚠ **« Régime » ne se confond pas avec « posture ».** La posture est un mécanisme de la doctrine : comment
l'assistant se tient face à l'utilisateur. Le régime est une règle d'écriture du corpus sur lui-même.
Deux objets, deux mots.

| Document | Régime | Ce qu'il fait, et ce qu'il ne fait pas |
|---|---|---|
| [`SPEC.md`](SPEC.md) | **normatif** | Les règles, et rien d'autre. Vocabulaire « DOIT / PEUT ». **Aucune justification, aucun exemple, aucune image** : le pourquoi vit au whitepaper |
| [`WHITEPAPER.md`](WHITEPAPER.md) | **argumentatif** | La thèse et le pourquoi de chaque règle. Dense, sans emphase. **Il expose, il ne convainc pas** |
| [`fiches/`](fiches/index.md) · **de mécanisme** | **pédagogique** | L'arc complet, en six sections : voir le gabarit ci-dessous. **Il illustre et borne, il ne norme jamais** |
| [`fiches/`](fiches/index.md) — **transverses** | **propre à l'objet** | Synthèse, glossaire, bornes, pratique candidate. **Elles ne suivent pas l'arc, et c'est délibéré** : il explique un mécanisme, elles n'en expliquent aucun |
| [`LINEAGE.md`](LINEAGE.md), [`research/`](research/) | **généalogique** | Les sources vérifiées sur textes originaux, ce qui est repris **et ce qui ne l'est pas**. Le lecteur doit pouvoir prendre le corpus en défaut |
| [`README.fr.md`](README.fr.md) | **liminaire** | Un constat, un invariant, de quoi décider d'entrer. **Il ne vend pas** |
| [`fiches/GLOSSAIRE.md`](fiches/GLOSSAIRE.md) | **traductif** | Une ligne par terme. **Il traduit, il ne norme pas** |
| [`templates/`](templates/TEMPLATE-DE-LA-RELATION.md) | **impératif** | La structure, verrouillée et vide. **Le contenu appartient à l'utilisateur** |

### Le gabarit d'une fiche

Une fiche suit un **arc pédagogique** en six sections, dans cet ordre :

1. **`## Le problème, en trois phrases`** : ce qui ne marche pas sans le mécanisme.
2. **`## L'idée, en une image`** : une analogie, **et un diagramme**.
3. **`## N questions que la pratique a posées, et les réponses`** : les objections réelles, pas les faciles.
4. **`## Les règles (SPEC § N)`** : le renvoi normatif ; la fiche cite, elle ne redéfinit pas.
5. **`## Les pièges`** : les manières connues de mal l'appliquer.
6. **`## Ce que ça change`** : le bénéfice observable, ou `## En pratique`.

*Ce gabarit est celui de [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE), où il est appliqué
aux sept fiches du corpus. Les deux couches partagent la même discipline d'écriture ; MYSTANCE l'aligne ici.*

## Statuts, crédits, licence

Les documents normatifs et d'étude (SPEC, WHITEPAPER, LINEAGE, journaux d'antériorité) portent leur statut (`proposé / validé`) et leur date ; les fiches et templates portent leur statut. Les statuts et les révisions datées restent des décisions d'auteur. « Validé » est une décision éditoriale : elle atteste la cohérence et l'exactitude arrêtées d'un texte, jamais l'efficacité d'un mécanisme, qui relève des rangs de preuve ([SPEC § 10](SPEC.md)) et ne s'attestera qu'au terrain.

Toute contribution acceptée est créditée. La licence du dépôt s'applique ([LICENSE](LICENSE.md)).

Merci de votre lecture, et de vos objections : ce corpus n'apprendra pas sans elles.
