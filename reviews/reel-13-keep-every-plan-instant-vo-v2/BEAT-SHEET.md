# Instant VO v2 — Keep Every Plan (ambient + Instant clone)

**Ship:** `/workspace/ehq-reels/reel-13-keep-every-plan-instant-vo-v2-ship.mp4`  
**Voice:** ElevenLabs Instant clone `DBu7tcRyPKsbfQv3t9vl` (LOCKED from Mac voice/.env)  
**Smokes:** `kep-01-walkin-clone.mp3` · `kep-02-bar-clone.mp3`  
**Music:** OUT (Blake picks in IG) · **Ambient bed:** KEPT (pub/room, laughs, clinks)

## Blake feedback addressed
1. Proper speaking recut (not crude full-strip VO replace).
2. Hey-guys: two takes on the **mates-laugh** scene (`motion/mates-3s.mp4`) — **Take A won**.
3. Instant VO layered **over** ducked ambient — not VO-only silence.

## Hey-guys take pick
| Take | Scene | VO delay into mates | Score | Notes |
|------|-------|---------------------|-------|-------|
| **A (WIN)** | mates-3s (mates toasting/laughing) | **0.30s** | 8.55 | Wide-open mouth ~0.25–0.50 + laugh/high-band energy; clearer “Hey” attack |
| B | same mates-3s (repeat candidate) | 0.55s | 6.65 | Later sync; weaker peak; still mates-laugh but less mouth match for line start |

**Why A:** Earlier VO hits the open-mouth smile at the start of mates while mates’ laugh/clink high-band stays audible under/around the line.

## Beat map (timeline)
| Beat | Timeline | Video | Audio |
|------|----------|-------|-------|
| walkin | 0.0–4.0s | walkin-ov (KEEP EVERY PLAN) | Ambient only — Kling dialogue speech-band suppressed; room bed kept |
| **mates (hey-guys)** | **4.0–7.0s** | mates-ov (fortnight / You do) | **Ambient laughs/clinks + Instant VO line 1** @ +0.30s into beat → audible ~4.30–6.2s |
| bar | 7.0–10.0s | bar-ov (Same seats…) | Ambient bed (no dialogue) |
| **order (soda)** | **10.0–14.0s** | order-ov (Different glass) | **Ducked ambient + Instant VO line 2** @ +1.25s into beat → audible ~11.25–12.6s |
| glass | 14.0–18.0s | glass-ov (I don’t drink) | Ambient bed |
| cta | 18.0–21.1s | cta-ov (Follow…) | Ambient bed |
| hold | +0.4s | end hold | Near-silent pad |

## Spoken lines (Instant)
1. **Hey guys — ready for a big night?** → mates-laugh scene (Take A)
2. **Soda with lime, thanks.** → order beat

## Mix notes
- Bed: per-clip ambient extracted from overlay masters; walkin/order get stronger mid speech-band EQ cut (remove Kling words) while lows + highs (room/laughs/clinks) remain.
- Bed level ~0.65–0.70 linear under VO; **sidechaincompress** ducks bed under VO peaks (threshold 0.03, ratio 6–7, attack ~15–20ms, release ~250–280ms).
- VO gain ~1.15–1.20; final `alimiter` 0.95.
- Non-speaking beats keep continuous pub ambience (not silence).
- Music still out.

## QA snapshot
- Duration ~21.3s · 1080×1920 · AAC ~192 kb/s
- Silence (&lt;-45 dB) ~8% (v1 Instant was ~88% VO-only)
- VO peaks visible at mates (~4–6s) and order (~11–13s); ambient between/under lines

## Assemble
`build/r13-keep-every-plan/assemble_instant_vo_v2.sh`
