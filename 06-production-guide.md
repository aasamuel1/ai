# PRODUCTION GUIDE
## How to turn these scripts into finished AI videos

---

## STEP 1 — Generate Character Reference Images (Consistency Lock)

Before making any video clips, create locked reference images:

1. Open an image tool (Midjourney, Leonardo.ai, Flux, or your video tool's image mode).
2. Generate 4–6 images of each character using the **Master Descriptions** in `02-character-bible.md` (front view, side view, emotional variants).
3. Pick the best one per character and **save it** — this is your reference for every scene.
4. In tools that support character reference (Midjourney `--cref`, Kling "Elements", Pika "Ingredients", Hailuo "Subject Reference"), upload the reference image with every generation.

> ⚠️ Consistency is the #1 challenge in AI video. Always use the same reference image + the same style block for every scene.

---

## STEP 2 — Generate Video Clips

**Recommended tools (any one of these):**

| Tool | Best for | Notes |
|------|----------|-------|
| **Kling AI** | Best overall realism + character elements | 5–10 sec clips, image-to-video |
| **Hailuo (MiniMax)** | Great human emotion & motion | Strong facial acting |
| **Runway Gen-3/4** | Cinematic quality, fast | Good camera control |
| **Pika** | Budget-friendly | Good for stylized looks |
| **Veo (Google)** | High quality with audio | Check regional availability |

**Workflow per scene:**
1. First generate a **still image** of the scene (image tools give more control).
2. Then use **image-to-video** with motion prompts (e.g., "slow push-in", "she walks forward", "he turns his head slowly").
3. Generate 2–3 takes per scene and pick the best.
4. Keep clips 5–8 seconds — shorter clips = fewer AI artifacts.

**Camera motion keywords that work well:** slow push-in, slow pull-back, orbit, handheld, tracking shot, low-angle hero shot, rack focus.

---

## STEP 3 — Voiceover

**Options:**
- **ElevenLabs** (best): Use a deep, warm, aged male voice (e.g., "Daniel," "George," or clone-style aged voice). Paste the narration from each episode script. Set stability ~50%, style ~35% for natural emotion.
- **Free alternative:** TTSMaker, Microsoft Edge Read Aloud (record), or your own voice with a slight slow-down.

**Voice direction:** Slow, deliberate, emotional. Pause after key lines ("…she never told anyone I was her father."). Let the voice crack slightly in Episode 3's final act.

---

## STEP 4 — Music & Sound

- **Music sources (royalty-free):** YouTube Audio Library, Pixabay Music, Epidemic Sound (paid)
- **Music arc per episode:**
  - Ep 1: melancholic piano → hopeful strings (the rise)
  - Ep 2: somber → tension strings (the villain)
  - Ep 3: tension → total silence at the reveal → emotional swell at the hug → warm outro
- **Sound effects:** gate beeps, footsteps, crowd murmur, a single dramatic heartbeat before the revelation.

---

## STEP 5 — Editing

**Recommended editors:** CapCut (free, mobile/desktop — best for vertical video), or DaVinci Resolve (free, pro).

**Edit checklist per episode:**
- [ ] Import clips in scene order; trim each to narration timing
- [ ] Add voiceover track; sync scenes to narration beats
- [ ] Add music at ~20% volume under voice
- [ ] Add subtitles (CapCut auto-captions) — 80% of social viewers watch muted
- [ ] Add text overlays for hooks and CTAs (see episode scripts)
- [ ] Color: slight warm grade for present day, desaturated for flashbacks
- [ ] Export: 1080×1920 (9:16), 30fps, high bitrate

---

## STEP 6 — Publishing Plan

| Day | Action |
|-----|--------|
| Day 1 | Post Episode 1 (Short + Reel + TikTok) |
| Day 2 | Community post teasing Episode 2 |
| Day 3 | Post Episode 2 |
| Day 4 | Tease Episode 3 ("The revelation is coming…") |
| Day 4/5 | Post Episode 3 |
| Day 7 | Post the full combined story as one YouTube long-form video (5–8 min) |

**Optimization tips:**
- First 3 seconds = the hook line + the most dramatic visual. Never start with a logo.
- Pin a comment with the CTA question to seed discussion.
- Reply to early comments in the first hour (algorithm boost).
- Reuse the best 15 seconds (the hug) as a standalone teaser clip.

---

## BUDGET SNAPSHOT (optional)

| Item | Free route | Paid route |
|------|-----------|------------|
| Video clips | Kling/Hailuo free credits | ~$10–30/mo subscription |
| Voiceover | TTSMaker / own voice | ElevenLabs ~$5–22/mo |
| Editing | CapCut free | CapCut Pro / Premiere |
| Music | YouTube Audio Library | Epidemic Sound |
| **Total** | **$0** | **~$15–50/mo** |

---

## QUICK-START CHECKLIST

- [ ] Generate character reference images (Emeka, Amara, Okafor)
- [ ] Generate Episode 1 scenes (9 clips) using prompts in `03-episode-01-script.md`
- [ ] Record ElevenLabs voiceover for Episode 1
- [ ] Edit in CapCut with captions + music
- [ ] Publish Episode 1 → repeat for Episodes 2 & 3
- [ ] Combine series into long-form YouTube video