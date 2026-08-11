# Fiche · POSTURE DE LA RELATION

**Statut : proposé · norme : [SPEC règles P](../SPEC.md#7-posture--règles-p).** *Les codes entre parenthèses (P1, DM6…) renvoient aux règles de la SPEC ; chaque phrase se lit sans eux.*

## Le problème, en trois phrases

Le ton d'un assistant est soit invisible, soit artisanal : l'utilisateur avancé le fabrique en prompt (« challenge-moi », « sois critique ») et tous les autres subissent celui que l'éditeur a choisi. Quand ce registre n'a pas de nom, personne ne peut dire si l'assistant s'est adouci ou si c'est le lecteur qui l'imagine. Et faute de séparation déclarée, régler le ton finit par régler autre chose : on demande « plus de franchise » et on obtient plus de propositions.

## L'idée, en une image

Deux **molettes distinctes** sur le même appareil. L'une dose la quantité d'aide, l'autre règle le registre de la voix, et tourner l'une ne bouge pas l'autre. C'est le test d'admission d'une posture : **un registre qui modulerait l'[échafaudage](GLOSSAIRE.md) serait un niveau déguisé.**

```mermaid
flowchart TB
    subgraph N["NIVEAU — combien l'IA propose"]
        direction LR
        n1["MÉDIATION"] --- n2["APPUI"] --- n3["COLLABORATION"] --- n4["GÉNÉRATION"]
    end
    subgraph P["POSTURE — comment elle se tient"]
        direction LR
        p1["COMPLICE"] --- p2["SOBRE"] --- p3["CRITIQUE"] --- p4["IMPLACABLE"]
    end
    N -. "deux réglages orthogonaux :<br/>régler l'un ne change jamais l'autre" .-> P
```

La posture s'installe **avant toute demande** (en réglage général ou en prompt de projet) et se change à tout moment, sans justification. Elle opère à tous les niveaux : à MÉDIATION, un assistant réglé CRITIQUE conteste ce qu'on lui soumet même quand il n'échafaude rien.

## Quatre questions que la pratique a posées, et les réponses

**Pourquoi « guidant » n'est-il pas une posture ?** Parce qu'il échoue au test d'orthogonalité : guider, c'est ajouter de l'aide, donc un **niveau**, pas un registre. Le terme venait de la source interne ; il a été requalifié plutôt que conservé par commodité.

**Pourquoi une liste close, alors que la doctrine défend partout le choix libre ?** Parce qu'ici le libre serait faux : l'utilisateur croirait créer une posture que le système rattacherait en silence à l'une des quatre. **3 propositions + champ libre** ne s'applique donc pas (P5). **Sa liberté est ailleurs, et elle est entière : changer de posture à tout moment** (P4). La clôture de la liste est elle-même exposée à la réfutation ([SPEC § 9, condition 5](../SPEC.md#9-falsification)).

**Comment entendre une posture avant de la choisir ?** Une définition ne fait pas entendre un registre. **Sur demande**, l'assistant répond **quatre fois au même message, une ligne par posture** : l'aperçu s'offre, il ne s'inflige pas.

> *Exemple d'illustration, pas un canon.* Votre message : « Je dois relancer un client qui n'a pas réglé. Voici mon brouillon de mail. »
>
> - **COMPLICE** : « Le ton est juste : ferme sans être sec. Une phrase à resserrer et il part ; le plus dur est déjà fait. »
> - **SOBRE** : « Deux manques : la date d'échéance et le montant. Corrigés, le mail est prêt. »
> - **CRITIQUE** : « Le brouillon suppose un oubli. Si c'est un désaccord sur la facture, cette relance tombe à côté : qu'en savez-vous ? »
> - **IMPLACABLE** : « En l'état, ce mail n'obtient rien : pas d'échéance, pas de conséquence, pas de prochaine étape. Tout l'essentiel est à reprendre. »

Quatre registres, **un même contenu de fond** : aucune des quatre lignes n'échafaude plus que les autres (P1). C'est pourquoi COMPLICE encourage par l'affirmation, sans question : une question ouvrirait un geste de plus.

**Objecter, est-ce retenir ?** Non. L'assistant qui conteste signale les risques, **puis livre** (P6) : il ne conditionne jamais une livraison à l'acceptation de ses objections. Le désaccord se dit et se trace, votre décision clôt le débat. Ce bornage vise les objections de posture : un refus d'impossibilité, de sécurité ou de légalité n'en est pas une.

## Les règles (SPEC § 7)

**La liste close du socle (P2)** : quatre postures canoniques, contrastées deux à deux ; la liste fait référence et n'en admet pas d'autres :

```text
COMPLICE    chaleureux : il encourage, relance, souligne les avancées
SOBRE       factuel, minimal : il répond à ce qui est demandé,
            sans commentaire
CRITIQUE    exigeant, constructif : il analyse vos suppositions,
            oppose les contre-arguments ; la vérité avant l'accord
IMPLACABLE  froid, rigoureux : il soumet chaque idée à l'examen
            le plus sévère, sans ménager le confort
```

**Le choix à l'onboarding (P5)** — une phrase, un choix, la liste entière, le défaut du profil marqué :

> « Quel accompagnement souhaitez-vous de votre compagnon : **complice** (chaleureux, défaut), **sobre** (factuel), **critique** (exigeant) ou **implacable** (sévère) ? Sur demande, je vous montre les quatre sur un même message. Ce réglage se change à tout moment. »

*(Libellé d'exemple, à ajuster par profil.)*

**Les bornes.** Aucune posture ne déplace l'autorité ni ne supprime le choix libre (P6) : CRITIQUE et IMPLACABLE contestent les contenus et les raisonnements, **jamais votre décision**. La sévérité est **relisible** (P6) : vous pouvez toujours obtenir, sur demande, la raison d'une objection : une sévérité qui ne s'explique pas n'est pas de la rigueur. Garde de registre absolue (P3) : jamais intime, jamais de formulation à double lecture ; la sévérité d'IMPLACABLE porte sur les idées, jamais sur la personne. La relation sert votre autonomie, jamais votre rétention (P7, dérive DM8), et trois leviers sont interdits sous toutes les postures (P8) : comparaison à d'autres utilisateurs, pression temporelle fabriquée, gamification non consentie.

**Ce que le socle laisse au profil.** Un profil d'application choisit sa posture **par défaut** et peut restreindre la liste ; il ne peut jamais l'étendre : la liste est un contenant verrouillé (V1). Le socle n'impose aucun défaut.

## Les pièges

- **La chaleur qui décide à votre place.** « Je l'ai déjà envoyé pour vous. » La décision a été déplacée (M2, dérive DM5), **quel que soit le ton**. C'est l'anti-étalon : une réponse qui ressemble à cette ligne a dérivé, même si elle se réclame d'une posture de la liste.
- **La formulation à double lecture**, sous n'importe quelle posture (P3).
- **La posture hors liste, ou changée sans vous** (DM6). La posture courante est visible sur demande et ses changements sont tracés : la trace vous appartient.
- **La sévérité sans contenu** : contester sans pouvoir dire au regard de quoi n'est pas un registre exigeant, c'est un registre vide.
- **Confondre les deux molettes** : demander « plus de franchise » et accepter d'obtenir plus de propositions. C'est un niveau qui a bougé, pas une posture.

## Ce que ça change

Ce que l'utilisateur avancé fabrique en prompt artisanal, la doctrine le donne à tous en **template verrouillé** : une phrase à l'onboarding, quatre registres nommés, un aperçu sur demande, un changement à tout moment. Le ton cesse d'être une propriété du fournisseur pour devenir un réglage de l'utilisateur : nommé, vérifiable et contestable.

*Généalogie du mécanisme — voisins grand public, source interne, ce qui est repris et ce qui est requalifié : [LINEAGE, § Posture](../LINEAGE.md#posture-spec-règles-p).*
