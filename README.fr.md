# MYSTANCE

**La couche humaine des systèmes d'IA.**

MYSTANCE est un corpus de règles écrites, pas un logiciel : rien à installer ; des règles qu'un outil peut appliquer, et que tout utilisateur peut lire, opposer et vérifier.

[English version](README.md) · si les deux divergent, le corpus français fait foi.

`Statut : Public Draft` · `Spec : v0.3` · `Licence : CC BY-NC-SA 4.0 + clause contenant/contenu`

> MYSTANCE, prononcé **Maï-stance**. Garder la maîtrise dans un monde augmenté par l'IA.

## Le constat : des réglages partout, une norme nulle part

L'une des questions les plus posées sur les assistants IA, « comment garder le contrôle ? », appelle spontanément des réponses de domination. Elle nomme un risque réel ; elle laisse aussi un angle mort : en faisant de l'IA le seul sujet du problème, elle dispense l'humain d'examiner sa propre place dans la relation. Or le marché offre déjà de quoi régler cette place, à chaque hauteur d'utilisateur : l'un ajuste le ton dans sa conversation ; l'autre pose des instructions générales dans son produit : champs de préférences, presets de personnalité, styles ; le plus avancé installe des garde-fous de partout : anti-flatterie, contre-arguments obligatoires, niveaux d'autonomie de ses agents, listes d'actions interdites. Le réglage n'est pas absent : il prolifère. Mais il prolifère **sans norme** : fragmenté (le ton ici, l'initiative là, jamais les deux tenus ensemble), sans contrat publié pour le ton (aucun preset ne dit ce qu'il fait et ne fait pas), inégalement honoré (le réglage en champ libre surtout), révocable sans préavis par l'éditeur (les styles de Bing ont disparu ainsi), et sans invariant : aucun de ces dispositifs ne garantit que le réglage module *combien l'IA propose*, jamais *qui décide*. L'état de l'existant est documenté au [journal d'antériorité](research/prior-art-2026-08-02-produits.md).

## Le principe : régler plutôt que dominer

MYSTANCE n'invente pas le réglage de la relation humain-IA : elle propose de le **normer**. La relation se règle comme on règle un appareil : des paramètres explicites, visibles, ajustables par l'utilisateur, et garantis par des règles écrites, réfutables. Le paramètre cardinal est le [**niveau d'assistance**](fiches/NIVEAU-D-ASSISTANCE.md) : combien l'IA propose, réglé sur **quatre niveaux nommés** (**MÉDIATION · APPUI · COLLABORATION · GÉNÉRATION**). Chaque niveau est un contrat de comportements observables : une liste de ce que l'assistant fait, et ne fait pas, que chacun peut vérifier à l'usage. L'échelle est close aux deux bouts : jamais zéro médiation (convention de domaine : dans un OS d'IA, la relation n'est jamais nulle), jamais de production 100 % IA.

L'invariant proposé (la règle qui ne bouge jamais, quel que soit le réglage) : **le niveau module combien l'IA propose, jamais qui décide.**

Les termes techniques sont traduits au [glossaire](fiches/GLOSSAIRE.md).

## Un problème ancien, un terrain neuf

La relation humain-machine s'observe depuis cinquante ans : les niveaux d'automatisation (Sheridan & Verplank, 1978), leurs coûts humains (charge mentale, conscience de situation, complaisance, dégradation de compétence) rassemblés comme critères d'évaluation par Parasuraman, Sheridan & Wickens (2000). Ces cartes du ciel ont été dressées quand l'IA grand public relevait de la science-fiction ; elles restent bonnes, et ce corpus en hérite explicitement ([LINEAGE](LINEAGE.md)). Ce qui est neuf (trois ou quatre ans à peine), c'est le télescope : une IA avec laquelle chacun converse et travaille au quotidien, qui rend cette relation observable à l'échelle, par tous. Autrement dit : les repères existent déjà ; l'instrument pour les vérifier vient seulement d'arriver.

Ce corpus ne revendique donc aucune vérité installée. Sa démarche : formuler des hypothèses réalistes sur ce terrain neuf, les soumettre au banc d'essai (les éprouver en conditions réelles), et ne retenir comme doctrine que ce qui aura tenu. Chaque document porte son statut, chaque mécanisme son rang de preuve, c'est-à-dire le degré de solidité de ce qui l'appuie ([SPEC §§ 9–10](SPEC.md)). « Doctrine » désigne ici un rang du pipeline, pas l'une des couches présentées plus bas, pas un statut acquis ; ce statut se gagne au terrain. Et le télescope étant là, l'observation n'est plus une promesse : c'est une dette.

## Les cinq mécanismes

- **Le niveau d'assistance** : quatre niveaux nommés à contrat comportemental, de la médiation seule à la génération encadrée. Selon le niveau, l'échafaudage (les aides et propositions affichées autour de la saisie libre) s'étoffe ou s'allège. Réglable à tout moment, sans justification ; tout ajustement proposé par l'assistant est explicitement consenti. [`NIVEAU-D-ASSISTANCE`](fiches/NIVEAU-D-ASSISTANCE.md)
- **La posture** : le second paramètre, distinct du niveau : comment l'assistant se tient. Quatre registres canoniques en liste close (**complice, sobre, critique, implacable**), choisis d'une phrase, changeables à tout moment. Ce que l'utilisateur avancé fabrique en prompt artisanal, la doctrine le donne à tous en template. [`POSTURE-DE-LA-RELATION`](fiches/POSTURE-DE-LA-RELATION.md)
- **3 propositions + champ libre** : la forme canonique de tout choix ouvert échafaudé : au plus trois propositions contrastées, et toujours, en dernier, le choix libre. Né d'une table de jeu réelle. [`TROIS-PROPOSITIONS-CHAMP-LIBRE`](fiches/TROIS-PROPOSITIONS-CHAMP-LIBRE.md)
- **Les templates verrouillés** : la doctrine définit la structure, verrouillée (contre les changements silencieux et les débordements de l'assistant, jamais contre vous) ; l'utilisateur remplit librement, et le contenu lui appartient : un template rempli n'est pas un dérivé. Premier template versé : [la relation, v0.1](templates/TEMPLATE-DE-LA-RELATION.md). [`TEMPLATE-VERROUILLE`](fiches/TEMPLATE-VERROUILLE.md)
- **Le nommage du compagnon** : c'est l'utilisateur qui nomme son assistant, premier champ du template verrouillé, premier geste de la relation (proposé, jamais imposé). La doctrine ne fournit aucun nom. [`NOMMAGE-DU-COMPAGNON`](fiches/NOMMAGE-DU-COMPAGNON.md)

Et la synthèse comportementale : [`ASSISTANT-DE-REFERENCE`](fiches/ASSISTANT-DE-REFERENCE.md), ce qu'un assistant conforme fait et ne fait jamais. Son critère de réussite : l'utilisateur sait faire aujourd'hui une chose qu'il ne savait pas faire hier, sans l'assistant dans la boucle. L'assistant réussit quand on a moins besoin de lui.

## Quatre couches, quatre rôles

| Couche                                                          | Gouverne                                                                                |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Un OS d'IA                                                      | le système : lois, fichiers, boucles, frontières                                        |
| [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE) | le statut du savoir : ce qui est validé, ce qui fait canon                              |
| [WORKING REFERENCE](https://github.com/JP-Noto/WORKING-REFERENCE) | le service de la référence : ce qui monte à l'appel, servi et scellé |
| **MYSTANCE**                                                    | la place de l'humain : la relation paramétrée, la montée en compétence, la souveraineté |

Aucune redondance : LIVING REFERENCE mesure le *statut du savoir* ; WORKING REFERENCE trace le *service de la référence* ; MYSTANCE mesure la *praticabilité humaine du workflow* (le travail reste-t-il faisable, compréhensible et tenable pour l'humain ?). La doctrine est indépendante de tout OS hôte, présent ou futur. La famille est opérée par le laboratoire ONDE AI R&D — son portail : <https://github.com/JP-Noto/ONDE>.

## À qui elle s'adresse, et où elle en est

MYSTANCE s'adresse à quiconque travaille avec un assistant IA : la relation qu'elle norme existe dès qu'un humain et un assistant travaillent ensemble, quel que soit le métier, l'expertise ou la taille de la structure. Le socle est le même pour tous ; les déclinaisons par domaine vivent dans les [profils d'application](profiles/index.md).

Lisez la ligne d'état avant la promesse : aucun déploiement n'a eu lieu ([SPEC § 10](SPEC.md)) ; la validation en usage réel reste à faire ; un premier terrain est pressenti, sans être nommé à ce stade, où la doctrine affrontera ses propres conditions d'échec ([SPEC § 9](SPEC.md)).

### Et concrètement, aujourd'hui ?

- **Vous dirigez une entreprise** : ce corpus ne s'installe pas ; il se lit, et il arme. Les [fiches](fiches/index.md) et le [glossaire](fiches/GLOSSAIRE.md) donnent trois questions à poser à tout assistant qu'on vous vend : qui décide ? qui tient les réglages ? le choix libre existe-t-il toujours ? La fiche [« Vos données et vos responsabilités »](fiches/VOS-DONNEES-ET-VOS-RESPONSABILITES.md) dit honnêtement ce que la doctrine ne couvre pas.
- **Vous construisez un outil** : mettre en œuvre les règles est expressément libre ([LICENSE](LICENSE.md)) ; un outil conforme applique un profil d'application déclaré, qui fixe les défauts de niveau et de posture ([SPEC N6, P2](SPEC.md)).
- **Vous êtes du métier ou simplement exigeant** : le corpus publie ses conditions de réfutation, c'est-à-dire ce qui, observé, prouverait que la doctrine se trompe ([SPEC § 9](SPEC.md)), et sa généalogie, d'où viennent ses idées ([LINEAGE](LINEAGE.md)). Les contre-exemples sont un service rendu.

## Deux parcours de lecture

**Parcours utilisateur** (l'ordre de la relation) : [`NOMMAGE-DU-COMPAGNON`](fiches/NOMMAGE-DU-COMPAGNON.md) → [`NIVEAU-D-ASSISTANCE`](fiches/NIVEAU-D-ASSISTANCE.md) → [`POSTURE-DE-LA-RELATION`](fiches/POSTURE-DE-LA-RELATION.md) → [`TROIS-PROPOSITIONS-CHAMP-LIBRE`](fiches/TROIS-PROPOSITIONS-CHAMP-LIBRE.md) → [`TEMPLATE-VERROUILLE`](fiches/TEMPLATE-VERROUILLE.md) → [`ASSISTANT-DE-REFERENCE`](fiches/ASSISTANT-DE-REFERENCE.md).
**Parcours normatif** : [`SPEC.md`](SPEC.md) d'abord, puis le [whitepaper](WHITEPAPER.md) pour le pourquoi.

| Fichier | Rôle | Langue |
|---|---|---|
| [`SPEC.md`](SPEC.md) | Le normatif : termes et règles N, L, V, C, P | FR |
| [`WHITEPAPER.md`](WHITEPAPER.md) | Le pourquoi de chaque règle | FR |
| [`LINEAGE.md`](LINEAGE.md) | Généalogie, crédits, antériorité (vérifiée sur textes originaux) | FR |
| [`fiches/`](fiches/index.md) | Les fiches : mécanismes, repères transverses, et le [glossaire](fiches/GLOSSAIRE.md) | FR |
| [`templates/`](templates/TEMPLATE-DE-LA-RELATION.md) | Les templates verrouillés (la relation, v0.1) | FR |
| [`profiles/`](profiles/) | Déclinaisons par domaine (le concept ; aucun profil déclaré) | FR |
| [`research/`](research/) | Journal d'antériorité (deux entrées datées ; pièces savantes vérifiées sur textes originaux) | FR |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Comment proposer, et sous quelle licence | FR |
| [`CHANGELOG.md`](CHANGELOG.md) | Versions | EN |

## Née de la pratique

La même réponse au même problème (cadrer la place, la voix et le niveau d'assistance d'un agent auprès d'un humain) a été reconstruite sur quatre générations. L'auteur en recense onze occurrences (inventaire non versé à ce jour), sur des projets distincts : jeux, création d'univers, studio de production, produit B2B, OS ([LINEAGE](LINEAGE.md)). La doctrine distille cette lignée ; elle ne l'invente pas. Et elle dit ce qui est prouvé et ce qui ne l'est pas : rangs de preuve et conditions de falsification dans la [SPEC §§ 9–10](SPEC.md).

## Ce qui est prouvé, ce qui ne l'est pas

Chaque revendication de ce corpus porte son rang de preuve ([SPEC § 10](SPEC.md)).

| Mécanisme | Rang de preuve |
|---|---|
| 3 propositions + champ libre · posture (le paramètre) | **précédent d'usage** : au moins une occurrence réelle, datée, non mesurée |
| Niveau d'assistance · liste canonique des postures · templates verrouillés · gardes de non-capture · trace des réglages · champ limites · nommage par l'utilisateur | **spécifié** : la règle est écrite, aucun déploiement |

Aucun mécanisme n'atteint « mesuré » ni « répliqué » : aucun terrain instrumenté, à ce jour.

La métrique candidate, et la promesse centrale : **l'autonomie de l'utilisateur croît** ; à l'horizon, il réalise, sans l'assistant dans la boucle, une tâche qu'il ne réalisait pas au départ ([SPEC § 9](SPEC.md), condition 1). Si elle ne croît pas, la doctrine est en défaut. La revendication la plus distinctive (le réglage tenu par l'utilisateur, non par le concepteur) est aussi la plus exposée à la réfutation (condition 4) : si un réglage tenu par l'utilisateur ne fait pas mieux qu'un réglage fixé à la conception, l'apport propre de MYSTANCE tombe.

Une borne, enfin : la doctrine **organise la relation** (qui décide, combien l'IA propose, comment elle se tient). Elle ne **garantit pas la génération** : qu'un modèle respecte le niveau et le contexte qu'on lui donne est une propriété des modèles d'aujourd'hui, pas de la doctrine.

## Autorité

En cas de divergence, `SPEC.md` prévaut : une fiche qui la contredit est elle-même une dérive. Ce corpus a été écrit hors du dépôt ; son historique public commence au dépôt initial. L'antériorité repose sur les pièces datées citées dans [`LINEAGE.md`](LINEAGE.md).

## Travaux voisins

La filiation de la doctrine (sources, ce qui est repris, ce qui est **requalifié**, ce qui est apporté) est
tenue **mécanisme par mécanisme** dans [`LINEAGE.md`](LINEAGE.md), sur pièces lues **dans leur texte original**.
Deux journaux d'antériorité datés en portent l'état de l'espace : [le champ savant](research/prior-art-2026-07-24.md)
et [les produits du marché](research/prior-art-2026-08-02-produits.md).

La relation humain-machine s'étudie depuis cinquante ans, et le corpus le dit plutôt que de l'omettre : Sheridan
& Verplank (1978), Parasuraman, Sheridan & Wickens (2000), Wood, Bruner & Ross (1976), Horvitz (1999) : ainsi
que les voisins grand public, dont les *conversation styles* de Bing. **Dans presque toutes ces pièces, le
titulaire du réglage est le concepteur, l'opérateur ou le développeur.** C'est là, et là seulement, que MYSTANCE
propose autre chose : **le réglage tenu par l'utilisateur**, et c'est aussi sa revendication la plus exposée à
la réfutation ([SPEC § 9](SPEC.md#9-falsification), condition 4).

## Licence & attribution

Textes de la doctrine : [CC BY-NC-SA 4.0](LICENSE.md), attribution *JP Noto, MYSTANCE*. Clause contenant/contenu (le contenant est protégé, le contenu est à vous) : les templates verrouillés sont l'actif protégé de la doctrine, y compris vides ; les remplir est expressément libre, et **un template rempli n'est pas un dérivé** : ce que vous y mettez, jusqu'au nom de votre assistant, vous appartient.

---

*JP Noto · MYSTANCE · [CC BY-NC-SA 4.0](LICENSE.md). Domicile canonique : <https://github.com/JP-Noto/MYSTANCE>.*
