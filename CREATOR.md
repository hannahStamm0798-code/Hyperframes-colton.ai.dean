# Creator Profile — @laurelksanti

Laurel's identity, positioning, and workflow for video work in this workspace. **Read this before every video task** (alongside `PREFERENCES.md` and `_reference/content-playbook.md`). Use it for on-screen text, niche framing, and workflow assumptions.

## Identity

- **Name on-screen**: @laurelksanti _(no display name chosen yet — use the handle on screen)_
- **Instagram**: @laurelksanti
- **TikTok**: —
- **YouTube**: —
- **X / other**: —
- **Background**: clinical pharmacy, then a master's in Human Nutrition; 20+ years' experience. Lifelong active (swimming, skiing, horse riding, yoga teacher). Her parents' health story is why this work is personal to her.

When putting handles on-screen (lower-thirds, outros, end-cards), use @laurelksanti.

## Offer

- **Hormone Assessment** — a standalone 1:1 virtual consultation ($97, ~45 min). Reviews symptoms, health history, routines and what she's tried; she gives up to 3 personalized nutrition + lifestyle recommendations, clear priorities, guidance on whether testing is worthwhile, and a written summary. No required follow-on purchase.
- **Ongoing 1:1 program** — currently full; waitlist.
- Booking is via the **link in bio** (or a comment/DM keyword when a post calls for it).

## Platform priority

**Instagram Reels first**, cross-posted to TikTok / Shorts as needed. Reels and Stories: **9:16 vertical, 1080×1920, 30fps**. Carousels: **1080×1350 (4:5)**.

- Keep key text out of the bottom ~20% and the right-edge action rail.
- **Leave a gap at the top of reels:** top text starts at ~210px (of 1920), not at the edge.

## Content niche

**Nutrition, hormones & weight loss for women, especially late 30s–50s / perimenopause.** Health education — keep claims accurate and non-sensational, use "may / often / can" where evidence is uncertain, and avoid medical-advice framing. **Laurel checks every health claim before posting.**

- **Calls to action point to Laurel, never "see your doctor"**: link in bio, DM, a comment keyword, save, share, follow.
- **Don't put "Comment X" on every reel** (it limits reach). Rotate on-screen endings: save prompts, share prompts ("Send this to a friend who…"), a plain statement, and only occasionally a comment keyword. Keyword asks can live in the caption instead.
- **Booking asks**: "Book your Hormone Assessment via the link in bio."

## On-camera mix

**On camera, usually silent.** Most footage is real-life b-roll of Laurel (coffee, cooking, walking, gym, bedtime, desk) plus ~60 talking-to-camera clips recorded with a lav mic. Her talking clips are an untapped format (see playbook: "talking Reels").

- Use her b-roll as the background under text; **never put text over her face**.
- Choose stills/frames where her **eyes are open** and she looks warm — avoid bright-sun squinting shots. For calls to action, use **friendly eye contact / a smile**.
- Avoid frames with alcohol (e.g. wine glasses) in hormone content.

## Workflow — division of labor

**Mix — decided per post.** Most posts are built by the assistant from Laurel's footage (text-on-video Reels, carousels, Stories). If Laurel records a talking Reel, it is the source of truth: build captions/graphics on top and never cut her audio or pacing.

## Footage

Laurel's footage lives in a private **iCloud shared album ("Hannah and Laurel Content")**. The link is intentionally **not stored in this repo** (the repo is public) — the user pastes it into the session when needed. Clip numbers shift when the album changes, so identify clips visually, not by number.

- **Don't reuse a clip across reels on the same topic.**
- Some clips are 4:3 — **crop, never stretch**, to fill 9:16 or 4:5.

## Brand identity

Palette (tokens live in `assets/brand-tokens.css`):

| Role | Hex | Use |
|---|---|---|
| Background | `#ebe6e5` | warm off-white boxes / canvas |
| Accent | `#94b4da` | soft blue — shapes, highlights |
| Text | `#001f3f` | navy — headlines + body |
| Emphasis | `#c76d62` | terracotta — key words, labels (large text only) |

Two house styles:
1. **Reels (simple text)** — white bold sans with a navy outline over her footage, on screen the whole time. Her best performer ("Signs your estrogen may be running too high") used this.
2. **Carousels** — navy bold text on `#ebe6e5` rounded line-boxes, italic white quote line at the top with an optional blush (#f6b5aa) second line, white hand-drawn arrow bottom-right, navy "pill" for CTAs. Font: Open Sans 700/800 + 600 italic.
3. **Personal Stories** — plain Instagram-text-tool look (black text on white line-boxes) over a candid clip; never ad-like. Leave room for a poll/question sticker.

No logo file yet.

## Inspiration creators

See [`_reference/creator-library/INDEX.md`](_reference/creator-library/INDEX.md). Laurel's own baseline is `_reference/creator-library/laurelksanti/style-distilled.md`.

## Content playbook

Every idea follows [`_reference/content-playbook.md`](_reference/content-playbook.md): problem-first hooks, rotating formats, a clear purpose per post, and the 30-second talking-Reel structure.

## Project slug convention

**Topic-only, kebab-case.** Reels/Stories: `video-projects/<topic-slug>/`. Carousels: `carousels/<topic-slug>/` (HTML slides rendered to PNG with Playwright).
