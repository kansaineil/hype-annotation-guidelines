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
Value-judgement? (Hype-increasing)
 ├── NO
 └── YES
       │
       ▼
Hyperbolic?
 ├── YES → HYPE
 └── NO
       │
       ▼
Evaluate Step 3 additional signals:

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

**Question:** Does the adjective add a postive value judgement? Note that a value judgement does not mean that an adjective is hype.

**YES**   → hype-increasing signal
- Most adjectives in the lexicon imply a value judgement
- If gratuitous, treat automatically as a value judgement
→ Continue to Step 2.

**NO** → Typically, proper nouns, technical/domain-specific and literal meaning
→ Code as NOT HYPE.

[Back to overview](#overview)

---

<a id="step2"></a>
### Step 2. Hyperbolic

**Question:** Is the adjective hyperbolic?

**YES**  → HYPE
- Relatively closed class (e.g., *revolutionary*, *groundbreaking*, *superb*, *tremendous*)

**NO** → Continue to Step 3a.

[Back to overview](#overview)

---

<a id="step3a"></a>
### Step 3a. Gratuitous

**Question:** Is the adjective gratuitous?

An adjective is gratuitous if it can be deleted without extensive rewriting of the sentence and without changing the claim. 

---

**YES**  → hype-increasing signal
- Removal of the adjective (or the  phrase) with minimal local repair leaves the core meaning essentially unchanged.
- Common when the head noun or verb already conveys the same core idea, so the proposition is left intact. Common in **attributive position**, especially with **definite noun phrases** (*the / this / these*), where the adjective mainly adds evaluation.
- Common with shell nouns (abstract “container” nouns like *nature, role, fact, issue, aspect, importance*) where the adjective mainly adds evaluation.
- Allow for fixing number/determiner mismatch caused by deletion.
- Allow for removal of stranded adverbs/determiners tied to the adjective.
- Allow for removal of whole phrase (e.g. adverbial phrase) if meaning remains essentially unchanged.
- Allow deletion of shell-noun frames like *the [ADJ] nature/role/importance/value of X*, reducing to *X* when the core meaning stays the same.

**Examples:**  
- *the **dismal** prognosis* → *the prognosis*  
- *this **alarming** trend* → *this trend*  
- *the **vast** literature* → *the literature*
- *an **unmet** need*  → *a need* (*need* already encodes for requirement)
- *an **exciting** prospect* → *a prospect* (determiner mismatch)
- ***very exciting** results* → *results* (removal of stranded adverb)
- *increased **at an alarming rate*** → *increasesd* (removal of adverbial phrase, *increase* alread encodes for change)
- *This project focuses on **the unique nature of** the occipital artery microvasculature in nodose ganglia and its importance to the regulation of vagal afferent activity and cardiovascular function.* → *This project focuses on the occipital artery microvasculature in nodose ganglia and its importance to the regulation of vagal afferent activity and cardiovascular function.* 

---

**NO**  
- The adjective is necessary for the claim  or removing breaks the syntax beyond minimal local repair
- More likely in **predicate position**, **after the verb** or with **indefinite noun phrases** where the adjective adds defining information.

**Examples:**  
- *Patients showed **a dismal** response to treatment*
- *The prognosis is **dismal***  
- *This trend is **alarming***  


[Back to overview](#overview)

---

<a id="step3b"></a>
### Step 3b. Amplified

**Question:** Is the strength of the adjective amplified?

**YES**  → hype-increasing signal

| Pattern type | Generic pattern |
|--------------|----------------|
| Adverbial booster | X is highly / very / extremely / fully / completely [adjective] |
| Intensifying stance verb | Method X ensures|guarantees [adjective] results|

**NO** 

Continue to Step 3c.

[Back to overview](#overview)

---

<a id="step3c"></a>
### Step 3c. Broader context

**Question:** Are promotional signals present in the broader context?

**YES**  → hype-increasing signal
- Stacking with other hype adjectives (e.g. "a novel, innovative and reliable method)
- Other promotional elements outside the noun phrase.
- See list current list of hype adjectives for candidates, but also include words / phrases that aren't included, but are clearly promotional - e.g *cutting edge, breakthrough, breaking new ground*

<details markdown="1">
<summary><em>current list (as used for intensity sclaing)</em></summary>

- *abundant; accessible; accomplished; accurate; actionable; adaptable; ambitious; ample; appealing; astonishing; attractive; biggest; bleak; brilliant; broad; careful; catastrophic; catastrophic; certified; chief; cohesive; cohessive; collegial; colossal; committed; compelling; complete; complex; comprehensive; concrete; confident; consequential; considerable; constructive; coordinated; correct; countless; creative; credentialed; critical; crucial; cutting-edge; daunting; deadly; decisive; dedicated; deeper; dependable; deployable; desperate; detailed; devastating; dire; disasterous; disciplined; discriminating; dismal; distinguished; disturbing; diverse; dramatic; durable; dynamic; easy; easy-to-use; economical; effective; efficacious; efficient; elegant; elusive; emerging; empirical; energetic; enormous; error-free; essential; established; exact; exacting; excellent; exceptional; exciting; exhaustive; expandable; expansive; experienced; extensible; extensive; extraordinary; far-reaching; fascinating; fastest; fine-grained; first; flawless; flawless; flawless; foremost; formidable; forward-thinking; foundational; fresh; frightening; fruitful; fundamental; game-changing; generalizable; generous; gifted; gigantic; gigantic; gigantic; global; grave; greatest; grim; ground-breaking; high-level; high-performance; high-performing; high-priority; high-yielding; holistic; hopeless; huge; ideal; imaginative; immediate; immense; impactful; imperative; implementable; important; impressive; incomparable; incredible; indispensable; influential; innovative; innumerable; instant; integrated; integrative; intellectual; intense; interesting; international; intimidating; intriguing; intuitive; invaluable; inventive; key; knowledgeable; largest; latest; leading; lively; logical; longstanding; maintainable; major; mammoth; massive; meaningful; methodical; meticulous; minor; minor; miserable; momentous; monumental; motivated; multifarious; myriad; necessary; never-before-seen; newest / new; notable / noteworthy; novel; nuanced; one-of-a-kind; opportune; optimal; organized; original; outstanding; overpowering; overwhelming; painstaking; paradigm-shifting; paramount; paramount; perfect; perilous; phenomenal; phenomenal; pioneering; pivotal; plenty; powerful; practicable; practical; pre-eminent; precise; premier; pressing; prestigious; prime; problematic; problematic; productive; profound; promising; prompt; purposeful; qualified; quality; radical; ready; recent; refined; relevant; relevant; remarkable; renowned; repeatable; reproducible; reputable; revolutionary; rewarding; rich; rigorous; rising; robust; ruinous; safer; scalable; scarce; scientific; seamless; seasoned; self-explanatory; senior; serious; shocking; significant; simple; sizable; skilled; sophisticated; staggering; standard; standard; stark; stellar; straightforward; strategic; streamlined; strict; strong; structured; substantial; subtle; successful; superb; supportive; surprising; sustainable; sweeping; synergistic; systematic; tactical; tailored; talented; tangible; thorough; thrilling; thriving; timely; top; trailblazing; transdisciplinary / interdisciplinary / interprofessional; transferable; transformative; tremendous; troubling; ultimate; unanswered; unequaled; unheard-of; unified; unique; unmet; unoriginal; unoriginal; unparalleled; unprecedented; unrivaled; up-and-coming; up-to-date; urgent; usable; useful; user-friendly; valuable; vast; verifiable; veteran; viable; vibrant; vital; well-timed; wide-ranging; worldwide; worrying*

</details>

**NO** 

Continue to Step 3d.

[Back to overview](#overview)

---

<a id="step3d"></a>
### Step 3d. Grounds

**Question:** Are grounds (i.e., justifications) given?

**YES** → hype-reducing signal

| Pattern type                             | Generic pattern                                                   |
|------------------------------------------|-------------------------------------------------------------------|
| Explicit justification (in-sentence)     | X is [adjective] because / due to … / Y makes X [adjective]       |
| Explicit justification (cross-sentence)  | Thus / therefore / so / hence, X is [adjective] (from prior context) |
| Evidential justification                 | Evidence / data / results show X is [adjective]                  |
| Reference to assessment                  | Analysis / experiments indicate X is [adjective]                 |

**NO** 

Continue to Step 3e.

[Back to overview](#overview)

---

<a id="step3e"></a>
### Step 3e. Relative / Hedged

**Question:** Is the framing relative or hedged? Is the use of the adjective limited, qualified, or made conditional rather than presented as an absolute?

**YES** →  hype-reducing signal

| Pattern type        | Generic pattern                              |
|---------------------|-----------------------------------------------|
| Conditional         | If / when / under conditions C, X is [adj]   |
| Contrastive         | Unlike Y, X is [adj]                         |
| Comparative         | X is more [adj] than Y                       |
| Negation            | Not [adj] / lack of [adj]                    |
| Scope restriction   | In some cases / for specific tasks           |
| Modal hedging       | May / might / could be [adj]                 |
| Possibility framing | It is possible that X is [adj] / potentially [adj] |

All serve to bound the claim and make it less absolute.

**NO**

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
