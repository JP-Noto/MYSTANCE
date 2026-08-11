# Filiation & sources · MYSTANCE

**Version 0.2 · 2026-08-08 · statut : proposé.**

Cette doctrine n'invente pas ses primitives : elle les **assemble** en une norme de la relation humain-IA, dont les revendications sont énoncées sous forme réfutable ([SPEC § 9](SPEC.md)) ; cette réfutabilité est *énoncée, pas encore instrumentée* : le protocole de mesure n'est pas écrit. Ce fichier rapporte chaque mécanisme à ses antériorités connues. **Antériorité n'est pas influence** : hors lignée interne, plusieurs de ces sources ont été identifiées par la recherche d'antériorité du 2026-07-24, après formulation des mécanismes ; la convergence est rapportée parce que l'honnêteté l'exige, pas parce qu'il y aurait eu lecture ou emprunt. Là où une source a nourri la formulation (la souche ludique du nommage), la filiation est créditée dans sa section. Les pièces décisives ont toutes été vérifiées de façon adversariale sur les textes originaux ([journal](research/prior-art-2026-07-24.md), verdicts et limites déclarés). Assumer la filiation ne dilue pas la contribution : la **recontextualisation** et l'**assemblage normatif** sont la contribution.

Convention par mécanisme : **primitive connue → source datée → recontextualisation → apport.**

## La lignée interne

```text
PREMIÈRE GÉNÉRATION (2025)
  system prompt monolithique, première réponse au problème :
  cadrer la place d'un agent auprès d'un humain ;
  déjà : « trois choix cadrés… et un quatrième choix, totalement
  libre, réservé au joueur »
        │
COUCHE D'ASSISTANCE À NIVEAUX (août 2025, mtimes d'archive 2025-08-26)
  générateur 0–100 %, contrôleur 0–90 % : « minimum 10 % humain »
  et consentement d'ajustement en règles de produit, non garanties ;
  revue structurelle du 2026-07-10, domiciles vivants :
  les deux projets héritiers
        │
SECONDE GÉNÉRATION (2026)
  fiche de voix + étalon d'exemples + modules : le cadrage le plus mûr ;
  onboarding étagé : porte du retour + 3 portes tirées + choix libre
  → le motif **3 propositions + champ libre** (règles d'auteur des 07 et 08.07.2026) ;
  profil de registre changeable à chaud → la posture
        │
LIVING REFERENCE (2026)
  la couche épistémique : proposition / validation / trace ;
  templates et vocabulaires clos ; clause contenant/contenu
        │
MYSTANCE (fondée le 2026-07-11)
  la couche humaine : la relation paramétrée, distillation
  doctrinale de la lignée ci-dessus
```

Le corpus d'août 2025 fusionnait deux produits ; la séparation est actée le 2026-07-11 en deux projets héritiers, l'un de création de monde, l'autre de création d'ouvrage. Le mécanisme générique d'assistance est conservé chez les deux, en duplication assumée.

## Niveau d'assistance ([SPEC règles N](SPEC.md#3-niveau-dassistance--règles-n))

