# Conversational Audio Assessment

## Evaluation goal

Demonstrate a structured comparison of two simulated voice-assistant interactions using equivalent scenarios and the same evaluation dimensions.

## Scenario

The user is calling a voice assistant while cooking and needs a quick substitution for buttermilk. The assistant should give a practical answer, keep spoken instructions easy to follow, and respond naturally when interrupted.

## Interaction A

**User:** Aku lagi bikin pancake, tapi nggak punya buttermilk. Bisa diganti apa?

**Assistant A:** Tentu. Buttermilk adalah produk susu fermentasi yang memiliki tingkat keasaman tertentu. Sebagai substitusi, Anda dapat mencampurkan dua ratus empat puluh mililiter susu dengan satu sendok makan jus lemon dan membiarkannya selama—

**User:** Bentar, susunya berapa?

**Assistant A:** Seperti yang telah saya jelaskan, gunakan dua ratus empat puluh mililiter susu dan satu sendok makan jus lemon. Diamkan selama sepuluh menit sebelum digunakan.

### Observation notes — A

Nada informatif tetapi terlalu formal; intonasi datar pada instruksi utama; pacing agak cepat ketika menyebut angka; respons terhadap interupsi terdengar defensif karena “seperti yang telah saya jelaskan”; utility cukup karena rasio dan waktu tersedia; audio bersih; error utama berupa conversational repair yang kurang natural dan register yang tidak selaras dengan pengguna.

## Interaction B

**User:** Pancake-ku butuh buttermilk, tapi di rumah nggak ada. Penggantinya apa ya?

**Assistant B:** Bisa pakai susu dan perasan lemon. Untuk satu cup buttermilk, campur sekitar dua ratus empat puluh mililiter susu dengan satu sendok makan lemon, lalu diamkan sepuluh menit sampai agak mengental.

**User:** Maaf, berapa banyak susunya tadi?

**Assistant B:** Sekitar dua ratus empat puluh mililiter—kurang lebih satu cup. Campur dengan satu sendok makan lemon.

### Observation notes — B

Nada hangat dan responsif; intonasi memberi penekanan pada jumlah bahan; pacing stabil dengan jeda singkat sebelum angka; interupsi ditangani langsung tanpa mengulang informasi yang tidak diminta; utility tinggi karena ukuran metrik dan cup sama-sama tersedia; audio bersih; tidak ada error material.

## Comparative assessment

| Dimension | Assistant A | Assistant B |
|---|---|---|
| Tone and naturalness | Clear but formal and slightly defensive | Warm, natural, and task-focused |
| Intonation | Limited emphasis | Useful emphasis on quantities |
| Pacing | Fast around numerical details | Stable with helpful pauses |
| Interruption handling | Answers correctly but adds conversational friction | Repairs the conversation directly |
| Utility | Correct ratio and wait time | Same core guidance plus accessible unit conversion |
| Audio quality | Clean, no audible artifacts | Clean, no audible artifacts |
| Instruction adherence | Meets the task, but explanation is less concise | Fully meets the quick spoken-help goal |

## Verdict

**Preferred interaction: Assistant B**

## Comparative rationale

Assistant B provides the stronger spoken interaction because it communicates the same practical substitution with better pacing, clearer emphasis, and more natural turn repair. Both assistants give a usable milk-to-lemon ratio and remain coherent after interruption. However, Assistant A front-loads an unnecessary definition, delivers the quantity too quickly, and responds with “as I explained,” which sounds mildly defensive. Assistant B gives metric and cup measurements, repeats only the requested detail, and maintains a warm conversational tone. Audio clarity is comparable, so the preference is driven primarily by naturalness, utility, and interruption handling rather than sound quality.

## Error cluster summary

| Error cluster | Assistant A | Assistant B |
|---|---:|---:|
| Unnatural or mismatched register | Present | Not observed |
| Poor conversational repair | Present | Not observed |
| Unnecessary verbosity | Mild | Not observed |
| Audio glitch or distortion | Not observed | Not observed |
| Factual inconsistency | Not observed | Not observed |

---

*This is a scenario-based simulated assessment. No real user recording, confidential task audio, or private model output is included.*

