# Equalizer Pepe — EP. 01 "NO TIME TO SIP" (pilot)

**Format:** 30.0s · 9:16 · 1080×1920 · 30fps · review only (never posted by agents)
**Show:** Equalizer Pepe (@Equalizer0x · Sonic · $EQUAL · equalizer.exchange)

**Logline:** Equalizer Pepe's wine is one millimetre from his lips when the Scales tip: Maxxx the 100x gecko is about to get liquidated off Liquidation Cliffs. "Hold my wine." Roadster, warp tunnel, one-handed catch over the red abyss — balance restored. Maxxx immediately asks about 125x. Pepe gets home, reaches for his glass… it's gone. A caped silhouette raises it from the Epoch Clock Tower. EP. 02: THE WINE THIEF.

**Why this pilot:** merges the bible's pilot ("The Sip": rescue Maxxx, he instantly re-levers) with the original "NO TIME TO SIP" spine (Hold my wine → wine stolen → EP.02 The Wine Thief). Character first, product last: Equalizer shows up only as the pin, the car badge, the HQ sign, the watermark and the end card. No prices, APRs, TVL or promises.

**Loop:** the stinger (S16) pushes in on Pepe raising a *new* glass and lands on exactly the opening frame of S01, so the replay starts with the same sip → DING.

## Beat sheet / shot list (timecodes in final cut)

