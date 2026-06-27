# Usage Scenarios

Use this file to record common situations where one or more concepts are often used together.

The goal is to make knowledge easier to retrieve in context. A concept is more useful when the user knows when to use it, what other concepts it usually works with, and what kind of problem it solves.

## Scenario Template

### Scenario: [Name]

**When this appears**

- 

**Concepts usually used together**

- 

**Core question**

- 

**How to reason through it**

1. 
2. 
3. 

**Common mistakes**

- 

**Useful sentence patterns**

- 

**Example**

- 

**Active-recall prompts**

1. 
2. 

## Scenario Index

### 1. Explaining A Concept That Seems Familiar But Is Not Fluent

**When this appears**

- The user recognizes a term but cannot explain it cleanly.
- The user says "I understand it" but has not yet retrieved or applied it.

**Concepts usually used together**

- Familiarity vs. mastery.
- Active recall.
- Transfer.
- Socratic questioning.

**Core question**

- Can the user explain and use the concept without relying on recognition?

**How to reason through it**

1. Ask the user to explain the concept in their own words.
2. Ask for a new example or application.
3. Diagnose what is correct, missing, or imprecise.
4. Move the concept to the right mastery category in `learning_assets.md`.

**Common mistakes**

- Treating recognition as mastery.
- Giving another full explanation before testing retrieval.
- Moving too quickly to the next topic.

**Active-recall prompts**

1. Explain the concept without looking at the notes.
2. Give a new example where the concept matters.

### 2. Connecting A New Topic To Previous Knowledge

**When this appears**

- A new chapter, lecture, article, or problem introduces a topic that builds on earlier ideas.

**Concepts usually used together**

- Prior concept retrieval.
- Sequence and transition.
- Learning log.
- Concept map.

**Core question**

- Why does this topic appear here, and what earlier idea does it depend on?

**How to reason through it**

1. Identify the new topic's immediate purpose.
2. Retrieve the earlier concept it depends on.
3. Explain the transition from the earlier concept to the new one.
4. Record the connection if it is likely to recur.

**Common mistakes**

- Treating each topic as isolated.
- Listing chapter sections without explaining why they are ordered that way.
- Forgetting the previous concept once the new topic begins.

**Active-recall prompts**

1. What earlier concept does this topic depend on?
2. Why does this topic come next rather than earlier or later?

### 3. Turning A Repeated Task Into A Durable Asset

**When this appears**

- The same kind of analysis, answer, review, or workflow is likely to happen again.

**Concepts usually used together**

- Project compounding.
- Context accumulation.
- Asset accumulation.
- Process automation.
- Decision records.

**Core question**

- What part of this task should be preserved so that next time costs less?

**How to reason through it**

1. Identify repeated context or repeated steps.
2. Decide whether the reusable part belongs in an instruction file, template, script, index, or review asset.
3. Propose the asset if it would reduce future friction.
4. Update the project after user approval.

**Common mistakes**

- Creating too many files for tiny one-off exchanges.
- Letting useful repeated context remain buried in chat history.
- Automating before the workflow is understood.

**Active-recall prompts**

1. What did we do today that we may need again?
2. What file or template would make the next similar task easier?

### 4. Analyzing A Current Event Through A Framework

**When this appears**

- The user asks for commentary on news, markets, policy, technology, or a current event.

**Concepts usually used together**

- Source verification.
- Fact vs. interpretation.
- Framework concepts.
- Transfer.
- Counterintuitive points.

**Core question**

- Which parts are sourced facts, and which parts are interpretation through the chosen framework?

**How to reason through it**

1. Verify the current facts using reliable sources.
2. Select only facts that the framework can meaningfully explain.
3. State the framework concepts being used.
4. Separate sourced facts from interpretation.
5. End with retrieval questions if the goal is learning.

**Common mistakes**

- Summarizing generic news without applying the framework.
- Treating interpretation as if it were sourced fact.
- Using too many concepts instead of the few that actually explain the case.

**Active-recall prompts**

1. What fact changed, and why does the framework care?
2. Which concept does the most explanatory work here?

### 5. Explaining Algorithm Code From A Mathematical Framework

**When this appears**

- The user asks why algorithm code works or why a bug occurs.
- The code implements DP, graph traversal, automata, data structures, counting, optimization, or another mathematical model.
- The user can see the variables but has not yet named the object they represent.

**Concepts usually used together**

- Mathematical object.
- State meaning.
- Invariant or recurrence.
- Contribution formula.
- Code-variable mapping.
- Transfer action.

**Core question**

- What mathematical object is this code trying to represent?

**How to reason through it**

1. Name the object being counted, optimized, represented, or transformed.
2. Write the state meaning, invariant, recurrence, graph relation, or contribution formula.
3. Identify the mismatch between the intended framework and the current code.
4. Map each important code variable to the mathematical object.
5. State the reusable solving action for a similar but not identical problem.

**Common mistakes**

- Explaining line-by-line before defining the state meaning.
- Treating a data-structure implementation detail as the mathematical object itself.
- Fixing the symptom without naming the invariant that was violated.

**Useful sentence patterns**

- "Mathematically, this variable represents X, not Y."
- "The invariant is X; this line breaks it because Y."
- "The reusable action is to first write the state/contribution meaning before modifying code."

**Active-recall prompts**

1. What is the mathematical object behind this piece of code?
2. Which invariant or recurrence would make the code obviously correct?
