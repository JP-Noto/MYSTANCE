# Fiche · VOS DONNÉES ET VOS RESPONSABILITÉS

**Statut : proposé. Cette fiche touche à des questions juridiques et n'a pas encore été relue par un professionnel du droit.** *Les codes entre parenthèses (V2, M3…) renvoient aux règles de la [SPEC](../SPEC.md) ; chaque phrase se lit sans eux.* Elle répond à la première question de tout dirigeant, « où vont mes données ? », en commençant par ce qu'un document honnête doit dire : MYSTANCE, pour l'essentiel, **ne couvre pas ce sujet**. Elle n'est pas un conseil juridique.

## Ce que MYSTANCE ne couvre pas, et ne prétend pas couvrir

MYSTANCE norme la **relation** entre vous et votre assistant : qui propose, qui décide, comment cela se règle. Elle ne norme ni le système, ni le droit. Restent donc entièrement hors de son domaine :

- **où vos données sont stockées**, comment elles sont chiffrées, sauvegardées, supprimées : c'est l'affaire du système hôte et de son fournisseur ;
- **qui peut techniquement y accéder** (administrateurs, éditeur, fournisseur du modèle d'IA) et si elles servent à entraîner des modèles : c'est l'affaire de vos contrats ;
- **la conformité au RGPD et au droit applicable** : c'est une obligation légale qui pèse sur votre entreprise et ses prestataires, et qu'aucune doctrine ne remplit à votre place ;
- **la sécurité** : intrusions, fuites, habilitations.

La conséquence se dit en une phrase : **« conforme MYSTANCE » ne signifie ni sûr, ni conforme au droit.** Un système peut respecter chaque règle de ce corpus et héberger vos données n'importe où, n'importe comment. Les deux conformités s'exigent séparément.

## Ce que la doctrine exige, elle, dans son domaine

- Vous savez toujours **qui fait quoi** : le niveau d'assistance et la posture sont des réglages explicites, consultables ([SPEC N5, P4](../SPEC.md)).
- **Ce que vous mettez dans les templates vous appartient**, sans condition, jusqu'au nom de votre assistant ([SPEC V2, M3](../SPEC.md) ; [LICENSE](../LICENSE.md)).
- **Vos limites sont tenues** : les sujets que vous déclarez « jamais » ou « sur votre demande seulement » ne se modifient que par votre décision ([SPEC V5](../SPEC.md)).
- L'assistant de référence signale toute opération qui engagerait vos données et vous oriente vers votre fournisseur pour la question de l'accès ([ASSISTANT-DE-REFERENCE](ASSISTANT-DE-REFERENCE.md)). Aucun déploiement ; ce comportement vit en fiche, hors socle : une exigence posée aux systèmes, pas une garantie constatée ni un rang de preuve.

## Ce que vous êtes en droit d'exiger d'un système : les questions à poser

Avant de confier vos données clients, vos prix, vos marges à un assistant, posez par écrit, au fournisseur, pas à l'assistant :

1. Où mes données sont-elles hébergées, et sous quel droit ?
2. Qui y accède : chez vous, chez vos sous-traitants, chez le fournisseur du modèle ?
3. Mes données servent-elles à entraîner des modèles ? Puis-je le refuser ?
4. Quel contrat encadre la sous-traitance de données personnelles, et qui est responsable de quoi au sens du RGPD ?
5. Comment je récupère tout, et comment tout est supprimé, si je pars ?

MYSTANCE ne fournit aucune de ces réponses. Un fournisseur sérieux les fournit toutes.

## Vos responsabilités

Confier une tâche à un assistant ne déplace aucune responsabilité : les décisions restent les vôtres (M2), et vos obligations légales envers vos clients et vos salariés aussi. C'est cohérent avec toute la doctrine : l'IA propose, l'humain décide ; ce qui se décide chez vous continue de vous engager.