| # | In–Out | Shot (set · outfit) | Action / camera | Method | On-screen text (PIL, Bebas) | SFX |
|---|---|---|---|---|---|---|
| S01 | 0.00–1.50 | HOOK · Scale Room · tux | Close-up: wine glass at his smug lips. Slow push-in. Red alarm flash on the DING at 1.15s. | still + push | HE HAS NEVER FINISHED THIS SIP | lounge hum → DING + alarm |
| S02 | 1.50–3.00 | Scale Room · tux | Glass frozen at lips, eyes slide sideways; giant cyan scale behind him tips hard, red alarm light. | Kling i2v | ALERT: THE SCALES ARE TIPPING | alarm whoop |
| S03 | 3.00–4.70 | Liquidation Cliffs · Maxxx | Maxxx the gecko (sweatband) teeters on the ledge staring at his phone; leverage gauge needle in the red. | Kling i2v | MAXXX. 100x LONG. AGAIN. | gauge ticking |
| S04 | 4.70–6.40 | Scale Room · tux | No-look: sets the glass down on the bar, straightens the blue bow tie, smug. | Kling i2v | HOLD MY WINE. | glass tink |
| S05 | 6.40–8.20 | HQ rooftop pad · tux + roadster | Roadster launches off the pad, white compressed-air thruster bursts. | Kling i2v | — | thruster whoosh |
| S06 | 8.20–10.00 | Sonic Warp Tunnel · roadster | Roadster screams toward camera through the rings, Pepe one-handed, hair streaming. | Kling i2v | SONIC SPEED | big whoosh |
| S07 | 10.00–11.60 | Liquidation Cliffs · Maxxx | Ledge cracks; Maxxx slips backward toward the red abyss. | Kling i2v | LIQUIDATION IN 3… 2… | crack + scream sting |
| S08 | 11.60–13.80 | Cliffs · tux + roadster | Roadster swoops over the abyss; Pepe leans out and grabs Maxxx's wrist one-handed. | Kling i2v | NOT TODAY, SER. | impact |
| S09 | 13.80–16.00 | Cliffs ledge · roadster side | Roadster hovers by the ledge, door badge to camera (real icon.png), Pepe smug, Maxxx rescued in passenger seat. | still + push, logo comp | BALANCE RESTORED. | ding-chord |
| S10 | 16.00–17.30 | close · Maxxx | Maxxx grinning, phone up. | still + punch | …OK BUT WHAT ABOUT 125x? | phone blip |
| S11 | 17.30–18.60 | close · tux | Pepe's dead-eyed unimpressed stare. | still | — | silence beat |
| S12 | 18.60–20.60 | Scale Room · tux | Back at HQ, reaches to the bar without looking… grabs air; the spot is empty. | Kling i2v | BACK BEFORE THE WINE BREATHES… | swipe, drip |
| S13 | 20.60–22.00 | close · tux | Eyes wide, mouth open — the glass is GONE. Camera shake. | still + shake | WHO TOOK MY WINE? | sting |
| S14 | 22.00–24.50 | Epoch Clock Tower | Caped silhouette on the tower ledge raises Pepe's glass against the clock. Push-in. | Kling i2v | EP. 02 — THE WINE THIEF | clock tick + low hit |
| S15 | 24.50–27.50 | End card (navy #0A1633) | logo-01-white-text + JOIN THE DISCORD · SUBSCRIBE + EP. 02 tease. | PIL | EQUALIZER PEPE / EP. 02 — THE WINE THIEF / JOIN THE DISCORD · SUBSCRIBE | tick-tock |
| S16 | 27.50–30.00 | Scale Room · tux | Stinger: Pepe raises a fresh glass to his lips; push-in lands exactly on S01's first frame → loop. | still + push | …FINE. NEW GLASS. | lounge hum (loop seam) |

Pace: 16 shots in 30s (avg 1.9s; action stretch 1.3–2.2s). Hook text on frame 1. Watermark (real icon.png, keyed) top-left below the 250px UI band on every frame except the end card (which carries the full lockup).

## Facts guardrail
No prices, APRs, TVL, volumes, rankings, promises or buy calls. "100x / 125x" refer to the fictional gecko's leverage (character gag, not advice). Archetypes only, no real people.

## Plate prompts (GenerateImage, refs = master sheet(s) + set plate + icon.png [+ roadster sheet / Maxxx sheet])
See `plates/PROMPTS.md`.

## Production log (as built, 22 Oct 2026 AEDT)
- **Maxxx** (new recurring gecko) designed this episode: `plates/maxxx-sheet.jpg` (bald orange-yellow gecko, red sweatband, white tank, blue shorts). v1 had Pepe-style curly hair and was rejected to keep silhouettes distinct.
- **Plates:** 13 start frames via GenerateImage with refs (master-tux / master-expressions / roadster-sheet-logo / Maxxx sheet / final set plates / icon.png): `plates/sXX-*.jpg` (720×1280) → `plates/sXX-*-1080.jpg` (1080×1920 + real icon.png composited over every AI pin/badge/door decal and the HQ wall badge, `build/prep.py`).
- **Kling 2.6 Pro i2v (5s, 9:16, no audio):** S02, S03, S04, S05, S06, S07, S08, S12, S14 — 9 jobs × 0.156 USDC. Raw clips `clips/raw_sXX.mp4`, log `build/gen.log`.
- **Trims used (raw in-point → speed):** S02 0.1s ×1.0 (stops before the red alarm washes over the wall logo) · S03 0.3 ×1.0 · S04 0.2 ×1.3 · S05 0.4 ×1.4 · S06 0.3 ×1.0 + push 1.0→1.28 · S07 0.5 ×1.7 · S08 0.0 ×1.35 · S12 0.3 ×1.2 · S14 0.2 ×1.0 + push 1.0→1.55. All end before the last-0.7s blob zone.
- **Stills with camera moves (no Kling):** S01, S09, S10, S11, S13 (shake), S16 (loop push that lands on S01's first frame).
- **Edit:** `build/edit.py` + `build/cut.json` (PIL per-frame compositor → ffmpeg). Captions Bebas Neue, eyebrow Inter, watermark = keyed icon.png 92px at (48,260) on every frame except the end card. End card = `brand_overlay.end_card` (logo-01-white-text on #0A1633).
- **Sound:** fully synthesized in numpy (`build/audio.py`, no samples, no music licences): lounge e-piano bed (open + loop seam), signature bell DING, alarm, 140bpm kick/snare/hat/bass action bed, whooshes, thruster puffs, rock crack, impact boom, "balance restored" chime arpeggio, phone blips, clock tick-tock + end-card DING. Loudness-normalised to about −15 LUFS.
- **Spend:** balance before 11.484154 → after 10.080154 USDC = **1.404 USDC** (cap 3.00). GenerateImage plates: free.
