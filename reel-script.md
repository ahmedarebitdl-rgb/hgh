# REEL SCRIPT — "The Man Who Sold The Eiffel Tower"

**Format:** 5 × 10-second blocks · 0:50 total · Seedance 2.0 std · 1080p · **9:16 vertical** · no subtitles
**Voice:** Arthur (preset, `30fc8796-ceb6-4a66-b3a7-4a145ef7f346`) on all blocks
**Style key job id:** `bfa8ab83-1ad0-4539-b31f-8a8ed163f30f` (attach as `image_references` on every clip)
**STYLE tokens (every prompt):** flat 2D hand-drawn cartoon, thick sketchy black ink outlines, characters with oversized round white heads, small black dot eyes, expressive scribbly mouths, stick-thin black limbs, grungy paper-texture backgrounds in muted color washes, comic chaotic energy, non-photorealistic
**Character — "the Host":** round white head, smug half-grin, rumpled brown suit, crooked tie. Period characters are the same body type with costume variants.
**NEGATIVE (every prompt):** color drift, photorealism, 3D render, live action, lip-sync, captions, on-screen text, letters, watermark
**Clips are silent** (`generate_audio: false`) — narration laid over at assembly, music bed added in the editor.

**Budget:** 5 clips × 90 = 450 + 5 voice takes × 0.8 ≈ 4 → **~454 credits** (+ retry headroom).

**Framing note:** the style key was built 16:9. It still works as an `image_references` anchor at 9:16, but compose every scene for a vertical centre column — single subject, head in the upper third, props stacked rather than spread wide.

---

## Blocks

**Block 1 — HOOK (0:00–0:10)**

NARRATION: In nineteen twenty five, a man sold the Eiffel Tower. Not a replica. Not a painting. The actual Eiffel Tower. To a scrap metal dealer.

SCENE: The Host in his rumpled brown suit stands beside a towering cartoon Eiffel Tower with a blank hanging wooden sale tag, one arm presenting it like a game show prize.

MOTION: slow push-in on the Host, tower sways slightly, sale tag swings.

---

**Block 2 — THE SETUP (0:10–0:20)**

NARRATION: His name was Victor Lustig. He read that Paris found the tower too expensive to maintain. You'd read that and shrug. Victor read it and saw inventory.

SCENE: A pencil-mustached round-head in a dapper coat at a Paris café, newspaper raised, his dot eyes turning into little dollar signs.

MOTION: slow zoom to his face as the dollar-sign eyes pop.

---

**Block 3 — THE METHOD (0:20–0:30)**

NARRATION: So he forged government letterhead, gave himself a fake ministry title, and invited six scrap dealers to a secret hotel meeting. Sealed bids. Very confidential.

SCENE: Lustig stamping ornate fake seals onto papers at a hotel desk; six identical round-head businessmen in bowler hats file in behind him, one pressing a finger to his lips.

MOTION: stamp slams rhythmically, dealers shuffle in single file.

---

**Block 4 — THE GENIUS PART (0:30–0:40)**

NARRATION: Here's the genius part. He didn't pick the highest bidder. He picked the most insecure one. Then asked him for a bribe on top. The guy paid both.

SCENE: A sweating, nervous round-head dealer hands over two money sacks — one huge, one small — while Lustig accepts with a gracious villain smile.

MOTION: push-in on the handshake, comic sweat droplets fly off the dealer.

---

**Block 5 — PUNCHLINE / LOOP POINT (0:40–0:50)**

NARRATION: The victim was too embarrassed to call the police. So one month later, Victor came back to Paris. And sold it again. Source: trust me bro.

SCENE: The embarrassed dealer hides blushing under a desk; behind him the Host stands beside the same Eiffel Tower holding up two fingers, smug half-grin.

MOTION: Host raises the second finger, holds the grin, slow pull-back.

---

## Edit-time notes

- **No CTA block.** The reel ends on "sold it again" so it loops straight back into Block 1's hook — the second viewing reads as the joke landing early. Add a CTA only if this is going out as a trailer for the long-form video.
- **Hook overlay** (added in the editor, never in the generation prompt — on-screen text is in the negative): `HE SOLD IT TWICE` on Block 1, 0:00–0:03, bold all-caps, bottom third.
- **Cuts land on the narration, not the clip boundary.** Trim each clip so the hard cut hits immediately after the last stressed word — "dealer", "inventory", "confidential", "both". Block 5 gets ~0.4s of air after "trust me bro" before the loop.
- **Music:** low grungy bass bed, single hit on the Block 1 push-in and on "sold it again". Duck under narration throughout.
- **Relationship to the long-form.** This is Segment 1 of `video-script.md` compressed to a cold open. If the long-form ships, this reel is the natural teaser — swap Block 5's narration tail to "and he's number one of six" and add an end card.
