# Full AI Car Commercial Tutorial (Every Prompt I Used)

**Video:** https://www.youtube.com/watch?v=GNxmt_4IifA  
**Published:** 2026-08-03  
**Skill page:** https://higgsfield.ai/s/car-commercial-higgsfieldai-agFzmN  
**Cinema Studio link:** https://higgsfield.ai/s/car-commercial-higgsfieldai-ZOtjQX

## Final Result

A complete cinematic AI car commercial built in three stages: assets, setup, generations. Five scenes cover a dealership handoff, a girl stopping a moving car with her hands, a downtown/highway/tunnel drive, a toll checkpoint gag, and a drift-park finale at an airport. Everything generated inside Higgsfield with Soul Cinema / Seedream Pro 5 / Nano Banana Pro for stills and Seedance 2.0 for video. Claude writes the Seedance prompts via a custom skill.

## Skill Installation

1. Open the skill page: https://higgsfield.ai/s/car-commercial-higgsfieldai-agFzmN
2. Download `seedance-prompt-gen.skill` (zip).
3. In Claude: Customize → Skills → Upload the skill file.
4. The skill turns plain-language scene descriptions + attached assets into production-ready Seedance 2.0 prompts.
5. Save every locked asset as a Higgsfield Element with an `@name`. Attach the same image to Claude under that name so the skill can reference it.

## Complete Prompt Library

### Character Sheet — The Champion (hero driver)

```
Three-panel character reference sheet on one seamless canvas, based on the man from the attached photo — reimagined as a Formula 1 driver. Replicate his face 1:1 from the reference photo — exact same facial structure, eyes, eyebrows, nose, lips, skin tone, dark curly hair and silver hoop earrings in both ears — with only one change: he is completely clean-shaven. No mustache, no goatee, no beard — smooth bare skin on the upper lip, chin and jaw. Everything else about the face stays identical to the reference. Calm confident expression. Outfit: professional one-piece fireproof F1 race suit in matte black with white side panels and racing-red accent stripes, high padded collar, front zip, wide waist belt, black racing boots, race gloves tucked into the belt. The suit carries fully fictional made-up branding only: invented team wordmark "APEX GP" across the chest and upper back, invented sponsor patches with fantasy names like "VOLTRA", "KYRO FUEL", "NIMBUS TYRES", "OKTAN" on the sleeves, chest and belt line, plus a fictional race number "27" on the chest. All logos and lettering are original invented designs — no real brands, no real teams, no real sponsors, no existing logos. Panel layout, left to right: LEFT — full-body rear view of the race suit, headless: no head visible above the collar (ghost-mannequin style), showing back wordmark, sponsor placement, belt and boot heels. CENTER — full-body front view of the race suit, headless: no head visible above the collar (ghost-mannequin style), arms relaxed at sides, showing chest wordmark, race number, sponsor patches, belt and boots. RIGHT — tight close-up portrait of his clean-shaven face and shoulders in the suit collar, looking straight into camera, face identical 1:1 to the reference photo. Identical suit, proportions and lighting across all three panels. Clean dark-grey studio background, soft even softbox lighting, subtle contact shadow on floor, thin divider lines between panels. Photoreal, 8K, natural skin texture, organic color, soft contrast. NON-IP, fictional branding only. 16:9.
```

### Scene 1 excerpt — Disguise removal and launch (full reference definitions + technical block + prompt available on skill page)

Reference definitions include `@car_sheet`, `@car_wheel2`, `@loc_pick-up`, `@image_1`, `@char_girl_passenger`, `@hero_secretive_03`, `@hero_03`.

Technical block enforces: Cinematic photoreal. 16:9. 15s. SFX only. Exact seating lock (hero driver, girl rear seat only). Extreme close-up slow-motion for mustache and glasses removal. Accurate lip-sync and natural blinks.

