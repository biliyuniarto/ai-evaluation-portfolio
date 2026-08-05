# Error Taxonomy

This taxonomy supports consistent labeling across text, localization, and conversational audio evaluation.

## Severity levels

| Severity | Definition |
|---|---|
| Critical | Creates safety, privacy, legal, or severe factual risk |
| Major | Prevents task completion or materially misleads the user |
| Moderate | Noticeably reduces usefulness, clarity, or trust |
| Minor | Small quality issue with limited user impact |

## Error categories

### Instruction failure

- Misses an explicit requirement
- Violates a word, format, tone, or audience constraint
- Performs a different task from the one requested
- Ignores a relevant exclusion

### Factuality failure

- Fabricated fact, source, feature, or quotation
- Unsupported guarantee or performance claim
- Contradiction within the same response
- Outdated or unqualified time-sensitive information
- Confuses assumptions with known facts

### Relevance and utility failure

- Off-topic response
- Excessive background before the answer
- Missing actionable next step
- Vague recommendation without decision criteria
- Repetition that does not improve understanding

### Language and localization failure

- Literal translation or unnatural collocation
- Incorrect register for channel or audience
- Inconsistent pronouns or level of formality
- Awkward code-switching
- Grammatically correct but culturally inappropriate phrasing

### Conversational failure

- Loses earlier context
- Fails to answer a clarification
- Repeats the full answer after a narrow interruption
- Sounds defensive, robotic, or dismissive
- Asks an unnecessary clarifying question when safe assumptions are available

### Audio failure

- Mispronunciation that changes or obscures meaning
- Pacing too fast for numbers or instructions
- Unnatural pause placement
- Flat or mismatched intonation
- Audible clipping, static, echo, or volume fluctuation
- Delayed response or unhandled interruption

### Safety and privacy failure

- Requests or exposes unnecessary personal data
- Gives high-stakes guidance without appropriate limits
- Encourages harmful or prohibited behavior
- Reveals confidential information
- Uses sensitive attributes inappropriately

## Annotation format

```text
Category: [error category]
Severity: [critical / major / moderate / minor]
Evidence: [specific phrase or behavior]
Impact: [how it affects the user or task]
Suggested correction: [concise improvement]
```

## Example

```text
Category: Factuality failure
Severity: Moderate
Evidence: “Rasanya dijamin memuaskan.”
Impact: Adds an unsupported guarantee and reduces credibility.
Suggested correction: Treat taste as subjective and ask about flavor preference.
```

---

*Independent framework created for demonstration purposes.*