- **Primitive.** Graduer la part de la machine dans un travail partagé ; retirer l'échafaudage à mesure que l'humain monte en compétence.
- **Sources.** Sheridan & Verplank (1978, rapport original lu, Table 8.2) : les dix niveaux, « *going from a level wherein the human operator does everything to a level where the computer does everything* » ; le modèle sert « *the designer or operational manager* ». Parasuraman, Sheridan & Wickens (2000, article original lu) : la reformulation canonique : niveau 1, « *The computer offers no assistance: human must take all decisions and actions* » ; niveau 10, « *The computer decides everything, acts autonomously, ignoring the human* » ; l'échelle inclut les deux extrêmes (« *even full automation (Level 10) could be justified* »), et le titulaire du choix y est le concepteur. Horvitz (1999, vérifié) : l'initiative mixte dosée par utilité espérée, seuils réglés à la conception. L'autonomie ajustable de la robotique (Dias et al., 2008, vérifié) : contrôle déplacé en cours de mission, modes discrets, sans consentement formalisé. Wood, Bruner & Ross (1976, texte intégral vérifié) : l'**échafaudage** (le mot même, défini là) et son retrait progressif décrit empiriquement ; le terme *fading* est postérieur ; le tuteur décide du dosage.
- **Voisins à distinguer.** Parasuraman et al. (2000) recommandent des **bornes hautes et basses** de niveau par système (« *Acceptable system performance may require a certain minimal level of automation* ») : des recommandations de conception, évaluatives et révisables, à la main du concepteur ; et décrivent l'**automatisation adaptative** (le système fait varier le niveau selon le contexte, sans consentement) : précisément le comportement que la dérive DM1 nomme ; une occurrence de niveau **choisi par l'utilisateur** y figure en exemple d'appareil (photocopieur) : un choix de fonction, pas un paramètre normé de relation. Feng, McDonald & Zhang (arXiv:2506.12469, 2025, texte intégral lu) : cinq niveaux par rôles de l'utilisateur (*operator → observer*), l'autonomie posée comme « *a deliberate design decision made by agent developers* » ; leur L5 « *comes with no means for user involvement* » hormis un arrêt d'urgence ; leurs certificats prescrivent un plafond par agent : réglementaire, côté développeur, sans plancher. La branche produit 2025-2026, fouillée le 2026-08-02 ([journal](research/prior-art-2026-08-02-produits.md)) : les agents de code exposent des niveaux d'autonomie **nommés, tenus par l'utilisateur final et changeables en session** (modes de Cursor, mars 2025 ; modes de permission de Claude Code, 2025-2026 ; crans de Windsurf, février 2025) — le titulaire y est bien l'utilisateur, mais l'objet réglé est l'exécution d'actions dans un environnement technique, l'échelle est ouverte en haut (l'autonomie totale est un cran offert) et aucun invariant ne sépare l'initiative de la décision ; Devin 2.1 (mai 2025) module son autonomie sur sa propre confiance : l'automatisation adaptative de 2000, ressuscitée en produit : le contre-modèle daté de DM1 ; GPT-5.1 (novembre 2025) propose de lui-même la mise à jour des préférences : le voisin produit de N3, sans la norme du consentement.
- **Source interne.** La couche d'assistance à niveaux de la lignée interne naît en août 2025 (mtimes d'archive du 2025-08-26) et comporte deux strates : un générateur courant de 0 à 100 % et un contrôleur borné de 0 à 90 %, dont le minimum humain est déclaré au registre produit, non opposable. L'échelle y était déjà distribuée en paliers nommés à gloses comportementales (organisation, suggestion, collaboration, génération guidée, génération maximale) ; les quatre niveaux du socle en dérivent : COLLABORATION repris, APPUI renommé, GÉNÉRATION issu d'une fusion, MÉDIATION créé par la décision de plancher. L'ajustement proposé-consenti et la transparence du « qui fait quoi » y étaient natifs. Le même corpus contenait pourtant des ajustements automatiques sans consentement : la dérive que DM1 nomme, observée dans la propre source de la doctrine. Deux divergences sont assumées : le zéro d'assistance, qui décrit l'outil en veille et reste hors du domaine de la relation (décision d'auteur du 2026-07-23), et la symétrie assistance/travail humain, retirée (M2, N4). Le détail sur pièces est archivé hors dépôt et sera versé avec les pièces.
- **Recontextualisation & apport.** Dans chacune des pièces lues sur original (Wood, Bruner & Ross (1976), Sheridan & Verplank (1978), Horvitz (1999), Parasuraman, Sheridan & Wickens (2000), Dias et al. (2008), Feng, McDonald & Zhang (2025)), le titulaire du réglage est le concepteur, le manager, l'opérateur, le tuteur ou le développeur ; les bornes de niveau y sont des recommandations de conception, non des invariants garantis à l'utilisateur ; et la variation contextuelle sans consentement y est un idéal technique. Ce constat vaut pour ces pièces, et pour elles seules : il borne l'espace fouillé, il ne décrit pas la littérature entière. MYSTANCE porte l'échelle au rang de **paramètre de la relation, à la main de l'utilisateur** : réglable à tout moment sans justification (N2), ajustement du niveau proposé-consenti avec dérive nommée (N3, DM1 : les portes d'approbation de la lignée lue portent sur les *actions*, pas sur le changement du niveau lui-même), et **plafond constitutif, garanti à l'utilisateur** (N1). Le négatif d'antériorité de cette section se formule en conjonction stricte : l'assemblage « niveau d'assistance normé comme paramètre de la relation **et** utilisateur final titulaire du réglage **et** consentement requis pour tout changement de niveau **et** plafond constitutif garanti à l'utilisateur : jamais de production 100 % IA » est sans précédent trouvé *dans l'espace fouillé au 2026-07-24* ([journal](research/prior-art-2026-07-24.md)) ; un contre-exemple nommé le réfute. **Le plancher ne figure pas dans cette conjonction, et c'est délibéré** : « jamais zéro médiation » est une convention de définition du domaine, stipulative, comme un choix d'unité ([whitepaper § 3](WHITEPAPER.md), [SPEC § 1](SPEC.md)), et une stipulation est trivialement sans précédent puisqu'elle définit son propre objet ; la compter comme apport ferait porter la nouveauté par une définition. Le plafond, lui, interdit une pratique que les sources lues autorisent explicitement (« *even full automation (Level 10) could be justified* », Parasuraman et al. 2000) et la rend opposable par l'utilisateur : c'est à ce titre, et à ce titre seul, qu'il est revendiqué. Ce négatif est **suspendu** : deux pièces en réserve touchent sa composante consentement (Olson & Sarter 1999) et sa branche adaptative (Inagaki 1999), la branche automatisation adaptable / délégation n'a pas été fouillée (réserve en fin de fichier). L'espace des produits d'assistance 2023–2026, lui, a été fouillé le 2026-08-02 : le négatif en sort **tenu mais resserré** : des niveaux nommés tenus par l'utilisateur final existent en produit sur l'exécution d'actions (agents de code) ; la conjonction ne survit que par son objet (la relation d'assistance, pas l'exécution), le plafond constitutif, l'invariant M2 et le consentement d'ajustement du niveau ([journal du 2026-08-02](research/prior-art-2026-08-02-produits.md)). Tant que les lectures en réserve ne sont pas faites, cet énoncé reste une hypothèse de travail datée, pas une revendication publique.
- **Dérivation des quatre noms.** Les paliers du socle dérivent de ceux de la source interne :
  **COLLABORATION** repris tel quel ; **APPUI** renommé depuis « suggestion », pour lever la collision avec le
  terme *Proposition* ; **GÉNÉRATION** issu de la fusion de la paire « génération guidée / génération
  maximale » ; **MÉDIATION** créé par la décision de plancher.
