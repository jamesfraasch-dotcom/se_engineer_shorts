# SE Shorts — Show Bible

Paste this whole file into the SE Shorts Bot at the start of every session (or after any reset).
Keep the master copy here in GitHub so a bot reset never loses it.
Reference images live in `shorts/reference/`.

---

## 1. The character ("Sam the SE" — working name)

Match the brand avatar in `assets/avatar.jpg` exactly. Every clip uses the same reference image.

- Man, mid-to-late 40s, friendly, confident, a little dry
- Short dark hair with gray at the temples, light even stubble
- Black rectangular glasses (the avatar has them — keep them in every clip)
- Black crew-neck t-shirt under a medium-gray sport coat
- Natural off-white teeth; **closed-mouth or small smiles only**, no wide grins
- Proportions: realistic adult proportions, normal-sized head, no bobble-head

## 2. The set

- **He stands at a standing desk.** No chair in frame. (Removes the chair-clipping problem entirely.)
- Single monitor on the desk, angled slightly toward camera; it turns to face the viewer when there's something to show
- White coffee mug with a teal ring, desk nameplate reading "SE" in teal
- Soft-focus office window behind him, cool blue daylight
- Medium shot, waist up, camera at eye level, same framing in all four clips

## 3. Style lock

Clean modern 2D cartoon, flat colors with soft shading, crisp dark outlines, teal (#0E9488) and charcoal palette, 9:16 vertical, 1080x1920.

**Negative prompt (add to every clip):** bright white teeth, wide open-mouth smile, chair, sitting, body clipping through furniture, extra fingers, warped hands, changing outfit, changing hairstyle, missing glasses, text artifacts on screen, 3D render, photorealistic.

## 4. Continuity rules (four 15-second clips)

1. Generate the **full 60-second voiceover first** as one audio file, in one pass, with one voice. Then split it into four ~15s segments. Never generate voice per clip.
2. Clip 1 is generated from the reference image. Clips 2–4 are generated from the **last frame of the previous clip** (image-to-video), so pose, lighting and outfit carry over.
3. Same framing, same set, same time of day in all four.
4. In CapCut: lay the single voiceover track across all four clips, then add captions from the script (burned-in captions — most viewers watch muted).

## 5. Episode structure (60 seconds)

| Clip | Time | Job |
|---|---|---|
| 1 | 0–15s | **Hook (0–3s)** + the problem. One line, on-screen text, no intro. Like/follow ask at ~10s, one short line. |
| 2 | 15–30s | The idea: what it is, in plain words. One example. |
| 3 | 30–45s | The SE move: the exact question or action, quoted. Monitor turns to show it. |
| 4 | 45–60s | Payoff + the AE/SE split in one line + CTA ("Free account research tool, link in bio.") |

Tone: professional, slightly humorous, one joke max. Speak to one SE ("you"), never "you guys".

## 6. Voice

- One voice, one setting, saved as a preset (VoiceStudio or ElevenLabs "voice clone"/saved voice)
- ~150 words per 60s; write scripts at 140–150 words
- Write the script as it should sound: contractions, short sentences, numbers spelled out

## 7. Hooks bank (first 3 seconds)

Use one of these patterns: the deal-loss confession, the contrarian claim, the "you're doing X wrong", the number.

- **Metrics:** "Your demo was perfect. The deal still died. Because nobody wrote down a number."
- **Economic Buyer:** "If you've never met the person who signs, you're not in a deal. You're in a hobby."
- **Decision Criteria:** "Somebody's writing the scorecard for this deal. If it isn't you, it's your competitor."
- **Decision Process:** "'We'll decide next quarter' is not a process. Here's the question that gets you the real one."
- **Paper Process:** "The deal is verbally won. Here's how it still slips three months."
- **Identify Pain:** "No pain, no deal. And 'it's a bit slow' is not pain."
- **Implicate Pain:** "Pain they feel is nice. Pain their boss pays for closes deals."
- **Champion:** "Your champion likes you. That's the problem."
- **Competition:** "The competitor you should worry about is called 'do nothing.'"
- **Demo Crimes:** "Crime number one: the forty-minute tour of the settings page."

## 8. The SE vs AE line (end of every MEDDPICC episode)

Pattern: *"The AE owns [the relationship / the number / the paper]. The SE owns [the proof / the technical win / the risk]. Together you own the [letter]."*

Examples:
- Metrics: "The AE gets the number agreed. The SE proves you can hit it."
- Champion: "The AE builds the relationship. The SE gives the champion the slides they'll present without you."
- Decision Criteria: "The AE learns how they'll decide. The SE makes sure the criteria are ones only you can meet."

## 9. Series calendar

- **MEDDPICC Monday–Wednesday** (one letter per episode, then advanced follow-ups: "Metrics part 2: when the customer has no baseline")
- **Thursday — Demo Crimes** (one crime per episode; this is the shareable, funny series)
- **Friday — Book in 60 seconds** (Pitch Anything, Demonstrating to Win, The Challenger Sale, SPIN Selling; one idea per episode, no quotes from the book, your own words)
- Every 8–10 episodes: a **Deal Autopsy** — a made-up lost deal, and which letter killed it

Batch-produce: script 5 on Sunday, generate during the week, schedule in Buffer.
