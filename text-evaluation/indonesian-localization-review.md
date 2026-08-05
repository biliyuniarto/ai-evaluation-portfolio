# Indonesian Localization Review

## Evaluation goal

Identify wording that is grammatically understandable but unnatural in everyday Indonesian, then revise it without changing the intended meaning.

## Context

A food-delivery app needs an Indonesian notification for a delayed order. The message should be clear, empathetic, and concise without promising a delivery time that has not been confirmed.

## Source meaning

> Your order is taking longer than expected. The restaurant is still preparing it. We will notify you when the courier is on the way.

## Candidate translation

> Pesanan Anda mengambil waktu lebih lama daripada yang diharapkan. Restoran masih dalam proses mempersiapkannya. Kami akan memberikan notifikasi kepada Anda ketika kurir sedang berada di jalan.

## Review

| Phrase | Issue | Recommended change |
|---|---|---|
| “mengambil waktu lebih lama” | Literal transfer from English; unnatural collocation | “membutuhkan waktu lebih lama” |
| “daripada yang diharapkan” | Correct but stiff for an app notification | “dari perkiraan” |
| “dalam proses mempersiapkannya” | Verb-heavy and bureaucratic | “masih menyiapkan pesananmu” |
| “memberikan notifikasi kepada Anda” | Unnecessarily formal and verbose | “mengabarimu” |
| “sedang berada di jalan” | Ambiguous; may imply the courier is generally on a road | “mulai mengantar” |
| Mixed distance from the user | “Anda” is formal while the product tone appears consumer-friendly | Use one consistent pronoun based on the brand voice |

## Revised version

> Pesananmu membutuhkan waktu lebih lama dari perkiraan. Restoran masih menyiapkannya, dan kami akan mengabarimu saat kurir mulai mengantar.

## Why the revision is stronger

### Meaning preservation

The revision retains all three source facts: there is a delay, the restaurant is still preparing the order, and the user will receive an update when delivery begins. It does not invent a new ETA, reason for delay, refund, or compensation.

### Naturalness

“Membutuhkan waktu lebih lama dari perkiraan” is idiomatic Indonesian. “Masih menyiapkannya” removes unnecessary nominalization, while “mulai mengantar” communicates the courier's status more clearly than the literal “berada di jalan.”

### Tone

The message is direct but not cold. Using “pesananmu” and “mengabarimu” fits a friendly consumer app, provided the same pronoun style is used consistently across the product.

### Concision

The candidate uses 23 words and several formal constructions. The revision communicates the same information in 17 words with lower cognitive load.

## Evaluator note

Localization quality should not be reduced to grammatical correctness. A translation may be technically correct but still feel machine-produced because of literal collocations, excessive nominalization, inconsistent pronouns, or a register that does not fit the product context.

---

*Independent simulated evaluation sample. No confidential client or platform data is included.*