Full prompt (core action):
```
Interior of @car_sheet parked at the curb on @loc_pick-up, in the EXACT position and orientation shown in @image_1 — alone in front of the retro gas station... [full multi-shot sequence with mustache peel in 120fps feel, glasses removal in 240fps feel with lens flare, dialogue "Can we go already?.." and reply "All right. Whatever you say, late girl.."]
```
(Complete version lives on the skill page.)

### Scene 4 Part 2 — The Toll Controllers (full prompt)

```
— REFERENCE DEFINITIONS — 
@controller1: Toll officer, 45-55 years old, average build, warm characterful face, deep smile lines, prominent nose, short dark hair graying at the temples, dark peaked service cap with a badge, gray short-sleeved uniform shirt with red-trimmed epaulettes and chest pockets, black belt, dark gray cargo trousers, black shoes — character appearance only. Reference. 
@controller2: Toll officer, 50-60 years old, Black man, medium build, dignified lined face, short gray-flecked beard and mustache, gray peaked cap with black visor, gray short-sleeved uniform shirt with shoulder patch, black belt — character appearance only. Reference. 
@car_sheet: Modern dark red sports sedan, sleek fastback silhouette, black mesh rims, tinted windows — vehicle appearance only. Reference. 
@newspaper: Classic daily broadsheet newspaper "THE DAILY OBSERVER", slightly worn matte newsprint with soft creases, black masthead, bold fictional headlines, black-and-white photos, columns of unreadable body text — prop reference only, the newspaper held by the second controller. Reference. 
@checkpoint_04_01: Modern highway toll checkpoint on the city outskirts — low dark flat canopies on slim columns sheltering rows of concrete-and-glass booths with service windows, wide lanes curving through the plaza, strips of manicured green grass between the roadways, city skyline with high-rises hazy in the background, bright sunny daylight with soft haze — location and mood reference. Reference. 
— TECHNICAL BLOCK — 
Cinematic photoreal. 16:9. 8s. SFX only, no music. Natural grain, organic color, soft contrast, filmic look. NO CGI. NON-IP. Exactly five shots and four cuts — no more, no fewer, no extra inserts. The first four shots are brief and rapid-fire; the fifth and final shot is the longest, taking roughly half the runtime. Dynamic cinematic editing. English dialogue. Extreme facial micro-expression detail. 
— PROMPT — 
The sequence consists of exactly five shots separated by exactly four cuts — the first four snap by fast, the final shot lingers long.
SHOT 1 (brief) — medium shot of a single toll booth of @checkpoint_04_01 at a three-quarter angle: the booth takes up most of the frame, its service window large and clearly visible — and @controller1 is clearly visible in that window from the very first frame, leaning out of it, head and shoulders out of the booth, wearing his peaked cap, looking out at the road, plainly seen the entire shot; the empty traffic lane runs across the foreground between the booth and the camera — then the red sedan @car_sheet rips through that foreground lane in a split second, moving left to right across the frame, a blurred streak in front of the booth, a violent whip of wind and dust, and the gust tears the peaked cap clean off the head of @controller1 still leaning out of the window, the cap tumbling away in the air, his graying hair ruffling in the blast — the controller stays framed in his window through the whole shot, never leaving the frame. Cut.
SHOT 2 (brief) — close-up of @controller1, bareheaded, leaning out of the service window: his acting natural and restrained, no exaggeration — he turns his head to follow the departing car, eyes tracking it steadily toward the horizon, only slightly widened, brows gently lifted with faint creases on his forehead, lips barely parted — quiet genuine curiosity, a man mildly impressed by what he just saw, nothing theatrical. Cut.
SHOT 3 (very brief) — wide shot from behind the checkpoint @checkpoint_04_01: @car_sheet tearing away down the highway toward the hazy city skyline, shrinking fast, a faint dust trail over the empty lanes — and in the near foreground, on the camera's side, the peaked cap sails through the air and drops, landing on the asphalt with a soft bounce. Cut.
SHOT 4 (brief) — close-up of @controller1 again: he watches the car disappear for a beat, then turns his head toward the booth opposite with a natural, easy motion — his expression balanced and alive: mild surprise still sitting in his gently raised brows and slightly widened eyes, but the stronger note is interest — an attentive, engaged look, eyes focused on his colleague, head tipping forward a touch as he asks, genuinely wanting the answer; no smirk, no smile, mouth neutral, nothing overplayed and nothing flat — the natural animated face of a man who just saw something odd and is honestly curious. He asks in a lively, sincere, interested tone: "Who was that??" Cut.
SHOT 5 (the longest shot, held calmly for roughly half the total runtime, letting the moment breathe) — wide-medium shot of the booth of @controller2 at @checkpoint_04_01, seen from outside through the glass service window, his figure and the booth interior framed comfortably in the shot: he sits exactly as he has been all day, leaned back in his chair, feet up on the desk crossed at the ankles, the open newspaper @newspaper held up in both hands — its front page with the bold masthead facing the camera — utterly calm, heavy relaxed eyelids, the settled stillness of a man for whom nothing in this world is news. His gaze stays on the newspaper as he begins, flat and lazy: "Here we go again" — then a long deliberate pause, stretched well beyond comfort: a slow audible exhale through the nose, an unhurried beat of silence with only the road ambience, the paper @newspaper dipping a few centimeters as he lowers it just enough to look over its edge at @controller1 — and only then, on the second half of the line, his brows lift in a small matter-of-fact arc, eyes steady, the mild raised-brow expression of a man stating the most obvious thing in the world, the faintest veteran's smirk under the gray-flecked beard — "just Adil doing his things." — his brows settle, his eyes drop back to the paper and the newspaper @newspaper rises again to reading position, conversation over, the shot holding on him to the very end of the runtime. SFX only: violent wind whoosh of the passing car left to right, cap fluttering and landing on asphalt, settling dust, road ambience, faint booth interior hum, slow nasal exhale in the pause, newspaper rustle as it dips and rises, calm unhurried voice.
```

