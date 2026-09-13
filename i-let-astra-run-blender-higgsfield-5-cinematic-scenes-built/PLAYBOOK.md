# I Let Astra Run Blender + Higgsfield — 5 Cinematic Scenes Built

**Video:** https://www.youtube.com/watch?v=vUYq38wC_xI  
**Published:** 2026-09-12  
**Duration:** 15:36  
**Prompts article:** https://higgsfield.ai/s/blender-higgsfieldai-Viyiew  
**Article (resolved):** https://higgsfield.ai/@adilinthewildtempo/blogs/gpt-astra-6-blender-higgsfield-builds-the-craziest-cinematic-scenes  
**Plugin install (description link):** https://higgsfield.ai/s/blender-higgsfieldai-zHuqyR  
**Plugin page:** https://higgsfield.ai/plugins/blender  
**Official plugin guide:** https://higgsfield.ai/blog/higgsfield-blender-plugin

GPT-6 Astra rebuild of the earlier Claude + Blender credit-saving video (`OiULPvTJ-0E`). Astra builds the blocking, writes the Seedance 2.5 prompt, and runs generation from one chat. No `.skill` zip. Do not re-host the plugin.

## Final Result

Five Seedance 2.5 videos. Greybox or 3D Jutsu locks camera, timing, and staging. Stills lock faces, wardrobe, locations.

1. Infinite loop, 30s, 16:9. A man walks into a walnut study, finds a live miniature of that room with a tiny copy of himself, panics into a wardrobe. Camera cranes out: the room is the miniature on a table one scale up. Last frame matches first frame.
2. Impossible mirror shot, 15s. Camera dollies backward facing a detective and passes through the glass at 5s into a mirrored twin room. Both performances stay in sync. Blockout dressed as a post-apocalyptic shelter.
3. Casino one-take, 30s, blocked in 3D Jutsu. Couple: street, staff door, stairs, corridor, kitchen, table. Color-coded extras. Spoken lines stamped to speaker and timestamp.
4. Desert concert, 30s. One singer, three rings of dancers, cuts already in the Blender blocking. Choreography lives in the generation prompt. Song structure written into the audio block.
5. Vacuum commercial, 30s, one take. Hero is about 10 cm tall. Rug chase, sucked through the hose, dust bin, pullback through clear plastic onto the product. Host face used for the tiny hero.

Plan the camera first. Spend credits after the move is already right.

## Skill Installation

### A. Higgsfield Blender add-on

Blender 4.2–5.1 on the official blog; the plugin page currently says from 5.1. Windows or macOS. Internet. Signed-in Higgsfield account. Generation runs in the cloud.

1. Open https://higgsfield.ai/plugins/blender and download the signed `.zip`. Leave it zipped.
2. Drag the zip onto any open Blender window. Fallback: Edit → Preferences → Add-ons → Install.
3. Sign in on the floating bar over the viewport.
4. Tabs: Scene Builder, 3D Model, Character Animation, Image, Video, Camera, Asset.

Stills: Nano Banana 2, GPT Image, Seedream 5.0 Pro, Z Image. Video: Seedance 2.5. 3D: Meshy 5.

### B. Connect Astra

Spoken setup from 01:40 in the episode:

1. Higgsfield → Plugins → Blender → download.
2. Drag into Blender. Log in. Toolbar appears in the viewport.
3. Open chat → plugins → Higgsfield.
4. Run:

```
@higgsfield /use-blender
```

That is the connection string published on the companion article.

### C. Claude Bridge (optional)

Copy `https://bridge.higgsfield.ai/mcp`. Add a custom connector named Higgsfield Bridge. Test:

```
Build me a calibration bay blockout in Blender
```

### D. 3D Jutsu

Case 3 is blocked in the browser. Pick Astra. No local `.blend` required for that shot.

Do not download or re-host plugin binaries.

## Complete Prompt Library

