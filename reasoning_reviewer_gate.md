# Reasoning Reviewer Gate

**Projection Reality Model — PRM**  
**A PRM-style mechanism for reviewing reasoning quality before accepting an answer**

## Purpose

The **Reasoning Reviewer Gate** — **RRG** — is a proposed reasoning-quality mechanism inspired by the Projection Reality Model.

Its purpose is not to generate answers directly.  
Its purpose is to evaluate whether a reasoning process is stable, coherent and sufficiently grounded before a final answer is accepted.

RRG treats reasoning as a relational structure. In this view, an answer is not only a final statement, but a projection of relations between assumptions, sources, intermediate steps, concepts and conclusions.

If those relations are weak, hidden, contradictory or unsupported, the final answer may appear convincing while being structurally unstable.

## Basic Idea

A reasoning process can be treated as a chain of relational projections:

1. input or question,
2. available sources or context,
3. assumptions,
4. intermediate reasoning,
5. conclusion,
6. final response.

The role of RRG is to inspect this chain before the response is accepted.

The mechanism asks a basic PRM-style question:

> Is the final answer a stable projection of the available relational structure?

If not, the answer should be corrected, weakened, qualified or sent back for further verification.

## Why PRM Applies to Reasoning

In PRM, reality is approached as a structured field of distinguishable relations.

Reasoning can be viewed in the same way.

A conclusion becomes reliable only when it is properly related to:

- the original question,
- known facts,
- available sources,
- assumptions,
- definitions,
- logical constraints,
- uncertainty,
- missing information.

When these relations are stable, the answer is more trustworthy.  
When they are unstable, the answer may contain projection errors.

## Projection Errors in Reasoning

A **projection error** occurs when an answer presents something as more certain, more complete or more grounded than the underlying relational structure allows.

Examples of projection errors include:

- presenting an assumption as a fact,
- drawing a conclusion not supported by the sources,
- ignoring missing information,
- hiding uncertainty,
- using vague concepts as if they were precise,
- treating analogy as proof,
- producing a confident answer from weak premises.

RRG is intended to detect these errors before the final response is accepted.

## Review Dimensions

A PRM-style Reasoning Reviewer Gate may evaluate several dimensions of reasoning quality.

### 1. Source Grounding

Does the answer follow from the available sources, data or context?

Questions:

- Which claims are directly supported?
- Which claims are inferred?
- Which claims are speculative?
- Are any claims unsupported?

### 2. Logical Continuity

Does the reasoning move coherently from premises to conclusions?

Questions:

- Are there missing steps?
- Are there contradictions?
- Does the conclusion follow from the reasoning?
- Is any causal connection assumed without justification?

### 3. Assumption Visibility

Are hidden assumptions made explicit?

Questions:

- What has been assumed?
- Are the assumptions necessary?
- Are they reasonable?
- Would the conclusion change if an assumption were removed?

### 4. Stability of the Answer

Is the answer stable enough to be accepted?

Questions:

- Is the answer sensitive to missing data?
- Does it depend on uncertain interpretation?
- Should it be qualified?
- Should it be presented as provisional?

### 5. Uncertainty Handling

Does the answer properly express uncertainty?

Questions:

- Is uncertainty clearly stated?
- Are confidence limits visible?
- Is the answer too strong?
- Should alternative interpretations be mentioned?

### 6. Practical Safety

Could the answer cause harm if accepted without review?

Questions:

- Is the topic technical, legal, financial, medical or security-related?
- Could an incorrect answer lead to damage?
- Should the response recommend verification or expert review?
- Should the answer avoid operational instructions beyond the available evidence?

## RRG Decision Types

RRG does not need to produce only a pass/fail result.  
It may return different review outcomes.

### Accept

The answer is sufficiently grounded, coherent and stable.

### Accept with Qualification

The answer is usable, but uncertainty or limitations should be clearly stated.

### Revise

The answer contains weaknesses and should be improved before being accepted.

### Reject

The answer is unsupported, contradictory or misleading.

### Escalate for Verification

The answer depends on information that should be checked externally or reviewed by a human expert.

## Relation to PRM Concepts

RRG maps directly onto several PRM concepts.

### Distinction

The reviewer separates facts, assumptions, inferences, speculation and conclusions.

### Relation

The reviewer checks whether claims are properly connected to evidence and reasoning.

### Projection

The final answer is treated as a projection of the reasoning structure.

### Resistance

A stable answer should resist contradiction, missing steps and unsupported assumptions.

### Change

The review may transform the answer by weakening, correcting or restructuring it.

### Information

The reviewer checks whether distinguishable information has been preserved or distorted.

## Minimal RRG Workflow

A simple RRG workflow may look like this:

1. Identify the final answer.
2. Extract the main claims.
3. Identify sources, assumptions and reasoning steps.
4. Check whether each claim is supported.
5. Detect logical gaps or projection errors.
6. Estimate the stability of the answer.
7. Decide whether to accept, qualify, revise, reject or verify further.

## Example Review Questions

A practical reviewer may ask:

- What is the main conclusion?
- What evidence supports it?
- What assumptions are required?
- What is uncertain?
- What could be wrong?
- Is the answer stronger than the evidence allows?
- Does the response need a warning, limitation or qualification?
- Should the answer be rewritten before being accepted?

## Intended Use

RRG may be useful in:

- AI answer review,
- research assistance,
- document analysis,
- technical troubleshooting,
- legal or formal writing support,
- scientific hypothesis development,
- decision-support systems.

The mechanism is especially useful where an answer may look fluent and convincing but still contain hidden instability.

## What RRG Is Not

RRG is not:

- a complete AI safety system,
- a replacement for expert review,
- a proof engine,
- a truth oracle,
- a guarantee that an answer is correct.

RRG is a conceptual review layer.  
It is designed to make reasoning weaknesses visible before a final response is trusted.

## Project Status

RRG is currently a conceptual extension of the Projection Reality Model.

The next development steps are:

1. define a more precise review checklist,
2. create examples of reviewed answers,
3. test RRG on real reasoning tasks,
4. separate low-risk and high-risk review modes,
5. explore whether RRG can be implemented as a practical AI reviewer workflow.

## Summary

The Reasoning Reviewer Gate is based on a simple principle:

> A final answer should be accepted only when its reasoning structure is stable enough to support it.

In PRM terms, RRG checks whether the final response is a reliable projection of the underlying relational structure.
