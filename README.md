# MYSTANCE

**The human layer of AI systems.**

MYSTANCE is a corpus of written rules : not software: nothing to install; rules a tool can implement, and any user can read, invoke and verify.

[Version française](README.fr.md) · if the two ever diverge, the French corpus is authoritative.

`Status: Public Draft` · `Spec: v0.3` · `License: CC BY-NC-SA 4.0 + container/content clause`

> MYSTANCE, pronounced **My-stance**. Staying in command in an AI-augmented world.

> The reference documents are in French; this README stands on its own.

## The observation: settings everywhere, a norm nowhere

One of the most asked questions about AI assistants ("how do we stay in control?") tends to call for answers of domination. It names a real risk; it also leaves a blind spot: by making the AI the sole subject of the problem, it spares the human from examining their own place in the relationship. Yet the market already offers ways to tune that place, at every level of user: one adjusts the tone within a conversation; another sets standing instructions in their product : preference fields, personality presets, styles; the most advanced install guardrails everywhere : anti-flattery prompts, mandatory counter-arguments, autonomy levels for their agents, deny-lists of actions. Tuning is not absent: it proliferates. But it proliferates **without a norm**: fragmented (tone here, initiative there, never both held together), without a published contract for tone (no preset states what it does and does not do), unevenly honored (free-form instructions above all), revocable without notice by the vendor (Bing's styles vanished that way) — and without an invariant: none of these devices guarantees that the setting modulates *how much the AI proposes*, never *who decides*. The state of the existing landscape is documented in the [prior-art journal](research/prior-art-2026-08-02-produits.md) (FR).

## The principle: tuning rather than dominating

MYSTANCE does not invent the tuning of the human-AI relationship: it proposes to **norm** it. The relationship can be tuned the way you tune a device: explicit, visible parameters, adjustable by the user : and guaranteed by written, refutable rules. The cardinal parameter is the [**assistance level**](fiches/NIVEAU-D-ASSISTANCE.md): how much the AI proposes, set on **four named levels**, **MÉDIATION · APPUI · COLLABORATION · GÉNÉRATION** (mediation, support, collaboration, generation). Each level is a contract of observable behaviors: a list of what the assistant does, and does not do, that anyone can check in use. The scale is closed at both ends: never zero mediation (a domain convention: inside an AI OS, the relationship is never null), never 100% AI production.

The proposed invariant (the one rule that never moves, whatever the setting): **the level modulates how much the AI proposes, never who decides.**

Technical terms are translated in the [glossary](fiches/GLOSSAIRE.md) (FR).

## An old problem, a new terrain

The human-machine relationship has been observed for fifty years: the levels of automation (Sheridan & Verplank, 1978), their human costs (mental workload, situation awareness, complacency, skill degradation) brought together as evaluation criteria by Parasuraman, Sheridan & Wickens (2000). Those star charts were drawn when consumer AI was science fiction; they remain good, and this corpus explicitly inherits them ([LINEAGE](LINEAGE.md)). What is new (barely three or four years) is the telescope: an AI everyone converses and works with daily, which makes that relationship observable at scale, by anyone. In other words: the reference maps already exist; the instrument to test them has only just arrived.

This corpus therefore claims no settled truth. Its method: state realistic hypotheses about this new terrain, submit them to the test bench (try them in real conditions), and keep as doctrine only what holds. Every document carries its status, every mechanism its evidence rank, that is, how solid the support behind it is ([SPEC §§ 9–10](SPEC.md)). Here, "doctrine" names a pipeline rank, not one of the layers presented below, not an earned status; that status is earned in the field. And with the telescope now in hand, observation is no longer a promise: it is a debt.

## The five mechanisms

- **The assistance level.** Four named levels with behavioral contracts, from mediation alone to framed generation. Depending on the level, the scaffolding (the aids and proposals displayed around free input) fills out or thins down. Adjustable at any time, no justification required; any adjustment the assistant suggests requires explicit consent. [`NIVEAU-D-ASSISTANCE`](fiches/NIVEAU-D-ASSISTANCE.md)
- **The stance.** The second parameter, orthogonal to the level: how the assistant carries itself. Four canonical registers in a closed list: **supportive (complice), plain (sobre), critical (critique), relentless (implacable)**, chosen in one sentence, switchable at any time. What advanced users handcraft as standing prompts, the doctrine hands to everyone as a template. [`POSTURE-DE-LA-RELATION`](fiches/POSTURE-DE-LA-RELATION.md)
- **3 proposals + free field.** The canonical shape of any scaffolded open choice: at most three contrasted proposals, and always, last, the free choice. Born at a real game table. [`TROIS-PROPOSITIONS-CHAMP-LIBRE`](fiches/TROIS-PROPOSITIONS-CHAMP-LIBRE.md)
- **Locked templates.** The doctrine defines the structure, and locks it (against silent structural changes and assistant overreach, never against you); the user fills it freely, and the content is theirs: **a filled template is not a derivative.** First template shipped: [the relationship, v0.1](templates/TEMPLATE-DE-LA-RELATION.md). [`TEMPLATE-VERROUILLE`](fiches/TEMPLATE-VERROUILLE.md)
- **Naming your companion.** The user names their assistant (the first field of the locked template, the first gesture of the relationship), offered, never forced. The doctrine ships no name and no default. [`NOMMAGE-DU-COMPAGNON`](fiches/NOMMAGE-DU-COMPAGNON.md)

Plus the behavioral synthesis: [`ASSISTANT-DE-REFERENCE`](fiches/ASSISTANT-DE-REFERENCE.md), what a conforming assistant does, and never does. Its success criterion: the user can do today something they could not do yesterday, **without the assistant in the loop**. The assistant succeeds when it is needed less.

## Four layers, four roles

| Layer | Governs |
|---|---|
| An AI OS | the system: laws, files, loops, boundaries |
| [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE) | the status of knowledge: what is validated, what is canon |
| [WORKING REFERENCE](https://github.com/JP-Noto/WORKING-REFERENCE) | how the reference serves the work: what reaches the call, served and sealed |
| **MYSTANCE** | the human's place: the tuned relationship, skill growth, sovereignty |

No redundancy: LIVING REFERENCE measures the *status of knowledge*; WORKING REFERENCE traces the *serving of the reference*; MYSTANCE measures the *human practicability of the workflow* (does the work stay doable, understandable and sustainable for the human?). The doctrine is independent of any host OS, present or future. The family is operated by the ONDE AI R&D laboratory — its portal: <https://github.com/JP-Noto/ONDE>.

## Who it is for, and where it stands

MYSTANCE is for anyone who works with an AI assistant: the relationship it governs exists as soon as a human and an assistant work together, whatever the trade, the expertise or the size of the organization. The core is the same for everyone; domain variations live in the [application profiles](profiles/index.md).

Read the status line before the promise: no deployment has taken place ([SPEC § 10](SPEC.md)); validation in real use remains to be done; a first field case is envisioned, not named at this stage, where the doctrine will face its own failure conditions ([SPEC § 9](SPEC.md)).

### And concretely, today?

- **You run a company**: this corpus does not install; it reads, and it arms. The [sheets](fiches/index.md) and the [glossary](fiches/GLOSSAIRE.md) give three questions to ask of any assistant you are being sold: who decides? who holds the settings? does the free choice still exist? The sheet ["Your data and your responsibilities"](fiches/VOS-DONNEES-ET-VOS-RESPONSABILITES.md) states honestly what the doctrine does not cover.
- **You build a tool**: implementing the rules is expressly free ([LICENSE](LICENSE.md)); a conforming tool applies a declared application profile, which sets the default level and stance ([SPEC N6, P2](SPEC.md)).
- **You are in the field, or simply demanding**: the corpus publishes its refutation conditions, that is, what, if observed, would prove the doctrine wrong ([SPEC § 9](SPEC.md)), and its genealogy, where its ideas come from ([LINEAGE](LINEAGE.md)). Counter-examples are a service rendered.

## Two reading paths

**User path** (the order of the relationship): [`NOMMAGE-DU-COMPAGNON`](fiches/NOMMAGE-DU-COMPAGNON.md) → [`NIVEAU-D-ASSISTANCE`](fiches/NIVEAU-D-ASSISTANCE.md) → [`POSTURE-DE-LA-RELATION`](fiches/POSTURE-DE-LA-RELATION.md) → [`TROIS-PROPOSITIONS-CHAMP-LIBRE`](fiches/TROIS-PROPOSITIONS-CHAMP-LIBRE.md) → [`TEMPLATE-VERROUILLE`](fiches/TEMPLATE-VERROUILLE.md) → [`ASSISTANT-DE-REFERENCE`](fiches/ASSISTANT-DE-REFERENCE.md).
**Normative path**: [`SPEC.md`](SPEC.md) first, then the [whitepaper](WHITEPAPER.md) for the why.

| File | Role | Language |
|---|---|---|
| [`SPEC.md`](SPEC.md) | The normative rules: terms and rule families N, L, V, C, P | FR |
| [`WHITEPAPER.md`](WHITEPAPER.md) | The rationale: why each rule exists | FR |
| [`LINEAGE.md`](LINEAGE.md) | Lineage, credits, anteriority (verified against original texts) | FR |
| [`fiches/`](fiches/index.md) | The fiches: mechanisms, cross-cutting references, and the [glossary](fiches/GLOSSAIRE.md) | FR |
| [`templates/`](templates/TEMPLATE-DE-LA-RELATION.md) | The locked templates (the relationship, v0.1) | FR |
| [`profiles/`](profiles/) | Application domains (the concept; no profile declared) | FR |
| [`research/`](research/) | Prior-art journal (two dated entries; scholarly pieces verified against original texts) | FR |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to propose, and under which license | FR |
| [`CHANGELOG.md`](CHANGELOG.md) | Versions | EN |

## Born from practice

The same answer to the same problem (framing an agent's place, voice and assistance level alongside a human) has been rebuilt across four generations. The author records eleven occurrences (inventory not yet deposited), on distinct projects: games, world-building, a production studio, a B2B product, an OS ([LINEAGE](LINEAGE.md)). The doctrine distills that lineage; it does not invent it. It also states what is proven and what is not: evidence ranks and falsification conditions live in the [SPEC §§ 9–10](SPEC.md).

## What is proven, what is not

Every claim in this corpus carries its evidence rank ([SPEC § 10](SPEC.md)).

| Mechanism | Evidence rank |
|---|---|
| 3 proposals + free field · the stance (as a parameter) | **usage precedent**: at least one real, dated, unmeasured occurrence |
| Assistance level · canonical stance list · locked templates · non-capture guards · settings trace · limits field · user naming | **specified**: the rule is written, no deployment |

No mechanism reaches "measured" or "replicated": no instrumented field, to date.

The candidate metric, and the central promise: **the user's autonomy grows**; by the horizon, they do, without the assistant in the loop, a task they could not do at the start ([SPEC § 9](SPEC.md), condition 1). If it does not grow, the doctrine fails. The most distinctive claim (the setting held by the user, not the designer) is also the most exposed to refutation (condition 4): if a user-held setting does no better than a design-fixed one, MYSTANCE's own contribution falls.

A boundary, finally: the doctrine **organizes the relationship** (who decides, how much the AI proposes, how it carries itself). It does **not guarantee generation**: that a model respects the level and context it is given is a property of today's models, not of the doctrine.

## Authority

In case of divergence, `SPEC.md` wins: a sheet that contradicts it is itself a drift. This corpus was written outside the repository; its public history starts at the initial deposit. Anteriority rests on the earlier dated records cited in [`LINEAGE.md`](LINEAGE.md).

## Related work

The doctrine's lineage (sources, what is reused, what is **requalified**, what is contributed) is held
**mechanism by mechanism** in [`LINEAGE.md`](LINEAGE.md), on pieces read **in their original text**. Two dated
prior-art journals record the state of the field: [the scholarly space](research/prior-art-2026-07-24.md) and
[market products](research/prior-art-2026-08-02-produits.md).

Human-machine relations have been studied for fifty years, and this corpus says so rather than omitting it:
Sheridan & Verplank (1978), Parasuraman, Sheridan & Wickens (2000), Wood, Bruner & Ross (1976), Horvitz (1999)
— alongside consumer neighbours, including Bing's *conversation styles*. **In nearly all of these, the holder
of the setting is the designer, the operator or the developer.** That is where (and only where) MYSTANCE
proposes something else: **the setting held by the user**, which is also its claim most exposed to refutation
([SPEC § 9](SPEC.md#9-falsification), condition 4).

## License & attribution

The doctrine's texts: [CC BY-NC-SA 4.0](LICENSE.md), attribution *JP Noto, MYSTANCE*. Container/content clause (the container is protected, the content is yours): the locked templates are the doctrine's protected asset, including when empty; filling them is expressly free, and **a filled template is not a derivative**: what you put in, down to your assistant's name, is yours.

---

*JP Noto · MYSTANCE · [CC BY-NC-SA 4.0](LICENSE.md). Canonical home: <https://github.com/JP-Noto/MYSTANCE>.*