The companion article publishes the full Seedance generation prompts in Recreate boxes, including a very long Case 3 prompt (speaker ownership, wardrobe locks, annotated-location exclusions). Those boxes are the source of truth. Copy them before you generate. Do not invent missing lines.

What the article, the description, and the spoken brief actually give:

### Shared loop

1. Astra or 3D Jutsu builds a greybox with an editable camera path.
2. Export the blocking video at the shot length (15s or 30s), 16:9.
3. Generate character and location stills through Higgsfield.
4. Attach blocking + stills. Ask Astra to write and run the Seedance 2.5 prompt, or paste the article Recreate box.
5. Video-to-video. Greybox = camera and timing. Stills = look. Ignore placeholder colors on mannequins.

### Case 1 — Infinite Loop

Article assets: `@Image 1` opening/closing frame (empty walnut study + miniature), `@Video 1 · 30s` blocking, `@Image 2` man in olive MA-1 jacket.

Technical lock from the article: photoreal, cinematic, 16:9, 30s, SFX only, no music, single handheld take, droste / mise en abyme, three scales of one room, tiny man is the same performance scaled 1:10, `@Image 1` is first and last frame.

**Spoken block**

```
Build the room, the nested live miniatures, the character action, and an editable camera path with a bit of handheld drift.
```

**Spoken revision**

```
Keep the room and the opening camera move. Replace the ending with a pull back into a larger copy of the room.
```

**Spoken look pass**

```
Take the opening frame from the blocking and send it to Nano Banana as a layout reference. I want an old mansion study.
```

**Spoken generate**

```
Run Seedance 2.5, 30 seconds, 16:9, one continuous shot. Generate two versions.
```

Published generation prompt (article, Case 1 — PROMPT):

```
One room, three scales, one performance. Open on @Image 1 — the walnut-panelled room, the lamp glowing, the miniature on the writing table, the panelled door closed. The handheld camera holds on that door, breathing, following the exact path and timing of @Video 1 · 30s. The door opens and the man from @Image 2 steps in — cautious, off-balance, like he doesn't remember whose home this is. The door closes behind him; in the miniature, the tiny twin door has just closed behind a tiny him. He scans the lamplit room and crosses to the table, drawn to the miniature — and looking down into it he sees this same panelled room again, the same lamp lit in the same corner, and himself in it, leaning in at the exact same instant with the exact same posture. He sidesteps left — the tiny him sidesteps left in the same moment, the same stride. He steps back right — mirrored, frame for frame. He straightens and raises his right hand, fingers spread — the tiny arm rises in perfect unison, and he stares at his own hand like it isn't his. Then he freezes: slow, heavy footsteps approach outside the real door, a shadow shifting in the strip of light beneath it — and in the miniature, a tiny shadow shifts under the tiny door at the same moment. Someone is coming. Panic. He rounds the far side of the table, fast and low across the rug, reaches a tall dark panelled wardrobe against the side wall as its double doors swing open toward him, pulls them, slips backward between hanging coats, and the doors shut over his face — the tiny wardrobe in the miniature swallowing the tiny him in the same beat. And as he vanishes, the camera keeps rising — up and back, over the panelled walls — and the room proves the droste true: it is itself the miniature on the same dark writing table, inside the same walnut room ten times larger, the same lamp glowing at the new scale. The camera eases down and settles into @Image 1 exactly — same closed door, same glowing window, same miniature on the table, same breathing frame, the man gone from view — the last frame landing precisely on the first, an endless zoom-out.

SFX only: low warm room tone, floor lamp hum, heavy door hinge creak, latch click, slow boot steps on wood and rug, nylon jacket rustle, breath catching, slow muffled footsteps approaching behind the door, hurried steps, wardrobe hinges, coat hangers clinking, soft double-door thud, a slow airy whoosh as the room shrinks away, settling lamplit silence.
```

### Case 2 — Impossible Mirror Shot

Article assets: `@Image 3` detective sheet, `@Video 3 · 15s` blocking. Crossing timed to 5s. Paper pinned to the glass at ~9.5s.

