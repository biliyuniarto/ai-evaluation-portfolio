# Evaluation Rubric

This rubric is designed for text and conversational AI evaluation. Individual projects may add or remove dimensions depending on the task.

## Scoring scale

| Score | Meaning |
|---:|---|
| 4 | Fully satisfies the criterion; no meaningful issue |
| 3 | Mostly satisfies it; minor issue with limited user impact |
| 2 | Partially satisfies it; noticeable issue reduces quality or usefulness |
| 1 | Largely fails it; major issue substantially harms the response |
| 0 | Does not satisfy it or creates serious risk |

## Dimensions

### 1. Instruction adherence

Checks whether the response follows explicit and implied requirements, including format, length, tone, audience, exclusions, sequence, and requested outcome.

Key question: **Did the assistant do what the user asked, under the stated constraints?**

### 2. Factuality

Checks claims for accuracy, internal consistency, appropriate uncertainty, and unsupported invention. A response should not present assumptions as verified facts.

Key question: **Can the user reasonably trust the claims and qualifications in the response?**

### 3. Utility

Measures whether the response enables the user to understand, decide, or act. Relevant detail is valuable; detail that does not advance the goal is not.

Key question: **Does this response help the user make meaningful progress?**

### 4. Naturalness and localization

Assesses fluency, idiomatic phrasing, tone, pronoun consistency, register, and cultural fit. Grammatical correctness alone is insufficient.

Key question: **Would a native speaker consider this natural for the context and channel?**

### 5. Conversational dynamics

Evaluates directness, context retention, clarification behavior, turn-taking, interruption handling, and unnecessary friction.

Key question: **Does the assistant behave like a responsive conversational partner?**

### 6. Safety and claim control

Checks whether the response avoids harmful guidance, privacy violations, fabricated guarantees, and overconfident advice in sensitive contexts.

Key question: **Does the response manage foreseeable risk proportionately?**

### 7. Audio performance

For voice tasks, assesses pronunciation, intelligibility, intonation, pacing, latency, volume consistency, artifacts, and natural turn boundaries.

Key question: **Is the spoken response easy and comfortable to follow?**

## Pairwise decision rules

1. Score both responses using identical criteria.
2. Distinguish material errors from stylistic preferences.
3. Prioritize failures that affect the user's goal, safety, or trust.
4. Use a tie when differences are negligible or purely subjective.
5. Explain the preference with direct evidence from both responses.
6. Do not list only the winner's strengths; compare equivalent dimensions.

## Rationale template

> Model [A/B] is stronger because [primary evidence-based reason]. Both responses [shared strength or shared weakness]. However, Model A [specific evidence and impact], while Model B [specific evidence and impact]. The preference is mainly driven by [most important dimensions], with [other dimension] being comparable.

---

*Independent framework created for demonstration purposes.*

