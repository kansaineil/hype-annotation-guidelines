---
title: Hype Annotation Guidelines
nav_order: 1
---

# Hype Annotation Guidelines

These guidelines help annotators decide whether an adjective, in a given context, is being used promotionally or not. The following sections provide:  
1. An overview of the general annotation criteria,  
2. Explanations of the criteria, and  
3. Links to adjective-specific guidance.

---

## 1. Overview of annotation criteria {#overview}

| Order | Decision | Type | Effect |
|------:|----------|------|--------|
| **1** | [Value-judgement](#step1) | Gatekeeping | If **NO** → Not hype (stop) |
| **2** | [Hyperbolic](#step2) | Strong override | If **YES** → Hype |
| **3a** | [Gratuitous](#step3a) | Hype-increasing | Adds promotional force |
| **3b** | [Amplified](#step3b) | Hype-increasing | Adds promotional force |
| **3c** | [Broader context](#step3c) | Hype-increasing | Adds promotional force |
| **3d** | [Grounds](#step3d) | Hype-reducing | Counters promotional force |
| **3e** | [Relative / Hedged](#step3e) | Hype-reducing | Counters promotional force |

---

### Decision flow (priority logic)

```text
Value-judgement?
 ├── NO
 └── YES
       │
       ▼
Hyperbolic?
 ├── YES → HYPE
 └── NO
       │
       ▼
Evaluate Step 3 signals:

Hype-increasing:
 3a Gratuitous - YES / NO
 3b Amplified - YES / NO
 3c Broader context - YES / NO

Counter-signals:
 3d Grounds - YES / NO
 3e Relative / Hedged - YES / NO

Final decision:
If hype-increasing > hype-reducing → HYPE
Else → NOT HYPE
``` 

## 2. Explanation of the criteria

Each step below corresponds to the steps in the table above. Follow them in order.

---

<a id="step1"></a>
### Step 1. Value-judgement

**Question:** Does the adjective add a postive value judgement?

**YES → Potentially HYPE** (Most adjectives imply a value judgement)
→ Continue to Step 2.

**NO → Likely NOT HYPE** (Typically, proper nouns, technical/domain-specific and literal meaning)
→ Code as NOT HYPE.

[Back to overview](#overview)

---

<a id="step2"></a>
### Step 2. Hyperbolic

**Question:** Is the adjective hyperbolic?

**YES → HYPE**  
- Relatively closed class (e.g., *revolutionary*, *groundbreaking*, *superb*, *tremendous*)

**NO →** Continue to Step 3a.

[Back to overview](#overview)

---

<a id="step3a"></a>
### Step 3a. Gratuitous

**Question:** Is the adjective gratuitous?

An adjective is gratuitous if it can be deleted without extensive rewriting or the sentence or changing the claim. 

---

**YES → GRATUITOUS**  
- Removal of the adjective (or the  phrase) with minimal local repair leaves the core meaning essentially unchanged.
- Common when the head noun or verb already conveys the same core idea, so the proposition is left intact. Common in **attributive position**, especially with **definite noun phrases** (*the / this / these*), where the adjective mainly adds evaluation.
- Allow for fixing number/determiner mismatch caused by deletion.
- Allow for removal of stranded adverbs/determiners tied to the adjective.
- Allow for removal of whole phrase (e.g. adverbial phrase) if meaning remains essentially unchanged.

**Examples:**  
- *the **dismal** prognosis* → *the prognosis*  
- *this **alarming** trend* → *this trend*  
- *the **vast** literature* → *the literature*
- *an **unmet** need*  → *a need* (*need* already encodes for requirement)
- *an **exciting** prospect* → *a prospect* (determiner mismatch)
- ***very exciting** results* → *results* (removal of stranded adverb)
- *increased **at an alarming rate*** → *increasesd* (removal of adverbial phrase, *increase* alread encodes for change)

---

**NO → NON-GRATUITOUS**  
- The adjective is necessary for the claim  or removing breaks the syntax beyond minimal local repair
- More likely in **predicate position**, **after the verb** or with **indefinite noun phrases** where the adjective adds defining information.
- Sometimes the verb or noun will already encode teh 

**Examples (NOT HYPE):**  
- *Patients showed **a dismal** response to treatment*
- *The prognosis is **dismal***  
- *This trend is **alarming***  


[Back to overview](#overview)

---

<a id="step3b"></a>
### Step 3b. Amplified

**Question:** Is the strength of the adjective amplified?

**YES → HYPE**

| Pattern type | Generic pattern |
|--------------|----------------|
| Adverbial booster | “X is highly / very / extremely / fully / completely [adjective]” |
| Intensifying stance verb | “ Method X ensures|guarantees [adjective] results”|

**NO →** Continue to Step 3c.

[Back to overview](#overview)

---

<a id="step3c"></a>
### Step 3c. Grounds

**Question:** Are grounds (i.e., justifications) given?

**YES → NOT HYPE**

| Pattern type | Generic pattern |
|--------------|----------------|
| Explicit justification | “X is [adjective] because …” |
| Conditional justification | “If …, then X becomes [adjective]” |
| Procedural/evidential justification | “Using method M, X is [adjective]” |
| Contrastive justification | “Unlike previous approaches, X is [adjective]” |
| Reference to assessment | “Analysis shows X is [adjective]” |

**NO →** Continue to Step 3d.

[Back to overview](#overview)

---

<a id="step3d"></a>
### Step 3d. Broader context

**Question:** Are broader context signals present?

**YES → HYPE**  
- Stacking with other hype adjectives (e.g. "a novel, innovative and reliable method)
- Promotional context nearby

**NO →** Continue to Step 3e.

[Back to overview](#overview)

---

<a id="step3e"></a>
### Step 3e. Relative / Hedged

**Question:** Is the framing relative or hedged? Is the use of the adjective limited, qualified, or made conditional rather than presented as universally true?

**YES → NOT HYPE**

| Pattern type | Generic pattern |
|--------------|----------------|
| Comparative | “X is more [adjective] than Y” |
| Negative limitation | “There is a lack of [adjective] methods …” |
| Change framing | “This leads to increasingly [adjective] performance under condition C” |
| Scope restriction | “For specific cases, results are [adjective]” |
| Modal hedging | “The approach may be [adjective]” |

**NO →** Consider cumulative effect of criteria

[Back to overview](#overview)

## 3. Adjective specific guidance

For guidance on specifc adjectives, see the category and adjective pages below.

### Browse by category

- [Importance](Importance/index.md)
- [Novelty](Novelty/index.md)
- [Rigor](Rigor/index.md)
- [Scale](Scale/index.md)
- [Utility](Utility/index.md)
- [Quality](Quality/index.md)
- [Attitude](Attitude/index.md)
- [Problem](Problem/index.md)
