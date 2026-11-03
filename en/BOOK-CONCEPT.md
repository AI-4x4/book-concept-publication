> English translation. Quotations are translated; consult the [Russian source](../ru/BOOK-CONCEPT.md) for exact wording. Source status and limitations are unchanged.

# The Book as a Way to Preserve and Develop Intent

Albert Toma’s Concept

Intent follows a long path: discussion, description, requirements, design, implementation, verification, development. At each transition, it has to be explained anew and expressed through different means. Along the way, individual decisions may seem reasonable while the resulting whole gradually departs from the original idea.

We will call this shift Idea drift. It can occur even with detailed documentation, good recall among participants, and formal compliance with requirements. People can remember individual agreements accurately while gradually changing the meaning of what those agreements were made for.

**The Book is a coherent, evolving representation of intent, its grounds, the decisions made, and significant relationships. Its purpose is to counteract Idea drift as intent is communicated, developed, and realized.** It helps maintain the connection between what is intended, why a particular decision was chosen, what is being done, and what result has actually been achieved.

## How Drift Arises

Imagine a project intended to help people understand a complex subject on their own. During discussion, requirements emerge for convenience, speed, and answer quality. The team then begins measuring success by how quickly the user receives a ready-made solution.

Each individual improvement may be useful. Yet the user’s ability to work things out independently gradually drops out of consideration. The system becomes good at solving a different problem.

Drift can arise in the definition of a word, the choice of a metric, a convenient assumption, or a local optimization. It can be difficult to notice in a single change. That is why it is important to preserve the relationships between decisions and the original meaning.

As intent moves from discussion to plans, tasks, code, and checks, it takes different forms. A meaningful connection must be maintained between these representations.

## The Book as the Root SoT

The Book is the system's root source of truth (SoT). Specifications, architecture, plans, and other project documents are derived from it: they develop intent and adopted decisions for their own tasks while retaining a connection to the grounds, their versions, and their scope. Adding detail does not authorize silently changing the intent. The Book may consist of several connected materials; individual projects and audiences retain their boundaries.

Root status does not mean infallibility. Original evidence retains its own provenance, and an observed result may contradict the documented description. A discrepancy calls for checking both the derived material and its grounds. A revision to the Book adopted by an authorized decision requires checking the affected derived materials and consequences. Agreement among documents derived from one error is not independent confirmation.

## What the Book Holds Together

The Book connects several questions:

- **Intent.** What do we want to achieve, for whom, and why?
- **Concepts and boundaries.** What do the key words mean, and which properties are essential to the idea?
- **Grounds.** What information, observations, and assumptions are we relying on?
- **Decisions.** What has been chosen, for what reason, and under whose authority?
- **Open questions.** What do we not yet know, and which contradictions remain unresolved?
- **Result.** What evidence can be used to judge whether the result matches the intent?

The coherence of this information matters. For any significant decision, it should be possible to reconstruct which part of the intent it realizes and on what grounds it was made. For any significant requirement, it should be possible to find its expression in the work and the result.

The form depends on the task. The Book may be a short text or a system of interconnected materials. Specialized documents, source data, code, and evidence of execution retain their own roles. The extent of the description should help people understand the whole and make decisions.

## Surrounding Context

Understanding intent requires the surrounding context: the author's relevant goals and meanings, information about users and the organization, working conditions, constraints, and significant external relationships. This information may be distributed across different materials. The Book connects the necessary parts of the context while distinguishing direct statements, observations, interpretations, and adopted decisions.

A user profile is one representation of this context. If the task concerns a company, a Company Book is also needed: its purpose, goals, adopted decisions, roles and authority, commitments, and operating conditions. It may be maintained separately or together with the User's Book; a combined account must keep personal and corporate positions distinguishable. A participant's personal preference does not by itself become a company decision.

The Book includes context relevant to understanding and checking the task at hand. Possessing information does not grant permission to use or disclose it to every audience; its source, scope of applicability, and permitted recipients must be preserved.

A profile of an author, user, or company may be incomplete, mistaken, or out of date. An inferred preference does not replace an explicit decision, and writing style does not establish identity or authority. A conflict between an older profile and a current instruction requires checking scope, source, and current authority; a guess cannot fill an unknown.

## Developing Intent

An Idea can be enriched, refined, and changed. New data may reveal that a premise is mistaken, while testing may uncover a significant limitation of the original solution.

Preserving intent is therefore compatible with revising it on sound grounds. It is important to distinguish development from unnoticed substitution: what exactly changed, why the change was needed, and how it relates to other decisions.

If a premise changes, the conclusions that depend on it should be reconsidered. If a new goal is proposed, it must be explicitly stated and accepted by whoever has the authority to define it. A deviation that has already been implemented does not, by itself, become a new intent.

In the example above, one could consciously choose to create a service offering ready-made answers. That choice would change the project’s goal. The Book should keep this transition and its grounds visible.

## Contradictions and Completeness

The minimum requirement for an Idea is a check for contradictions and completeness.

Checking for contradictions concerns meaning. For example, a promise to develop independent thinking may conflict with a design that encourages people to obtain an answer without trying to understand. The contradiction needs to be investigated: it may indicate a flawed decision, an ambiguous concept, or a need to revise the goal.

Completeness is defined relative to the intent, the task, and the current stage. A first prototype and an operational product require different levels of detail. The key question is whether the description is sufficient to realize the necessary whole, or whether a critical transition still rests on an unstated assumption.