**Spoken block**

```
15-second scene. Mirrored copy of the room with both characters moving in sync. The mirror is an opening. It looks like a reflection, but the camera can pass straight through.
```

**Spoken generate**

```
Generate four detective character sheets through Higgsfield. Attach the chosen sheet with the blocking and ask for two 15-second versions, each one continuous take.
```

Published generation prompt opening (article, Case 2 — PROMPT). Copy the rest of the Recreate box if the article added more after this:

```
Post-apocalyptic sci-fi shelter bedroom turned investigation room — lived-in and kept in order, worn but not ruined: bare concrete walls with patched cracks, a worn grey plank floor swept clean, a few salvage crates stacked in the corner, a single cable run along the ceiling, pale ashen daylight through a dusty window with heavy tarp curtains, a neatly made metal-frame bed with an olive military blanket, a sealed metal door with a crossbar in the far wall, and a gunmetal desk covered in case files — scattered typewritten pages, photographs, a folder, a small slate glowing cold cyan. Beside the desk stands @Image 3, rifling through the papers, head bowed, jaw working, tapping a page with two fingers; a swaying pendant work-lamp flickers warm above. Across the room a full-length mirror in a weathered steel frame is set into a dark metal wall covered with dozens of pinned pages, photographs and notes — a sprawling evidence wall; colored sticky notes and pinned pages cling to the glass itself, one empty spot left at eye level. He snatches up a single page, turns on the spot, and strides toward the mirror — quick, driven steps, the robe swinging, eyes locked on the board; his reflection walks toward the glass from the far side in perfect sync. The camera retreats backward ahead of him, matching @Video 3 · 15s exactly, and at the five-second mark it slides backward through the mirror glass into the mirrored twin room — at the instant the lens crosses the plane, a brief subtle glass effect washes over the frame: a soft refraction shimmer, a whisper of chromatic fringe and a faint glint sweeping across the glass, one quick pulse and gone — then the room continues, reversed, and he is now seen through the frame while his true reflection crosses close past the lens in soft defocus. He pulls up short at the board, one taut beat, then slaps the page flat onto the glass in the empty spot — his reflection's palm striking it from the other side at the same instant — presses it down with the heel of his hand, and backs away in brisk uneven steps without turning, eyes never leaving the board, until he stops dead in the middle of the room, suddenly still, taking in the whole picture, jaw set, breathing hard; his reflection backs away in perfect sync on this side.
```

### Case 3 — Casino One-Take (3D Jutsu)

Blocked in the browser. Separate camera and character paths. Color codes on the blocking: black = man, white = woman, yellow = kitchen workers. Article also uses blue = suited staff, orange = other security, green = guests, red = VIPs. Night street. One sign: AUTHORIZED PERSONNEL ONLY, right of the door. Full prompt on the article is long; it assigns every spoken line to a speaker and a timestamp and excludes red-outlined foreground objects from the hall reference.

**Spoken block**

```
One continuous 30-second shot following the couple from the street down the stairs through the corridor and kitchen and into the casino. Separate paths for the camera and the characters.
```

**Spoken revision**

```
Start behind the car's window. The car pulls away when the camera follows the couple inside.
```

**Spoken generate**

```
Send the blocking and all four images to Astra. Build the Seedance 2.5 prompt and generate the shot.
```

### Case 4 — Desert Concert

Blender sequence with cuts already edited: close-ups, wides, overheads, slow dollies, push-ins. Singer center. Three rings of dancers. Boxes mark position and facing only (article: green face = front, red face = back). Choreography goes in the Seedance prompt. Singer sheet from a photo via Astra. Location from Soul Cinema (mirror-field desert, blue hour). Include music and vocal directions in the same request.

**Spoken block**

```
30-second sequence in Blender with the shots already cut together. Close-ups, wide shots, overheads, slow dolly moves, and quick push-ins. Singer at the center, three rings of dancers.
```