Additional full scene prompts (dealership, girl-stops-car, downtown/highway/tunnel, drift-park) are on the skill page. Use the Claude skill to regenerate any scene from a plain-language beat + attached elements.

## Step-by-Step Recreation Playbook

1. Create a new Cinema Studio project. One main folder per scene, subfolder per generation iteration.
2. Generate and lock assets first:
   - Car sheet on neutral grey.
   - Three-panel character sheets (front / rear / face) for every person. Use ghost-mannequin for outfits so only the real face appears.
   - Location stills. Clean plates: remove melted signs, distant cars that will morph.
   - Hand-drawn motion path for any complex trajectory (upload as `@image_1`).
   - Save every asset as a named Higgsfield Element (`@car_sheet`, `@hero_03`, etc.).
3. Load the `seedance-prompt-gen` skill into Claude.
4. For each scene: describe the beat in plain language, attach the required elements, let the skill emit the full reference-definitions + technical-block + shot-by-shot prompt.
5. Generate in Seedance 2.0. Enforce exact shot counts in the technical block. Prefer tight frames. Batch 3–4 takes per scene and stitch the keepers.
6. Iterate by directing: "reduce the smirk", "sweatiness 7/10", "split this prompt".
7. Edit the final cut from the best frames across takes.

## Key Learnings & Replication Notes

- Lock assets before any video generation. Consistency lives in the stills.
- Clean every plate. Anything the model can break will break.
- Exact shot counts in the technical block stop over-generation.
- Tight frames beat wide FPV for traffic and physics.
- Split overloaded prompts. Generate the anchor shot (dialogue or position lock) first.
- Seedance can serve as an image editor: generate a multi-angle static video, screenshot the frames, they match perfectly.
- Short text on props survives; long text dies. Pre-blur small print.
- Continuity is manual. The model does not remember previous scenes.
- Swap the car and characters and the same three-step system produces an ad for any product.

## Raw Links

- Video: https://www.youtube.com/watch?v=GNxmt_4IifA
- Skill + full prompts: https://higgsfield.ai/s/car-commercial-higgsfieldai-agFzmN
- Cinema Studio: https://higgsfield.ai/s/car-commercial-higgsfieldai-ZOtjQX
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
