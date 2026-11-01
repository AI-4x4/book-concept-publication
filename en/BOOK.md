# The Book as a Way to Preserve and Develop Intent

Albert Toma

Edition dated November 1, 2026

## Contents

- [Abstract](#section-1)
- [1 The Problem the Book Addresses](#section-2)
- [2 What Must Be Kept in View](#section-3)
- [3 How the Parts Are Connected](#section-4)
- [4 How to Distinguish Development from Drift](#section-5)
- [5 A Running Example of an Educational Workshop](#section-6)
- [6 An Example of a Change in Grounds](#section-7)
- [7 An Example of Complex Interaction](#section-8)
- [8 Checking the Concept and Its Implementation](#section-9)
- [9 Relationship to Other Working Materials](#section-10)
- [10 How to Begin Without Unnecessary Procedure](#section-11)
- [11 Development and Self-Application](#section-12)
- [12 Limitations and Open Questions](#section-13)
- [13 Self-Application and Revising the Book](#section-14)
- [14 Aging and Accumulating Errors](#section-15)
- [15 Reuse and the Limits of Transfer](#section-16)
- [16 A First Complete Book Example](#section-17)
- [Appendix A Glossary](#section-18)
- [Appendix B Questions for Analysis](#section-19)
- [Appendix C Status and Contents of the Edition](#section-20)

<a id="section-1"></a>
## Abstract

When intent is passed to other participants, translated into requirements, and implemented, its meaning can gradually change. Individual decisions remain reasonable, documents are consistent, checks pass, yet the resulting whole now serves a different purpose. Such a shift is called drift of the Idea here.

**The Book is a coherent, evolving representation of intent, its grounds, the decisions made, and significant relationships. Its purpose is to counteract drift of the Idea as intent is communicated, developed, and implemented.**

The Book connects the questions “what is intended,” “why this decision was chosen,” “what it is based on,” “who has the authority to change it,” and “what the outcome was.” Its form may be a short note or a system of linked materials. Checking for contradictions and completeness is a minimum requirement; completeness is defined relative to the intent, task, and stage.

Preserving meaning and establishing the reliability of grounds require different checks. An erroneous idea can be implemented faithfully. A working product can be created that has lost a significant part of the original intent. The result’s correspondence to the intent is therefore considered together with the support for factual claims.

The report is intended for project authors, managers, and collaborators who need to keep the whole in view amid change. It explains the basic concept and suggests ways to begin applying it. The practical examples in sections 5-7 are hypothetical: their decisions and proposed checks are not presented as test results. Historical episodes are placed in section 11.

<a id="section-2"></a>
## 1 The Problem the Book Addresses

Intent rarely becomes a result in a single step. It is discussed, described, divided into tasks, passed to those carrying them out, and expressed in architecture, rules, and actions. Participants see different parts of the whole and make local decisions.

Meaning can be lost at every transition. The word “convenient” begins to mean fewer actions, although the author meant fewer difficulties. The word “done” turns into the existence of a file, although the person needs a working way to solve a problem. Success is measured by an indicator that is easier to obtain, and people gradually forget what useful change it was meant to reflect.

Documents can accurately preserve individual agreements. The difficulty arises in the relationships between them: why a requirement appeared, which property of the intent it preserves, and when it should be reconsidered. If these relationships are lost, reconstructing the project becomes a matter of guessing from the surviving fragments.

The Book proposes preserving significant relationships along with the content. It should be possible to trace a decision back to its purpose and grounds. For an important part of the intent, it should be possible to find its expression in requirements, work, and results. A missing link can be marked as an open question and investigated, rather than filled with a convenient guess.

This does not imply a need to describe every step in detail. A description is useful as long as it helps people understand the whole, choose an action, or check a result. Simple work may need only a short Book; a complex project may require separate domain-specific documents.

<a id="section-3"></a>
## 2 What Must Be Kept in View

### Intent and Essential Properties

Intent answers the question of what change is needed, for whom, and why. Preserving it requires distinguishing the properties on which its meaning depends from the current ways of implementing them.

For example, “the participant independently works through a new problem” may be an essential property of an educational project. A video lesson, an in-person meeting, and a set of exercises are implementation options. Replacing a video with a meeting may preserve the intent. Removing independent work while retaining all the videos may change it.

Whether a property is essential is determined by the particular intent. No universal list of mandatory properties for every project is assumed here.

### Concepts and Boundaries

Ambiguous words should be explained wherever their meaning affects a decision. “Independence” may mean the absence of hints, the ability to explain the reasoning behind a solution, or the opportunity to choose a course of action. These alternatives require different checks.

A boundary also shows which tasks the project takes on and which fall outside its scope. It makes it possible to distinguish a missing part of the necessary whole from an attractive extension.

### Grounds and Decisions

Grounds explain why a proposition deserves consideration: they may be an observation, a document, a check result, or an explicitly stated assumption. A decision establishes a chosen direction within a defined scope of authority.

These roles differ. The statement “visitors come after work” requires factual support. The decision “hold classes in the evening” requires a choice and the authority to manage the schedule. A new observation may call the decision into question, but does not by itself establish a new schedule.

### Work and Results

The Book should make it possible to trace what has been done to implement a decision and what evidence demonstrates the result. Assigning someone to the work, starting it, obtaining intermediate material, and achieving a useful outcome have different meanings.

For a long-running task, it is also important to preserve what remains unfinished: what is still unknown, who is continuing the work, and what next step is actually available. Recording an intention to continue does not confirm future execution.

<a id="section-4"></a>
## 3 How the Parts Are Connected

A simplified reading framework looks like this:

> Intent → essential properties → decisions → work → observable result.
>
> Grounds support decisions; constraints and authority define permissible actions; checking the result brings questions back to the intent, grounds, and decisions.

This is a framework of meaningful relationships, not a mandatory linear sequence. An observation may arise during execution, bring the work back to the definition of a concept, and require a different decision.

The Book can be viewed as a graph: propositions and materials are connected by relationships such as “supports,” “clarifies,” “implements,” “checks,” “constrains,” and “contradicts.” Merely indicating that a connection exists is not enough. Its meaning and the conditions under which it holds must be understood.

| Relationship | What it helps establish | Error in interpreting the relationship |
| --- | --- | --- |
| Grounds support a decision | Why the decision was chosen and when it should be reconsidered | Treating any mention of a source as sufficient proof |
| A requirement expresses a property of the intent | What will be lost if the requirement is removed | Treating every historical requirement as immutable |
| A check relates to a result | Exactly which property was checked | Extending the success of one check to the readiness of the entire project |
| A change affects a dependent proposition | Where a new assessment is required | Revoking all neighboring decisions merely because they share a section |

If two propositions use the same source, they do not become two independent confirmations. If material is connected to many other materials, that does not yet mean that all the connections are useful or correct.

### The Idea and Technical Implementation

The Book entered practice as a replacement for the technical specification in the role of the project’s main reference. From the outset, it distinguished the idea from technical implementation so as to avoid mixing them wherever possible. According to the author’s clarification, this was the original framework, not a later consequence of representing the Book as a graph.

The idea answers the questions “what should result, for whom, and why.” The technical part describes the chosen means of implementation, its constraints, and the actual state of implementation. The connections between them are preserved: a decision must be justified by the intent, while observed constraints may require an explicit revision of the idea. A change in the implementation method does not in itself change the intent. “Wherever possible” preserves the necessary interaction between the parts and does not prescribe a rigid format or a complete separation of all information.

### The Overall Book and Specialized Documents

A precise description of an architecture, calculation, contract, or procedure may be held in a separate document. The Book maintains its purpose and significant connections to the whole. The specialized document retains its own precision, scope, and amendment procedure.

This makes it possible to avoid two extremes: overloading the general text with every detail or leaving details disconnected from the intent. For complex areas, separate domain-specific representations are acceptable if their interaction is clear and the significant commitments between them are preserved.

<a id="section-5"></a>
## 4 How to Distinguish Development from Drift

The Idea can change. New information can disprove a premise, use can reveal a limitation, and the author can consciously choose a different goal. Preserving intent does not mean prohibiting such changes.

A justified revision makes the transition visible: what is changing, why, who made the decision, and which dependencies require reassessment. Drift occurs when a significant substitution goes unnoticed or is presented as a continuation of the previous meaning.

| What changed | What should be checked | What the change does not establish by itself |
| --- | --- | --- |
| A factual premise | Which conclusions it influenced and whether other support exists | A new goal or permission to act |
| The author’s intent | Who has the authority to change it and which properties are now essential | The truth of factual statements |
| The implementation method | Whether the required properties and permissible constraints have been preserved | The acceptability of the result merely because a new version exists |
| Authority or an available resource | Which actions are now permitted and feasible | The right to restore what was revoked through another route |

A useful question when making a change is: “If this amendment is accepted, what will become possible, what will cease to be mandatory, and who will notice the consequences?” It helps reveal a non-obvious expansion of meaning, but answering it still requires domain-specific grounds.

<a id="section-6"></a>
## 5 A Running Example of an Educational Workshop

### Original Intent

Imagine a workshop that helps adults independently work through everyday financial problems. This is a hypothetical example. Its purpose is to demonstrate working with relationships; the decisions below are proposed for examination.

The author states the goal: after the classes, a participant should be able to analyze a new problem, identify the significant conditions, and explain the chosen approach to solving it. Obtaining the correct answer to a familiar exercise is useful, but insufficient for this goal.

Independent analysis of a new situation and the ability to check the reasoning are selected as essential properties. A constraint is the absence of access to participants’ personal financial data. These propositions establish a framework within which the class format can be chosen.

### From Intent to Decisions

| Proposition | Proposed decision | What can be observed |
| --- | --- | --- |
| The method needs to transfer to a new situation | After working through an example, give an unfamiliar problem with changed conditions | The participant identifies the conditions and explains the choice of method |
| It is important to understand the reasoning | Ask for a brief explanation of why this particular step was chosen | It is apparent whether the person distinguishes a rule from an instance of its application |
| Personal data is not required | Use fictional amounts and situations | No information about real accounts is requested in order to complete the class |
| An accessible first result is needed | Start with one short class | The essential chain can be checked without a full course |

The observations in the last column are not yet confirmed results. They show what evidence should be collected.

### How Substitution Arises

The team notices that ready-made answers resolve difficulties faster. It shortens explanations, supplies the next step in advance, and begins assessing quality by the time taken to reach an answer. Users are pleased with the speed, and the number of completed exercises grows.

This version may provide a useful service offering ready-made solutions. But the speed indicator does not answer the original question about independently analyzing a new problem. If the team continues to call it evidence that the previous goal has been achieved, substitution occurs.

The Book makes it possible to expose the discrepancy: the property of “independent transfer” remains in the intent, while the decisions and checks have ceased to express it. Different actions are then possible. The relevant practice and check can be restored. The goal can be changed with the consent of the person who defines it. Two modes can be retained, with the purpose of each identified separately.

### Checking Through Reconstruction

Before execution, a team member restates the task in their own words: “We need to create a class after which a person will independently solve a new problem and explain their reasoning; personal data must not be collected.” This restatement makes their understanding available for comparison.

An alternative restatement, “we need to provide the correct answer as quickly as possible,” reveals the loss of an essential property even before implementation. Correcting understanding saves subsequent work only if the corrected understanding is then preserved in execution.

At the end, the class and the evidence obtained are compared with the agreed understanding. The existence of materials and a correct restatement does not settle the question of how the participant handled the new problem.

### What Could Disprove a Good Result

The participant may have memorized a template, guessed the answer by chance, or received an unnoticed hint. The new problem may have been almost a copy of the one worked through. A check must therefore take into account how the tasks were selected and the conditions under which they were performed.

If the expected transfer is absent, the first step is to establish where the chain diverges: independence has been defined incorrectly, the teaching method is unsuitable, the evidence is insufficient, or the goal itself needs clarification. An elegant description of the chain cannot answer this question in place of observation.

<a id="section-7"></a>
## 6 An Example of a Change in Grounds

Imagine that the workshop chose evening meetings based on information that the room was available after 18. It is then discovered that the room is occupied during that period. This continues the hypothetical example.

The schedule, related agreements, and delivery format are affected. The change does not invalidate the requirement for independent analysis of problems itself. Nor is it necessarily necessary to discard the exercise content: it must be checked whether that content depends on the meeting format.

| Dependent proposition | What happened to its support | Possible next step |
| --- | --- | --- |
| An evening meeting in the selected room | Essential support has fallen away | Do not declare this option confirmed; find an available alternative |
| A specific deadline for enrolling the group | May depend on the available schedule | Check agreements and communicate the change to those affected |
| Independent transfer to a new problem | Does not depend on room occupancy | Retain it as an essential property of the goal |
| No collection of personal financial data | Does not depend on the schedule | Retain the constraint |

If another verified ground supports the previous decision, the decision may remain in place. For example, the meeting could be held in another room whose use has already been authorized. But the feasibility of that option must be established, not assumed for the sake of convenient continuation.

This analysis demonstrates targeted revision. Connectedness is needed to identify what is affected and preserve what is unaffected. Automatically resetting the entire project creates a different error: useful work is lost along with one incorrect premise.

<a id="section-8"></a>
## 7 An Example of Complex Interaction

Consider a hypothetical class registration service. A teacher, an administrator, and a participant act concurrently. Each has their own part of the task: class content, scheduling, and registration. The useful result for the participant is a confirmed place in a suitable class.

A submitted application does not yet mean a confirmed registration. An available teacher does not prove that a room is available. A sent notification does not establish that the recipient received it. These distinctions matter to the whole, even though each local process may appear complete.

The Book maintains the shared meaning and the relationships between the parts. Specialized documents may describe registration and scheduling rules in detail. At the same time, it must be clear which event confirms registration, who is responsible for a conflict, and what the participant is told when something changes.

### The Normal Path and Failure

In the normal case, the time, place, and feasibility of holding the class have been checked; the participant receives confirmation with the conditions. If two applications conflict, the same limited place cannot be promised to both. If the outcome of a notification is unknown, the actual outcome is checked first, before repeating an action that could create duplication.

The check proposed for this example should distinguish at least normal registration, lack of availability, conflicting simultaneous requests, and an unknown confirmation outcome. The detailed design of the checks depends on the implementation and the rights in force.

### What Counts as Completion

For an internal administrative step, completion may mean a processed application. For the original request, it means a confirmed registration or a clear response that no place is available. If the report shows only the internal step, the user may receive the false impression that their task has been resolved.

Checking from the result forces the question back to the recipient: what is now available to this person, which promise has been fulfilled, and what remains open? It does not require describing the entire system anew each time.

<a id="section-9"></a>
## 8 Checking the Concept and Its Implementation

### Contradictions

Two propositions may conflict within the same scope and under the same conditions. For example, a promise not to use personal data contradicts a mandatory requirement to upload an actual account statement. If one proposition applies to a public mode and the other to a separately agreed private service, their scopes must first be established.

Checking meaning precedes mechanical correction of wording. Changing words can hide a contradiction while leaving the conflict between actions intact.

### Completeness Relative to the Task and Stage

For the first class, it is sufficient to describe the necessary chain from intent to observable outcome. A complete enrollment, payment, and support system may lie outside the boundaries of this prototype. However, if the meeting is impossible without confirmed access to a room, that gap is already significant.

It is useful to ask: “Can the selected scenario be followed through to the result without inventing missing rules?” Any addition that proves necessary must be classified as a premise to be checked, a proposal, or an open question.

### Reconstruction

Reconstruction makes understanding available for checking. A participant reproduces the goal, essential properties, constraints, and intended result in their own words. This understanding is then compared with the original intent and available grounds.

Reconstruction can also proceed from the result: judging by what was created, what was considered the main task? If the product rewards the speed of a ready-made answer while the author expected independent reasoning, this discrepancy requires examination.

Two consistent restatements can repeat the same error. Their consistency is therefore useful as an observation about understanding, but insufficient for a conclusion about the reliability of factual propositions.

### Scenarios and Tests

A scenario connects initial conditions, an action, and an expected consequence. A test checks a particular property under specified conditions. Some of these checks can be automated; assessing correspondence in meaning often requires domain-specific examination.

In test-driven development, it is useful to determine in advance which observable result will provide evidence of the required property. But a test written from a misunderstood task can reliably entrench the error. Making understanding explicit and checking the result therefore complement testing.

The following are tasks for checking the approach. They have not been run as a system test and do not have the status of obtained results.

| Case | Expected distinction | What would constitute false success |
| --- | --- | --- |
| The wording retained convenience but lost independence | The loss of an essential property is noticed | All participants restated the substituted goal in the same way |
| An unknown premise is recorded as fact | The need for verification is visible | A source is cited, but its content does not support the statement |
| The grounds for the schedule have fallen away | Related decisions are reconsidered | All project content is discarded without examination |
| An internal step is complete, but the user’s result is absent | The step is distinguished from the original request | A “done” report is based on the existence of an intermediate file |
| A test checks speed instead of independence | The mismatch between measurement and intent is detected | Tests pass, so the goal is declared achieved |
| Two checkers use the same incorrect source | The shared dependency remains visible | Matching answers are declared independent confirmation |

### How to Assess the Usefulness of the Book Itself

For assessment, specific work and observable indicators should be selected in advance: whether the essential intent can be reconstructed, which substitutions are noticed, which are missed, and how many corrections are required. The costs of maintaining materials, reading, checking, and participants’ attention must be taken into account.

Comparison with the usual way of working must retain comparable tasks and conditions. One successful example demonstrates the possibility of useful application in that case. It does not establish an advantage across all projects. Applying the Book to itself also provides material for investigation, while retaining the risk of an error shared by the compiler and the checker.

<a id="section-10"></a>
## 9 Relationship to Other Working Materials

The following comparison explains the roles of materials according to their usual purpose. It is not a comparative product test or proof of the Book’s uniqueness. A particular wiki or requirements system may implement some of the same functions.

| Material or tool | Main role | Which connection matters to the Book |
| --- | --- | --- |
| Technical specification | Describes the agreed result and requirements | Why these requirements express the intent and what change should trigger their reconsideration |
| Wiki and knowledge base | Preserve and connect information | Which propositions are in force, what they are based on, and what they mean for a decision |
| Architecture document | Describes the structure in detail | Which properties of the intent the chosen structure preserves |
| Decision log | Stores chosen options and reasons | How decisions relate to the overall intent and subsequent results |
| Knowledge graph | Represents objects and relationships | Whether the relationships are correct, whether they are significant, and what actually follows from them |
| Plan and task list | Organize execution | How execution changes the situation of the result’s recipient |
| Tests and observations | Check properties and the actual state | Whether the selected properties are sufficient for the original goal |
| Version history | Preserves changes to the representation | What changed in meaning and why the transition was accepted |

The Book can draw on these tools. The choice of storage tool does not by itself determine whether a meaningful connection exists. Conversely, a short text may preserve that connection sufficiently for a limited task.

<a id="section-11"></a>
## 10 How to Begin Without Unnecessary Procedure

Choose one current task in which expectations and results already diverge or are at risk of diverging. Use available documents and verified information rather than gathering the entire project anew.

A short record is sufficient for the first pass:

| Question | What to record |
| --- | --- |
| What needs to be achieved | A useful change for a specific recipient |
| What preserves the meaning | A few essential properties and relevant constraints |
| What the choice is based on | Verified information, separate from assumptions |
| What has been chosen | The decision, its scope, and the grounds for adopting it |
| How to check | An observation capable of distinguishing the intended result from a plausible substitute |
| What remains open | A significant unknown and the next available step |

Ask another participant to reconstruct the understanding from this record. Correct any substitution discovered and carry out the authorized portion of the work. Then compare the result with the agreed understanding. Add to the Book wherever actual work has revealed a missing connection.

Not every task requires a separate document, a new term, or a complete revision of the system. If the available description is sufficient for making and checking a decision, additional formalization should be assessed by its usefulness. Preserved experience must also be applied with due regard for changed conditions.

To develop the Book, it is useful to preserve unsuccessful approaches as well: what problem they attempted to solve, why the method proved insufficient, and what was changed. Such a record helps avoid repetition if its limits are clear and the conditions are checked again.

<a id="section-12"></a>
## 11 Development and Self-Application

This brief authorial retrospective describes the development of the formulations. Dates do not establish scientific priority, the exact birth of the approach, or demonstrated effectiveness.

**Background.** Albert Toma recalls spending about two months trying to understand a complex, disordered project before the Book emerged. The exact beginning remains unknown. He dates the strand of monitoring that develops with a project to December 2025; the exact day is not established.

**Original arrangement.** The Book entered practice as a replacement for the technical specification in its role as the project's main reference. According to the author, the idea and technical implementation were distinguished from the outset wherever possible. Their connection remains essential: implementation results may justify revisiting the idea.

**August 2026.** The selected development strand begins on August 12 with the task of assembling a conceptual whole. By mid-August, protection against drift and simplification without loss of essential meaning are explicit. The requirement to check changes to the Book using its own rules also appears at this stage. Self-application therefore cannot be dated only to September. A requirement to check does not itself establish successful execution of that check.

**September.** On September 11, self-application and recursion are discussed explicitly: the developing approach itself becomes the subject of its description. This is a milestone of recognition rather than an established beginning of self-application. On September 17, the author explains the purpose as counteracting drift of the Idea and names checks for contradictions and completeness as a minimum requirement. The formulation clarifies the original purpose rather than retrospectively creating it.

**October.** The relationships between the overall Book and specialized documents, the representation of relationships as a developing graph, and checking results against an agreed understanding are refined. Attention to transitions between parts increases: individually functioning parts do not guarantee a successful joint result. These propositions are illustrated here through hypothetical examples.

**Edition dated November 1, 2026.** The full account develops the basic article, retains the examples and glossary, and adds a separate discussion of aging and material for initial application. The edition date does not relocate the origin of the concept to publication day.

### What to Retain from This History

The Book developed from a practical need to preserve the whole as details accumulated. Both the project and the Book itself became subjects of review. The history explains the author's path; demonstrating usefulness requires observations in specific tasks, comparison with alternatives, and accounting for costs.


<a id="section-13"></a>
## 12 Limitations and Open Questions

The Book can consistently preserve a mistaken intent. Fidelity to the author's goal therefore does not remove the need to check factual grounds and consequences.

Connections of meaning cannot be reduced to completed fields. A formal structure may be intact while its values are wrong. A successful software check of the structure establishes only the properties that were checked.

Self-checking is vulnerable to shared error. Different participants may rely on a single source, the same assumption, or an example understood in the same way. Separate consideration is useful only insofar as it genuinely changes how errors are detected.

Completeness has to be defined relative to the task and stage. It is impossible to promise that every possible question has been listed. It is possible to show the chosen boundary, significant dependencies, and remaining gaps.

Maintaining the Book has a cost. Excessive records, repeated readings, and formal checks can hinder work. The useful amount is determined by which errors and costs the description helps prevent in a particular case.

The mere presence of a record in the Book does not grant authority, and a formulation alone does not ensure that boundaries are respected. The right to change a goal, perform an action, or allocate a resource requires its own grounds. Compliance with these constraints is checked in the real environment.

Further research needs to address transfer between different participants, resilience through prolonged changes, maintenance costs, and comparison with methods already in use. This report describes the concept and ways to test it while leaving these questions open.

<a id="section-14"></a>
## 13 Self-Application and Revising the Book

If the Book helps preserve a project's intent, its own revisions invite the same question: does the new version preserve its purpose, essential relationships, and necessary constraints? A rule added after one failure may correct that case while complicating all others. A reduction may remove excess detail and also lose a condition of applicability.

Before a significant revision, recover the reason for the change, compare suitable options, and define the result by which improvement will be judged. Afterward, check both the specific correction and the affected whole. A small change can warrant a small check; this does not imply a fixed number of documents or approvals.

Describing the Book within the Book is self-application. It does not create a circular proof of truth: a coherent new version may preserve a shared error. Evidence must distinguish a useful correction from improvement only in an internal measure.

<a id="section-15"></a>
## 14 Aging and Accumulating Errors

Aging is considered here as possible cumulative degradation of state, structure, or relationships. Error accumulation is one possible mechanism. Unlike obsolescence caused by changing external conditions, aging can occur in an unchanged environment.

For example, an exception is repeatedly transferred to new situations without its original condition, a retelling comes to count as verified grounds, and checks adapt to the modified version. Each step may appear acceptable. Together, the changes may impair the original result. This is a possible mechanism, not an established law of all systems.

Time alone, increasing volume, or a single failure does not establish aging. A conclusion requires a sequence of changes, comparable results, and examination of other explanations. Correcting a record does not establish recovery of dependent decisions. It can be useful to compare a local correction, simplification, bounded rollback, and rebuilding the affected area, preserving commitments and checking the result after the change.

<a id="section-16"></a>
## 15 Reuse and the Limits of Transfer

A successful method can be retained with its situation, conditions, action, result, and limitations. In a new task, compare the essential relationships rather than familiar words alone. A changed condition may make the previous solution unsuitable.

The same applies to the Book itself. Success in one project does not establish an advantage in every other project. Compare the full route to a useful result: writing and reading costs, clarification, detected and missed errors, corrections, and maintenance. Additional formality is justified when it helps the task; the number of records is not an independent measure of quality.

<a id="section-17"></a>
## 16 A First Complete Book Example

Consider the workshop in section 5. A small Book could be written as follows.

| Question | Example of a substantive answer |
| --- | --- |
| What is intended, and for whom? | A participant learns to analyze unfamiliar everyday financial problems independently. |
| What must be preserved? | Explanation of the grounds for a solution and transfer to a new comparable problem; real personal financial information is not required. |
| What supports the choice of method? | Gradual hints are proposed as a hypothesis; their benefit has not yet been measured. |
| What has been decided? | An independent attempt comes first, followed by a hint and discussion. A complete answer is available after the attempt. |
| What result is needed? | Solving a new comparable problem without a supplied answer, with an explanation of the reasoning. |
| What remains unknown? | Adequacy of the problems, the effect of hints, participants' initial differences, and the cost of the workshop. |
| What might require revision? | Participants memorize answers without transferring the method; hints replace independent reasoning. |

This is a completed instructional example, not a universal requirements template. Before a real evaluation, define the problems, conditions, and sufficient evidence. After evaluation, record the observed result and its limits. If intent changes, adopt the new decision explicitly; if a factual premise is wrong, reconsider dependent conclusions.


<a id="section-18"></a>
## Appendix A Glossary

| Concept | Meaning in this report |
| --- | --- |
| Idea and intent | The envisioned whole and the meaning of the required change; not merely a list of functions |
| Drift of the Idea | An unnoticed shift in essential meaning during communication, development, or implementation |
| Book | A coherent, evolving representation of intent, its grounds, decisions, and significant relationships |
| Essential property | A property whose loss changes the meaning of the given intent |
| Grounds | Information or propositions on which a particular conclusion or decision rests |
| Assumption | A proposition accepted for consideration whose truth has not yet been established to the required extent |
| Hypothesis | A testable supposition requiring a discriminating test |
| Decision | A chosen direction within a defined scope of authority |
| Unknown | A significant question for which there is not yet a sufficient answer |
| Contradiction | Incompatibility of propositions within the same scope and under the same conditions |
| Completeness | Sufficiency of the description relative to the intent, task, and stage |
| Reconstruction | Reestablishing an understanding of the whole so that it can be presented and checked |
| Derived representation | A requirement, diagram, assignment, or other material expressing part of the intent in its own form |
| Evidence of a result | An observation or material supporting a conclusion about a specific property achieved |
| Revision | Explicit reassessment of a proposition and affected dependencies on new grounds or by an authorized decision |

<a id="section-19"></a>
## Appendix B Questions for Analysis

These questions can be used when reading the concept, analyzing a project, or discussing a change. Choose those relevant to the current task.

1. What useful change is the goal, and who is its recipient?
2. Which properties cannot be lost if the work is still to count as an embodiment of this intent?
3. Where are participants using the same word with different meanings?
4. Which decision looks convincing but rests on an unverified premise?
5. What will change in the conclusion if that premise proves false?
6. Which ordinary scenario and which adverse scenario must be followed through to the result?
7. What evidence will distinguish a result from a completed internal step?
8. What could disprove our conclusion that we are ready?
9. Where do checks share a single common basis?
10. What is now available to the recipient, and what remains open?

<a id="section-20"></a>
## Appendix C Status and Contents of the Edition

Concept: Albert Toma. This full public edition, dated November 1, 2026, develops the basic edition of November 1. The three extended examples, check tables, questions, and fillable outline support explanation and analysis; they are not reports of measured effectiveness.

Completeness here means a coherent account of the Book concept, its application, evaluation, and development. The text does not claim to enumerate every possible situation. Implementing a particular product requires its own documentation and trials. No independent scientific review of this edition is claimed.

[Brief introduction](BOOK-CONCEPT.md) · [Fillable outline](TEMPLATE.md) · [Terms of use](RIGHTS.md)
