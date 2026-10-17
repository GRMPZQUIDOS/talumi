# The Talumi method

**Blind independent paths, compared after the fact, decided by a professional.**

## 1. The problem

A translation can be fluent and still unfaithful. In a contract, a code or a manual, a changed condition, exception, negation or subject can change the scope of a sentence without producing a sentence that looks wrong. Reviewing the language is not enough: the review must check the relations the text expresses.

A professional understands these relations, but attention and time are limited. An automatic system can multiply checks, but it can also repeat a wrong reading with confidence. Talumi organises the two together.

## 2. One translation, several checking paths

The work file contains a fixed source text (version, date, origin, scope) and the professional's translation. Articles, paragraphs, titles and cross-references keep stable identifiers.

Checking paths can include, for an Italian source translated into French:

- Italian → direct analysis of meaning
- Italian → French, as an internal counter-version
- Italian → Swedish → French
- Italian → Korean → French
- other languages, chosen for the distinctions they can bring out

Languages with different roots force different decisions: one language must say who acts, another must mark time, another distinguishes "and" from "or" more strictly. Where the paths come back different, the source deserves a closer look. Linguistic distance is a means of exploration, not a certificate of reliability: a weaker language can add noise. The number and choice of languages are tested and adjusted.

Intermediate versions are checking material. The version delivered to the client is the professional's. No vote between model outputs replaces it.

## 3. Blind, then confronted

**Blind.** Each path works without access to the others or to the professional's translation. It receives the source and its instructions, and records a frozen result before any comparison. Inside a path such as Italian → Korean → French, the second step necessarily receives the Korean output: blindness applies between paths. Independence is enforced by the orchestration software, not promised by a model. The professional's first translation is also recorded before they see the counter-versions.

**Confronted.** The comparison looks for disagreements and also for fragile agreements: several outputs can repeat the same error, because different models can share training data and habits. Every resolution goes back to the source passage and, when needed, to documented references. Agreement is a clue; the decision still needs a reason.

## 4. Nodes: uncertainty and consequence

A node is a passage where meaning, structure or consequences call for attention. Two dimensions stay separate: the uncertainty detected, and the severity of a possible error.

| Possible consequence | Little uncertainty | High uncertainty |
|---|---|---|
| Low | Sample check | Targeted check |
| Significant | Reinforced check | Priority human check |
| Critical | Systematic human validation | In-depth validation, specialist if needed |

A passage can be stable across every path and still be critical. Priority depends on the consequences, the reach of the effects and how hard an error would be to discover after delivery, not on a model's confidence score.

## 5. What is compared

Persons concerned, actions, obligations, permissions, prohibitions, conditions, exceptions, negations, time effects, numbers, units and cross-references. Talumi separates differences of wording from differences of scope, and shows the exact passages.

## 6. Same question, several paths

When the direct analysis and the Korean path raise the same question, both flags are kept and shown together with their origin. Two flags make a question more visible; they are not two independent proofs. Talumi says whether the paths used the same model or a common step. A single flag stays visible: it may be the only one that found a real problem.

## 7. The professional decides

The professional receives an ordered file: source passage, their translation, agreeing and diverging elements, references, stakes and the question to settle. They keep their translation, change it, ask for further checks or call a specialist. Each decision is recorded with its reason. Corrections are followed by a consistency check across the whole document. Open questions stay open; they are never turned into silent validations.

## 8. Proof that checks really ran

The orchestration software runs the model calls; a model cannot replace that with a story saying it consulted other models. For each path, Talumi records the provider, the model reported by the API, parameters, start and end times, the request identifier when available, inputs and outputs or their hashes, dependencies between steps and failures. A failed path is shown as failed. The final file distinguishes checks planned, run, incomplete and not run.

## 9. Measuring the result

Talumi aims to be more reliable than a professional working without it and than AI alone. The evaluation compares three conditions (professional alone, AI alone, professional with Talumi) with the same delivery requirements, assessed blind by qualified reviewers. The main indicators: remaining meaning errors and their severity, critical problems found, false alarms, and the professional's time. The contribution of pivot languages is tested separately.