**Spoken generate**

```
Generate the sequence with Seedance 2.5 using the blocking, location, and character sheet. Follow the camera moves and cuts, then add the choreography. Include the music and vocal directions in the same request.
```

### Case 5 — Vacuum Commercial

One 30s take. Tiny hero flees across the rug, sucked through the hose, lands in the dust bin, camera pulls back through the clear plastic wall onto the product. Article calls this the wall rule: the transparent compartment wall exists only when the story needs it. Map placeholder colors to real objects.

**Spoken block**

```
Block out a 30-second chase in Blender. Tiny hero flees from a vacuum, gets sucked straight through the hose, and lands inside the dust bin. Then the camera pulls back through the clear plastic wall to reveal the final product.
```

**Spoken assets**

```
Generate references for the hero, the woman, and the vacuum. Woman: striped pajamas and slippers. Vacuum: transparent dust compartment for the final reveal.
```

**Spoken generate**

```
Generate the ad with Seedance 2.5 using the blocking and all the references.
```

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm a paid Higgsfield account, Blender 4.2–5.1 (or 5.1+), and GPT-6 Astra with the Higgsfield plugin. 3D Jutsu covers Case 3 without Blender.
2. Send the operator to https://higgsfield.ai/plugins/blender. Do not store binaries in this repo.
3. Install the add-on. Sign in on the viewport bar.
4. In Astra chat run `@higgsfield /use-blender`.
5. For each case:
   a. Paste the spoken block brief. Ask for an editable camera path and a file backup after every stage.
   b. Review the greybox. Change camera only. Do not dress it.
   c. Export blocking video at 15s or 30s, 16:9.
   d. Generate stills (opening frame / location / character). Host face is valid for the tiny hero in Case 5.
   e. Attach blocking + stills. Paste the article Recreate prompt, or ask Astra to write the Seedance 2.5 prompt from those assets and run two versions.
6. Case 3: 3D Jutsu + Astra. Keep separate camera and character paths. Color-code extras. Send blocking + four stills to Astra.
7. Reject takes that break blockout timing, swap faces, add cuts, or ignore speaker timestamps.
8. Do not re-host `.blend` files, skill binaries, or images.

## Key Learnings & Replication Notes

- Text-only 30-second one-takes fall apart. The blocking file is the structure. Seedance paints over it.
- Astra can own the loop: block, stills, prompt, generate. One chat.
- `/use-blender` is the Astra connection. Claude still uses `https://bridge.higgsfield.ai/mcp`.
- 3D Jutsu is enough when you do not want a local file. Case 3 never leaves the browser until generation.
- Loop shots need a numeric last-frame = first-frame check.
- Mirror trick: the glass is a doorway into a duplicated room. Time the refraction pulse to the crossing (5s here).
- Crowded scenes need color-coded extras and speaker-ownership rules. Camera attention is not who speaks.
- Concert boxes mark position and facing. Write choreography in the prompt or dancers copy the stiff previz.
- Product / vacuum: map placeholder colors to real objects. Hold the transparent wall until the reveal.
- Generate two versions. Pick one. Do not iterate camera inside Seedance.
- Separate pack from the Aug 28 Claude + Blender episode. Do not mix files.

## Raw Links

- Video: https://www.youtube.com/watch?v=vUYq38wC_xI
- Skills & prompts: https://higgsfield.ai/s/blender-higgsfieldai-Viyiew
- Companion article: https://higgsfield.ai/@adilinthewildtempo/blogs/gpt-astra-6-blender-higgsfield-builds-the-craziest-cinematic-scenes
- Plugin short link: https://higgsfield.ai/s/blender-higgsfieldai-zHuqyR
- Plugin page: https://higgsfield.ai/plugins/blender
- Plugin guide: https://higgsfield.ai/blog/higgsfield-blender-plugin
- Bridge MCP: https://bridge.higgsfield.ai/mcp
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