- **Divergence assumée avec la source interne.** Elle descendait à 0 % : l'outil en veille, l'humain hors de la
  boucle. MYSTANCE norme la **relation** : tant qu'elle existe, la médiation n'est jamais nulle. Le palier
  « organisation » (0 %) de la source n'a donc **pas d'équivalent** ; MÉDIATION est le premier niveau *de la
  relation*. Les pourcentages de la lignée (générateur 0 à 100, contrôleur borné à 90) demeurent des repères de
  conception, **pas une mesure** : rien, dans la relation, ne se compte en pour cent.

## Posture ([SPEC règles P](SPEC.md#7-posture--règles-p))

- **Primitive.** Un registre de comportement de l'assistant, choisi par l'utilisateur dans une liste fermée.
- **Sources.** Le premier voisin grand public : les *conversation styles* de Bing Chat (mars 2023), Créatif / Équilibré / Précis, liste close, changeable, mais mêlés aux paramètres de génération, sans orthogonalité avec un niveau, et retirés depuis sans annonce : la révocabilité du réglage tenu par l'éditeur, sur pièce. Depuis, la liste close est devenue un dispositif standard du marché ([journal du 2026-08-02](research/prior-art-2026-08-02-produits.md)) : styles de Claude (novembre 2024 : trois presets plus styles personnalisés), presets de personnalité de ChatGPT (août 2025 : réponse déclarée de l'éditeur à l'épisode de sycophancie d'avril 2025), étendus et doublés de curseurs de caractéristiques par GPT-5.1 (novembre 2025) ; « Real Talk » de Copilot (octobre 2025) : un registre opt-in qui conteste les prémisses. Les *custom instructions* d'OpenAI (juillet 2023) : la posture en champ libre, le geste artisanal que la doctrine constate chez les utilisateurs avancés, l'inverse d'une liste close. Les modes de relation de Replika, vérifiés sur documentation produit le 2026-08-02 : liste close (ami, partenaire romantique, frère/sœur, mentor), où les registres intimes sont l'actif monétisé : le contre-modèle de la garde P3.
- **Source interne.** Le profil de registre de la seconde génération de la lignée (juillet 2026) : trois registres, défaut marqué, changement à chaud, garde de registre du 2026-07-08 (jamais intime, jamais de double lecture ; conservée en P3). La pratique des prompts de posture a une pièce datée : un export archivé au 2026-07-11 d'instructions rédigées par l'auteur pour un projet d'entreprise réel, configurant à la main un registre critique. C'est le geste artisanal que la posture CRITIQUE normalise : le constat d'usage précède la règle.
- **Recontextualisation & apport.** MYSTANCE sépare normativement ce que les produits mêlent : le **test d'admission par orthogonalité** (P1 : une posture décrit *comment*, jamais *combien* ; « guidant », hérité de la source, est requalifié en niveau par ce test), la liste close **canonique et verrouillée** (P2 : COMPLICE · SOBRE · CRITIQUE · IMPLACABLE ; restriction possible par profil, extension jamais ; et clôture exposée à la réfutation, SPEC § 9 condition 5), les gardes de dérive nommées (DM6, DM8 ; P6 : conteste les contenus, jamais la décision). Négatif tenu, en conjonction stricte : l'assemblage « registre de comportement en liste close canonique **et** orthogonal à un niveau d'assistance normé **et** gardes de dérive nommées » est sans précédent trouvé dans l'espace fouillé : les pièces du [journal du 2026-07-24](research/prior-art-2026-07-24.md) et la fouille produit du [journal du 2026-08-02](research/prior-art-2026-08-02-produits.md). Ce qui a changé au 2026-08-02 : le premier conjoint (liste close tenue par l'utilisateur, changeable) est banal depuis les presets de personnalité de ChatGPT (août 2025) : il ne discrimine plus rien ; le négatif ne tient que par la conjonction entière, les dispositifs du marché mêlant ton, verbosité et personnalité sans orthogonalité déclarée, sans contrat de comportements publié, et sous révocabilité éditeur. Ce négatif reste **dérivé** de celui du § Niveau : son conjoint discriminant, l'orthogonalité à un niveau d'assistance normé, se réfère à un objet que ce corpus définit ; il tombe donc avec lui, et un contre-exemple nommé suffit. Réserve levée : les modes de relation de Replika sont vérifiés sur documentation produit.

- **Les trois registres de la source, nommés.** Le profil de la seconde génération proposait
  « complice et cinéma » (défaut), « plus doux et guidant », « plus froid et implacable », choisis à
  l'onboarding en une phrase et changeables en cours d'usage. **COMPLICE** et **IMPLACABLE** en descendent
  directement. « Guidant » est **requalifié en niveau** par le test d'orthogonalité : guider ajoute de
  l'échafaudage, donc relève des règles N. La garde de registre du 2026-07-08 est conservée.
- **La pratique constatée des utilisateurs avancés** (observation d'auteur, non chiffrée). « Challenge-moi »,
  « sois critique », « un sceptique dirait… » posés en réglage général : l'IA devient conseillère exigeante
  avant toute demande. **CRITIQUE** en descend. C'est aussi, dans cette observation, ce qui sépare
  l'utilisateur avancé de l'utilisateur courant : tenu pour la grande majorité, sans avoir été mesuré.
- **SOBRE ne descend d'aucune des deux sources.** Il formalise le registre minimal constaté au plancher, et
  opère comme les trois autres à tout niveau.

## Trois propositions + champ libre ([SPEC règles L](SPEC.md#4-trois-propositions--champ-libre--règles-l))

- **Primitive.** Des propositions non contraignantes, la saisie libre disponible.
- **Sources.** L'antécédent le plus ancien trouvé est dans l'échelle de 1978 elle-même, révélé par la lecture directe : le niveau 3, « *computer helps determine options and suggests one, which human need not follow* » ; la reformulation 2000 en garde la gradation (« *offers a complete set of alternatives… narrows the selection down to a few… suggests one* »). Google Smart Reply (Kannan et al., KDD 2016, vérifié sur texte) : trois positions de suggestion en production de masse, et la règle de diversité par intention, « *the user should never see two responses of the same intent* », parallèle direct de la règle de contraste L3, crédité comme tel ; la disponibilité de la saisie libre y est un fait de l'interface produit, pas un énoncé du papier. Les *quick replies* des plateformes conversationnelles (2016 et suivants). Le fondement empirique du plafond : Hick (1952), Iyengar & Lepper (2000, réplications discutées), Schwartz (2004). L'architecture du choix (Thaler & Sunstein, 2008), dont la doctrine retourne la leçon des défauts : pas de défaut au nommage, défaut marqué à la posture.
- **Source interne.** La seconde génération de la lignée, onboarding étape 2 (règles d'auteur des 2026-07-07 et 2026-07-08) : trois portes tirées jamais plus, contraste vérifié, chaque porte une phrase d'envie, choix libre toujours en dernier. Le motif est antérieur : les pièces d'archéologie de la première génération (archivées le 2026-07-08) posent déjà trois choix cadrés plus un quatrième choix totalement libre, réservé au joueur, et interdisent aux agents d'y suggérer quoi que ce soit. La seconde génération a corrigé la première sur pièce datée : la voie libre reste vierge, jamais pré-remplie ; l'absurde se traduit au lieu d'être ridiculisé ; le quota de saisie libre de la première génération n'a pas été reconduit. Les règles L2, L6 et L7 distillent cette histoire ; elles ne l'inventent pas. La transposition B2B est antérieure à la fondation : les principes UX d'un produit B2B de la lignée interne (mars 2026) prescrivent déjà trois options contextuelles plus un choix libre ; pièce reconstituée depuis un journal de session, comptée avec ce caveat.
- **Recontextualisation & apport.** Dans l'espace fouillé ([journal du 2026-07-24](research/prior-art-2026-07-24.md) : l'échelle de 1978, Smart Reply 2016, les *quick replies*, la littérature du choix), aucune source lue n'érige le motif en **norme réfutable** : plafond, contraste obligatoire, choix libre garanti en dernière position. Un contre-exemple nommé le réfute ; l'espace fouillé est celui du journal, pas la littérature entière. L'apport est la normalisation : plafond à trois (L1), contraste obligatoire (L3), choix libre garanti en dernière position quel que soit le niveau (L2, dérive DM2), vierge (L6) et honoré (L7), propositions non engageantes au sens [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE) (L4), dose modulée par le niveau (L5), distinction choix ouvert / liste close (P5, pas de faux libre). L'invention du motif n'est pas revendiquée ; sa norme l'est.

- **La source, en détail.** Le mécanisme naît d'une **table de jeu réelle** : à l'onboarding de la seconde
  génération de la lignée, le choix d'un univers suit exactement cette forme (règles d'auteur des 2026-07-07 et
  2026-07-08) — **trois portes tirées**, jamais plus, contraste vérifié, chaque porte formulée en une phrase
  d'envie crédible ; puis la dernière option, toujours : « **qu'est-ce que tu as envie de VIVRE ?** »
  La doctrine généralise le dispositif à tout choix échafaudé ; la source reste intouchée, étudiée comme cas.
- **Requalification du critère de contraste.** La source disait le contraste **« en ton »** ; la norme le teste
  **en intention**. Critère convergent avec un précédent industriel crédité ci-dessus — **convergence constatée,
  pas filiation**.
- **Renommage du 2026-08-08.** Le mécanisme s'appelait « motif « 3 + libre » ». Motif du changement : le nom
  ne disait ni *trois quoi*, ni *libre quoi*. « Propositions » est un terme défini de la SPEC, et « champ libre »
  dit que le libre est **un champ vierge, pas une quatrième option**. Les journaux de `research/` portent
  l'ancien nom à leur date et ne sont pas réécrits.

## Templates verrouillés ([SPEC règles V](SPEC.md#5-templates-verrouillés--règles-v))

- **Filiation directe.** LIVING REFERENCE : vocabulaires clos (règle F3), clause contenant/contenu de sa licence (« un formulaire rempli n'est pas un dérivé »). Les primitives lointaines (formulaires, classification à facettes) sont documentées dans le LINEAGE de LR : on lie, on ne recopie pas.
- **Recontextualisation & apport.** Adoption architecturale portée aux **templates de la relation** (niveaux, postures, réglages, nom), et clause miroir conçue pour MYSTANCE ([LICENSE](LICENSE.md)) avec une divergence assumée : les templates restent protégés même vides (la structure verrouillée est l'actif), là où les formulaires vides de LR sont MIT. Pas de négatif propre revendiqué.

## Nommage par l'utilisateur ([SPEC règles C](SPEC.md#6-nommage-de-lassistant--règles-c))

- **Primitive.** L'utilisateur nomme son compagnon.
- **Sources.** Replika (Luka, Inc., 2017–) : le compagnon IA nommé à l'inscription, renommable (documentation produit), le précédent grand public direct. La souche commune est ludique : nommer son animal, son personnage (Tamagotchi 1996, jeux de rôle et d'élevage depuis les années 1980), celle-là même que la décision d'auteur invoque : pour cette famille, l'antériorité est une influence, revendiquée. Contre-modèles : Siri, Alexa et la quasi-totalité des assistants, nom imposé par l'éditeur, marque déposée ; le mot d'éveil d'Alexa se choisit dans une liste fermée de dénominations de l'éditeur, ce qui n'est pas un nom donné par l'utilisateur.
- **Recontextualisation & apport.** Replika nomme par choix produit ; MYSTANCE **norme le geste** : pas de nom par défaut (C2, dérive DM4), geste proposé, différable et re-proposé sans insistance, le nom premier champ du template verrouillé (M3 : structure à la doctrine, nom à l'utilisateur), rituel dosé au niveau (C3), règles du champ (C4), et la conséquence stratégique articulée : renoncer à toute marque d'assistant (l'espace des noms est saturé) et faire de ce renoncement un principe. L'apport est le renversement doctrinal et juridique, pas le geste de nommer.

## Souveraineté invariante (axiome M2)

- **Filiation directe.** Axiome A1 de LIVING REFERENCE (« l'IA propose, l'utilisateur décide »), appliqué à la relation. Adoption déclarée, domicile distinct : LIVING REFERENCE norme le statut du savoir, MYSTANCE norme la relation.

## L'assise empirique

L'acte de naissance daté de la relation comme objet est un constat d'auteur du 2026-07-06, au journal des décisions de la seconde génération de la lignée : « L'expérience n'est pas assez exceptionnelle, pas de relation entre l'animateur et le joueur ». Le journal en tire, le même jour, le diagnostic de séance : la mécanique était corrigée, mais il n'y avait personne en face ; le différenciateur d'un LLM est la simulation d'une présence, pas la production de texte. Tout ce que ce corpus norme (la posture, le nom, le registre) descend de ce constat-là.

Onze occurrences du même problème (cadrer la place, la voix et le niveau d'assistance d'un agent) sur des projets distincts : jeux, création d'univers, studio de production, produit B2B, OS. Quatre générations de réponse (lignée interne ci-dessus, plus la convergence indépendante constatée avec le cadrage minimal d'un OS d'IA). L'inventaire détaillé est un constat daté du 2026-07-13, **non versé** : tant qu'il ne l'est pas, le décompte « onze occurrences » n'engage que l'auteur, et la lignée se lit comme ce qu'elle est, une lignée intra-praticien, vérifiable pièce à pièce au fur et à mesure des versements (les occurrences déjà versées ou localisées sont citées dans leurs sections, avec leurs caveats). Il sera versé ou lié à une référence datée opposable le jour où le corpus s'y engage ; aucune pièce hors dépôt ne fait foi contre le texte publié.

La transversalité du problème est établie par les faits, pas par ambition. Elle fonde l'antériorité de la démarche ; elle ne démontre pas l'efficacité de la doctrine.

## Crédits externes

- **[LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE)** (JP Noto) : la couche épistémique du trio ; MYSTANCE adopte son axiome d'autorité, sa discipline de statuts et son patron de templates, et déclare la conformité de son corpus documentaire (déclaration de conformité, hors dépôt).
- **Un OS d'IA** : la couche système du trio. La doctrine est indépendante de tout hôte, présent ou futur.

## Antériorité du corpus

Ce corpus a été écrit hors du dépôt ; son historique public commence au dépôt initial. L'antériorité repose sur les pièces datées antérieures : verbatim source du 2026-07-05 (messages horodatés 09:25–10:04, retrouvés et déposés le 2026-07-11), fondation du 2026-07-11, vérifications de noms du 2026-07-12, inventaire du 2026-07-13, décisions des 2026-07-14, 2026-07-21, 2026-07-23, 2026-07-24, 2026-07-25 et 2026-07-26, journaux append-only internes du corpus. Un dépôt e-Soleau INPI de l'état initial est prévu, selon la même procédure que LIVING REFERENCE.

## Bibliographie

- Wood, D., Bruner, J. S., Ross, G., « The Role of Tutoring in Problem Solving », *Journal of Child Psychology and Psychiatry*, 17(2) (1976). [texte intégral vérifié le 2026-07-24]
- Sheridan, T. B., Verplank, W. L., *Human and Computer Control of Undersea Teleoperators*, MIT Man-Machine Systems Laboratory / ONR, rapport technique (juillet 1978). [original lu le 2026-07-24, Table 8.2, pp. 8-15–8-19]
- Hick, W. E., « On the Rate of Gain of Information », *Quarterly Journal of Experimental Psychology*, 4 (1952).
- Horvitz, E., « Principles of Mixed-Initiative User Interfaces », CHI (1999). [texte vérifié le 2026-07-24]
- Parasuraman, R., Sheridan, T. B., Wickens, C. D., « A Model for Types and Levels of Human Interaction with Automation », *IEEE Transactions on Systems, Man, and Cybernetics — Part A*, 30(3), 286–297 (2000). [article intégral lu le 2026-07-24]
- Iyengar, S. S., Lepper, M. R., « When Choice is Demotivating: Can One Desire Too Much of a Good Thing? », *Journal of Personality and Social Psychology*, 79(6) (2000). [réplications discutées]
- Schwartz, B., *The Paradox of Choice* (2004).
- Thaler, R. H., Sunstein, C. R., *Nudge* (2008).
- Dias, M. B., et al., « Sliding Autonomy for Peer-to-Peer Human-Robot Teams », IAS (2008). [texte vérifié le 2026-07-24]
- Kannan, A., et al., « Smart Reply: Automated Response Suggestion for Email », KDD (2016). [texte vérifié le 2026-07-24]
- Feng, K. J. K., McDonald, D. W., Zhang, A. X., « Levels of Autonomy for AI Agents », arXiv:2506.12469 v2, University of Washington ; publication Knight First Amendment Institute (2025). [texte intégral lu le 2026-07-24]
- Microsoft, styles de conversation de Bing Chat (mars 2023) : presse d'époque ; dispositif retiré depuis, sans annonce éditeur.
- OpenAI, *custom instructions* (juillet 2023) : documentation produit.
- Replika (Luka, Inc., 2017–), documentation produit : choix et changement du nom du compagnon ; statut de relation en liste close. [vérifié le 2026-08-02]
- Anthropic, styles de Claude (novembre 2024) : annonce éditeur et documentation produit. [fouille du 2026-08-02]
- OpenAI, post-mortems de sycophancie (29 avril et 2 mai 2025), presets de personnalité de ChatGPT (août 2025), GPT-5.1 (novembre 2025) : billets éditeur et presse datée. [fouille du 2026-08-02]
- Microsoft, Copilot « Real Talk » (octobre 2025) : annonce éditeur relayée. [fouille du 2026-08-02]
- Cursor (mars 2025), Windsurf (février 2025), Anthropic Claude Code (2025-2026, mode auto mars 2026), OpenAI Operator (janvier 2025) et ChatGPT agent (juillet 2025), Cognition Devin 2.1 (mai 2025) : changelogs, documentations et billets éditeurs : les niveaux d'autonomie de la branche produit. [fouille du 2026-08-02]
- « Offscript: Automated Auditing of Instruction Adherence in LLMs », arXiv:2512.10172 (décembre 2025). [résumé et chiffres ; non lu intégralement]

**En réserve : lectures requises avant de tenir les négatifs en public.** Aucune des pièces suivantes n'a été lue : leur contenu n'est pas connu de ce corpus ; elles sont listées parce que leur titre, ou leur signalement par la relecture professionnelle du 2026-07-24, en fait des défaiteurs potentiels des négatifs ci-dessus, au premier chef du négatif du § Niveau, suspendu à ce titre. Composante consentement : Olson & Sarter, « Supporting informed consent in human-machine collaboration » (HFES 1999). Branche adaptative : Inagaki, « Situation-adaptive autonomy » (1999). Branche automatisation adaptable / délégation, non fouillée : Miller & Parasuraman (2007), Rouse (1988), Scerbo (1996), Billings (1997), Opperman (1994), Findlater & McGrenere (2004), Amershi et al. (2019, ligne directrice G17), Shneiderman (2020) ; signalés en complément : Barber & Martin (1999), Scerri et al. (2002). Critique de l'axe unique : Dekker & Woods (2002), « MABA-MABA or Abracadabra? » : signalée par la relecture externe, non lue, discutée comme position au [whitepaper § 3](WHITEPAPER.md). Côté normatif : AI Act, article 14, repéré en fouille produit (supervision humaine exigée, adressée au fournisseur/déployeur, pas à l'utilisateur), lecture juridique fine restante. Divers : SAE J3016. La réserve « modes de relation Replika » est levée (vérifiés sur documentation produit le 2026-08-02) ; celle de l'espace produit 2023–2026 est remplacée par une dette d'entretien : l'espace bouge par trimestre, un négatif tenu contre lui porte une date. Détail, verdicts et limites : [journal du 2026-07-24](research/prior-art-2026-07-24.md) et [journal du 2026-08-02](research/prior-art-2026-08-02-produits.md).

---

*JP Noto · MYSTANCE · [licence](LICENSE.md). Domicile canonique : <https://github.com/JP-Noto/MYSTANCE>.*