During verification, one can try to reconstruct the proposed system from its description: who acts, what happens, how the parts are connected, and what consequences arise. Gaps in that reconstruction remain open questions. A plausible guess still requires verification.

## Preserving Meaning and Checking the Grounds

The Book does not make a recorded statement true. It is possible to develop an intent consistently while relying on mistaken assumptions. Project participants may agree with one another while using the same sources and sharing the same errors.

Two related checks are therefore needed: whether the work matches the intent, and whether the factual propositions on which it rests are sufficiently supported.

In the learning example, the first step is to define what kind of independence is to be developed. The next is to check whether the proposed method actually helps a person solve new problems. The mere existence of a description, a prototype, or a positive review does not establish this.

An unknown, a hypothesis, and an adopted decision have different meanings. Distinguishing between them makes it possible to continue working while keeping visible what remains to be established.

## From Concept to Implementation

The Book is the system's root SoT; the specification and other project documents are derived from it. As the author clarifies, it distinguished between the idea and its technical implementation from the outset, to avoid conflating them as far as possible. The idea describes what should be achieved and why; the technical part describes how it is to be realized and what has actually been implemented.

These parts are connected: a technical solution must serve the intent, while implementation constraints and results may provide grounds for explicitly revising it. At the same time, replacing a technical method does not in itself mean changing the idea. This distinction does not require complete isolation of the parts or a predetermined number of documents.

Tasks, architecture, code, tests, and instructions are created as derivative representations of intent. A technical specification, if required for a particular task, likewise becomes such a derivative document. Each serves its own purpose and must preserve the essential meaning of the original idea.

Meanwhile, the actual implementation shows what has been created and how it works. Comparing intent with execution is necessary in both directions: requirements are checked against the result, and the properties discovered in the result are brought back for consideration of the grounds and decisions.

Passing tests confirms the properties checked under the test conditions. A separate question remains: whether the checks themselves correspond to the purpose for which the product was created. In our hypothetical example, the speed of obtaining an answer can be measured accurately and still fail to adequately characterize the learner’s independence.

## Working Together on Intent

The Book provides a shared foundation for understanding the whole. At the start of the work, the intent may be incomplete, records may be scattered, and significant constraints may not yet have been agreed upon. Participants connect materials, identify gaps, and develop options. It is important to distinguish the author’s initial propositions, other participants’ proposals, and decisions that have already been adopted.

Such collaboration requires distinguishing desire, knowledge, and authority. The author defines the intent within their domain. A factual statement requires appropriate grounds. A new capability or the technical availability of an action does not, by itself, grant permission to perform it.

The Book can also be applied to its own development: its propositions are refined in light of accumulated experience, contradictions, and the results of its use. Self-application provides material for testing the approach; conclusions about its effectiveness require separate evidence.

### The User's Book and the Assembly of the First Book

According to the author, the user's (operator's) own knowledge base was intended from the outset to support reconstructing and preserving their intent. It may include correspondence available for the task, personal and project documents, earlier decisions, examples of accepted and rejected results, and accumulated experience. The very first Book may be **the User's Book**: a coherent representation of their intentions, significant concepts, grounds for decisions, and experience, reconstructed from these materials and clarified with them. The knowledge base supplies source material for this assembly; the Book identifies and preserves significant relationships of meaning.

This arrangement makes it possible to compare a brief task statement with its origins and specific cases. For example, the meaning of "convenient" can be clarified by examining which difficulties the user wanted to remove and which results they considered suitable or unsuitable. Assembly distinguishes the user's statements, the system's proposals, and adopted decisions; it preserves references to original materials, circumstances, and changes of position. Contradictions and gaps are presented for examination, and a system assumption does not become a user decision. Where significant materials are unavailable, the corresponding understanding remains unverified and requires clarification.

The User's Book may support subsequent project Books. A specific project draws on information that is relevant to it and permitted for its participants, retaining the circumstances and limits of the original decisions. This arrangement helps interpret an individual request within the user's broader context while taking their current explicit decisions into account.

The knowledge base makes it possible to recheck an interpretation against original evidence and seek information that contradicts it. Its size alone does not guarantee correct understanding. An earlier decision may no longer apply, a summary may lose a condition, and several records may repeat the same error. Selected materials are therefore checked for relevance, currency, and permitted use. The expected benefit is less loss of meaning and less repeated explanation; the actual effect must be established through the results of the work.

## How to Start with a Small Task

For an initial application, one can choose a project where expectations and results are already diverging. State the intent, define the essential concepts, identify the grounds, and reconstruct the reasons behind several important decisions. Then trace their connections to the requirements and the resulting outcome.

A practical question for this work is: **can the result produced and the grounds preserved be used to reconstruct what was intended, why these decisions were chosen, and what remains unverified?**

The benefits of the approach should be assessed through specific cases: whether the essential meaning is preserved, whether significant discrepancies are detected, how many clarifications and corrections are required, and what the full cost of the work is. Having a Book does not guarantee a successful project. Its value remains to be demonstrated by how well it helps preserve and develop intent on sound grounds in real-world activity.


---

Supplement dated November 2, 2026. The original edition is dated November 1, 2026.


Correction dated November 3, 2026: the Book as the system's root SoT; derived documents and checking their grounds.
