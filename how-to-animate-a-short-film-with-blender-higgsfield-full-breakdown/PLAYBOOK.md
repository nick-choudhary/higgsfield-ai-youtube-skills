# How To Animate a Short Film with Blender + Higgsfield (Full Breakdown)

**Video:** https://www.youtube.com/watch?v=reFzEtCG_m8  
**Published:** 2026-09-23  
**Channel:** Higgsfield AI (animator Amina / Higgsfield Animation)  
**Prompts article:** https://higgsfield.ai/s/higgsfield-animation-episode-1-higgsfieldanimation-cyOPRU  
**Article (resolved):** https://higgsfield.ai/@emilywallace/blogs/blender-higgsfield-animation-pipeline-breakdown-animated-short-film  
**Plugin page:** https://higgsfield.ai/plugins/blender  
**Official plugin guide:** https://higgsfield.ai/blog/higgsfield-blender-plugin

First Higgsfield Animation breakdown. Passport Rush teaser: stylized 3D characters in a watercolor world. No `.skill` zip. Do not re-host plugin binaries or image assets.

## Final Result

A consistent film world for the five-minute action comedy *Passport Rush*, built from locked stills plus Blender previs plus Seedance 2.5.

The published teaser work covers:

- Heroine: copper-red hair, dusty steel-blue hoodie, cream headphones worn as a collar, beige-khaki mini skirt, cream knee socks, red canvas sneakers.
- Taxi driver: older Indian man, bald, grey moustache, gold wire glasses, herringbone driver cap, maroon short-sleeve shirt, embroidered jeans, kolhapuri sandals.
- Compact toy-like yellow taxi, plus a wrecked roofless finale version.
- Watercolor S-curve highway location.
- Isolated mushroom-cloud explosion still, later hand-textured to the film look.
- Scene 8: one-take two-wheel squeeze between oncoming trucks.
- Scenes 10–11: 4s double-seatbelt gag with a motion-match cut at 1.5s.
- Framework example: 6s two-shot, cop flung off the hood onto a partner motorcycle.
- Scene 3 experimental: ceiling handles tear out under inertia.
- Team note from the video: 18 scenes in three days. Failed takes, missing details, and weak acting are part of the published process.

## Skill Installation

No downloadable `.skill` file ships with this episode. The published stack is:

| Job | Tool |
|---|---|
| Base stills | SOUL 2.0 |
| Hand correction | Photoshop |
| Roofless taxi edit | Seedream 5.0 Pro |
| Camera / timing / squash | Blender + Higgsfield add-on |
| Video | Seedance 2.5 |

### Higgsfield Blender add-on

1. Open https://higgsfield.ai/plugins/blender and download the signed `.zip`. Leave it zipped.
2. Drag the zip onto an open Blender window. Fallback: Edit → Preferences → Add-ons → Install.
3. Sign in on the floating bar over the viewport.
4. Use the add-on for Scene Builder / Character Animation / Camera / Video. Greybox only. Final look comes from the stills.

Official install write-up: https://higgsfield.ai/blog/higgsfield-blender-plugin

Do not store plugin binaries in this repo.

### Recreate boxes

Every still and video prompt below is also a Recreate button on the companion article. Attach the same numbered `@Image` / `@Video` slots the prompt names. Numbering is local to that prompt. Do not reuse slot numbers across scenes.

## Complete Prompt Library

Source: the Sep 23, 2026 article by @emilywallace. Copy from the Recreate boxes when generating. Do not invent missing cop, motorcycle, composition, interior, or truck sheets. The article says those supporting stills exist as finished references on the page; police / motorcycle / composition keys for the two-shot example are *not* in the published asset set and must be supplied before running that example.

### Asset — The Girl (SOUL 2.0, 3:4, 1080p)

What it does: full-length base design on white. Hand-correct the approved sheet. Keep ginger hair, blue hoodie, and white headphones on every later camera reference or the model drops them.

```
A cute young East Asian woman shown on her own, full-length, standing in a
relaxed three-quarter stance with her face turned to the viewer, on a plain
clean white background, nothing else in the frame, no environment. Her face
is fully visible.
She is slender with long slim bare legs. Her copper-red hair is worn LOOSE —
long and softly straight with a gentle wave, parted in the middle, falling
freely over both shoulders and down past her chest, a few light strands
framing the face. Pale clear skin, delicate features: light grey-blue eyes
with a calm level gaze, fine natural eyebrows, a small neat nose, the
faintest blush and softly closed lips — a quiet, composed expression.
Her outfit, head to toe: an oversized dusty steel-blue zip-up hoodie, worn
unzipped and slouchy, the hood lying back with some of the loose hair
resting over it, white flat drawstrings hanging down, a small red chenille
varsity letter patch on the left chest, ribbed hem and cuffs, the sleeves
pushed into soft scrunched folds at the wrists — both hands tucked into the
front pockets. Under it a plain white cotton long-sleeve tee with a simple
crew neck, its hem falling loose, the white sleeve cuffs just peeking out
of the hoodie's scrunched sleeves. Around her neck, resting on the white
crew neckline and over the fallen hair, a pair of cream wireless over-ear
headphones with soft cushioned ear cups and a padded headband, worn like a
collar. Below the hoodie's long hem a pleated beige-khaki mini skirt just
peeks out. Long bare legs, then loose cream ribbed-knit socks pulled up
over the knees and slouched in soft rolls. Classic red canvas low-top
sneakers with white laces, white rubber soles and toe caps.
Lit softly and evenly, with a faint soft shadow directly beneath her feet —
the background stays pure white.
one cute girl with long loose copper-red hair, full-length view, face fully
visible, oversized blue hoodie over a white long-sleeve tee, headphones
around the neck, pure white background, nothing else in the frame
```

### Asset — The Taxi Driver (SOUL 2.0, 16:9, 1080p)

Three-view sheet. Hand-adjust. Reuse the corrected sheet.

```
Character reference sheet of one older man, three views arranged side by side on a plain flat cream background, evenly spaced, full figures aligned on the same ground line. LEFT — FULL BODY FRONT VIEW: standing straight and relaxed, weight evenly on both feet, feet slightly apart pointing forward, both arms hanging down at his sides, hands open and relaxed, shoulders level, head facing directly at the viewer, calm neutral expression, slight tired droop to the eyes. CENTER — FULL BODY BACK VIEW: exactly the same standing pose seen from directly behind, arms down at the sides, the back of the cap and the bare nape of the neck visible, showing the back construction of the cap, shirt and trousers. RIGHT — LARGE CLOSE-UP PORTRAIT: head, shoulders and upper chest only, cropped large so the face fills most of the panel, slight three-quarter turn of the head toward the viewer, same neutral expression, cap clearly readable, shirt collar visible at the bottom edge. CHARACTER: an older man of Indian origin, roughly 60 years old, medium height, soft heavy build with a rounded belly, sloping shoulders, thick forearms and a short neck. Warm medium-brown skin with visible age: forehead creases, crow's feet at the eye corners, deep nasolabial folds, slight jowls, soft double chin, faint dark circles under the eyes. Broad face with a wide nose, full cheeks, small dark brown eyes. HEAD: completely bald — no hair at all on the scalp, smooth bare skin above and behind the ears, clean shaved head. Eyebrows are thin and grey. Thick bushy grey moustache covering the upper lip, full and wide. Clean-shaven cheeks and chin with faint grey stubble shadow. Round thin gold wire-frame glasses with small circular lenses sitting low on the nose. HEADWEAR: a classic taxi-driver cap — a soft flat cap / newsboy-style driver's cap in dark grey-brown herringbone wool, rounded low crown made of stitched panels, short stiff brim at the front, a small button at the top centre, worn straight and slightly pushed back so the bald forehead shows beneath the brim. CLOTHING: dark brick-red / maroon short-sleeve button-up shirt, plain, worn loose over the belly, collar folded open, tucked in at the waist. Bottom: blue denim jeans with an Indian flavour — straight relaxed cut, mid-blue washed denim, folk embroidery along the outer seams in warm ochre, saffron, magenta and turquoise thread, small mirror-work discs near the pockets, a leather belt with a chunky brass buckle. Simple brown leather open-toe sandals (kolhapuri style) on bare feet. Empty hands, no props. Consistent character design, identical face, bald head, cap, glasses, moustache, clothing colours and body proportions across all three views. Clean neutral background, no scenery, no text, no labels, no arrows.
```

### Asset — The Highway (SOUL 2.0, 16:9, 1080p)

Layout only. Video lighting is locked later.

```
Elevated view from a pedestrian overpass looking down a six-lane urban
highway that does NOT run straight: it enters the frame from the bottom left
in a wide sweeping curve, bends gently to the right through the middle
ground, then straightens only near the horizon — a long, shallow S-curve
receding into the distance. The guardrail, shoulder and the row of tall lamp
posts all follow the same arc rather than a straight line. Wide asphalt
roadway split by a curving central grass median; near carriageway nearly
empty, far carriageway filled with cars, a box truck and a yellow school bus
following the bend. White dashed lane markings, solid yellow line along the
inner edge. Both sides are steep green slopes densely covered with deciduous
trees and shrubs; grassy embankment on the left, a single-track railway on
gravel ballast and electricity pylons behind the trees on the right, curving
away with the valley. Beyond the treetops, a city skyline: a tall residential
tower on a hill at the right, industrial buildings and smokestacks in the
centre, construction cranes, distant towers fading in haze. Pale hazy white
sky, no clouds, soft diffused summer daylight, high horizon line, curving
perspective.
```

### Asset — The Yellow Taxi (SOUL 2.0, 9:16, 1080p)

Three stacked views. Watercolor personality first; a cleaner 3D pass from that design held up better in motion.

```
Vehicle reference sheet of one and the same yellow taxi cab, three views of the identical car stacked vertically in one tall image, each view its own band, plain seamless light background, even soft lighting, soft contact shadow under the car in each view. THE CAR — a small stubby toy-like taxi with exaggerated compact proportions: a very short hood, a tall boxy cabin with a high flat roof, a nearly vertical rear end, thick rounded corners and soft inflated body panels with no sharp creases. Short wheelbase, wide track, oversized chunky black wheels with plain grey steel-look hubs pushed right out to the corners of the body, small wheel arches barely covering them, high ground clearance. Large tall greenhouse: a big upright windshield, wide square side windows with thick pillars, a small quarter window behind the rear door, thin dark window frames. Simple flat front face — a small dark grille slot with a tiny round emblem in the center, two big oval headlights with clear lenses, small square amber turn signals at the outer corners, a plain rounded bumper with a white rectangular license plate reading 8887 in the middle. Rounded pill-shaped side mirrors on short stalks, small oval door handles, a low simple bumper line running around the body. TAXI IDENTITY — uniform bright glossy taxi yellow paint over the whole body, a rectangular taxi light box on the roof center with a black base, orange-red top and a white number panel reading 8B87, a short black antenna behind it, a black circular emblem with a white letter T on both front doors with small dark text lines beside it, a small round badge with an orange accent on the rear door, small side reflectors near the wheel arches, dark tinted rear glass, black interior with a partition and headrests visible through the windows. TOP BAND — front three-quarter view: seen from the front-left at slightly above bumper height, angled about 30 degrees so the short hood and the full left flank are visible. MIDDLE BAND — top-down view: seen from directly overhead, flat plan view, nose pointing left, whole car in frame, showing the wide square roof, the roof light box, antenna, black mirrors sticking out on both sides, hood and tailgate panel gaps, and the T emblems on the doors. BOTTOM BAND — pure side profile: seen exactly from the left at wheel-hub height, no perspective distortion, showing the short overhangs, tall boxy cabin, big wheels at the corners and the roof sign silhouetted above the roof. All three views must show the exact same vehicle with identical proportions, paint, markings, roof sign, plate number and wheels, consistent scale, centered in each band.
```

### Asset — The Roofless Taxi (Seedream 5.0 Pro)

Attach the intact taxi as `<<<image_1>>>`. Keep identity, angle, and environment. Damage must look ripped, not cut.

```
Use <<<image_1>>> as the base concept, preserving the car’s
identity, proportions, color, camera angle, and environment.
Show the car with its roof and upper cabin structure
violently ripped away, leaving the interior exposed.
The damage must look physically believable and chaotic:
jagged torn sheet metal, buckled roof pillars,
twisted window frames, shattered glass remnants,
and irregular fractures around the remaining bodywork.
Vary the damage across both sides.
Leave some structural pieces bent outward and others
crumpled inward, with exposed seams, chipped paint,
and raw metal visible along the torn edges.
Keep the lower body recognizable, with localized dents
and deformation where the upper structure was torn away.
The result should look like a genuinely wrecked car,
not a convertible, a precision cutaway,
or a neatly disassembled vehicle.
Avoid smooth cut lines, symmetrical breaks,
polished edges, and cleanly separated components.
Match the reference’s lighting and visual treatment.
Render convincing material thickness, contact shadows,
and depth inside the exposed cabin.
No people, no added text, no watermarks.
```

### Asset — The Explosion (SOUL 2.0, 3:4, 1080p)

Isolated mushroom cloud on white. Hand-texture after generation to match character style. Use the hand-textured version in Scene 18.

```
A straight-on studio shot depicts a single, massive nuclear mushroom cloud explosion set alone against a pure, solid white backdrop. The fire and smoke assume the iconic atomic blast shape, presenting a dramatic column with a broad upper cap, captured as an isolated object, with no sky, horizon, landscape, or figures in the frame. The cloud structure features a huge bulbous top, resembling a rounded mushroom cap formed by roiling, boiling fire in shades of blazing orange, deep red-orange, and crimson, alive with tumbling billows and laced with dark veins of charcoal smoke. At the core, a white-hot central glow radiates brightly from within the dome. The underside of the cap curls inward in a thick rolled rim, transitioning into a tall, turbulent stem of dense smoke, which glows with its own internal fiery orange at the core that fades to dark brown-grey at the edges. The column twists upward, forming oversized cauliflower-like billows feeding into the cap. At the bottom, the column flares outward, forming a wide, ring-shaped skirt of churning orange-lit smoke clouds—highlighted on their sunward sides and deepened to umber on the shadowed portions. This studio setup is lit softly and evenly from all sides like a high-end product image, with the internal fire glow providing the dominant source of illumination. The fire and smoke are rendered cleanly and crisply, with sharp, well-defined edges for a sense of isolation against the background. A faint, soft studio shadow is visible directly under the base, heightening the sculptural clarity. The color palette features hot oranges, reds, white-hot highlights, fading to brown-gray and umber shadows, all against a flat white background. Captured with a high-resolution camera and deep focus, the immaculate image shows no digital artifacts, noise, or film grain, with crisp rendering throughout, which contributes to a dramatic, cinematic, and hyperreal mood.
```

### Supporting stills (no Recreate text on the article)

Front-seat cabin, rear-seat cabin, delivery truck, log truck. Match each scene’s numbered input map. Same image number does not mean the same asset across prompts.

### Framework — Shared Lighting

Reusable fragment, not a shot request. Warm highlights, cool shadows, one world-fixed key. The published Scene 3 prompt embeds the working copy:

```
Cinematic lighting throughout. Golden hour: a single low-angle warm key light raking across the frame from one side, throwing long, fine, hard-edged shadows across every surface, subject and floor. Shadows run cool, highlights run warm, and the warm/cool contrast is what builds the depth.
— Key plus rim on every beat. Subjects are lit warm on the key side and fall into a cool shadow side, with a visible warm-to-cool transition at the terminator. A distinct rim light separates hair, shoulder lines and top edges from the darker background behind them.
— Volumetric light in the air: soft Tyndall beams as the sun passes through thin cloud, light haze and a gentle bloom, so the light reads as travelling through air rather than just landing on things.
— Glass behaves like glass: specular highlights and reflections skate across it, with restrained lens flare when the low sun clips frame. Anyone behind glass stays clearly visible, softly veiled by the reflection, never hidden.
— Bounce: warm light kicks off the ground and back up into undersides — jawlines, chassis, seat bases. Ambient colour from the surrounding landscape reflects into the scene.
— The light is fixed to the world, not to the subject. It never rotates to follow a face or a body. As subjects move, the lit side, the terminator and the rim travel across them — that travel is the intended effect.
— Light position, angle, colour temperature and quality are constant for the whole shot and identical across every shot in the film. One light source only. No second key, no colour shift, no time-of-day change, no flicker, no strobing, no practical lamps.
```

### Framework Example — Controlled Two-Shot (Seedance 2.5, 16:9, 1080p, 6s)

Needs highway, roofless taxi, Cop 1, Cop 2 + motorcycle, driver, heroine X-belt seating still, Shot 1 composition key, heroine video. Police / motorcycle / composition keys are not in the published asset set. Supply them first.

Full Recreate prompt lives on the article Recreate button and in the article body under “Framework Example — A Controlled Two-Shot Sequence.” Paste that box. Do not reconstruct it from memory.

Hard locks from the published prompt:

- TAXI GEOMETRY LOCK — this example is LHD. Driver front-left, heroine centre-rear in X-harness, Cop 1 on the hood, Cop 2 far down the road lower-right.
- SEAT LOCK — driver and heroine stay seated. Only Cop 1 flies.
- CAMERA RIG LOCK — camera bolted to the taxi. When the car brakes, the camera brakes.
- BRAKE PHYSICS LOCK — bite → ~0.4s inertia skid on locked tires → dead stop with nose-press and one rebound. Cop 1 leaves at bite, not later.
- LAUNCH LOCK — standing to airborne in 2–3 frames. Catapult, not a slide.

Shot 1 (3s): low camera ~25 cm off the asphalt behind the left rear wheel. 84° wide.
Shot 2 (3s) after a hard cut: side-track the motorcycle. Cop 1 enters back-first from frame left and lands back-to-back. 63° normal.
Audio: diegetic only. No music. No readable text.

### Scene 8 — Squeezing Between Two Trucks (Seedance 2.5, 16:9)

Inputs: `@Video 1` Blender motion + sun direction; `@Image 1` taxi; `@Image 2` left truck; `@Image 3` right truck; `@Image 4` lighting still; `@Image 7` driver; `@Image 8` heroine.

This prompt is RHD: steering RIGHT, driver FRONT-RIGHT, girl REAR-LEFT, FRONT-LEFT empty. That seat map is local to Scene 8. Do not mix it with the LHD two-shot example.

What changed in production: pulling the camera back in the previs made the squeeze readable.

Published scene-context header:

```
Scene Context
Create a fast-paced automotive action-comedy sequence in stylized, hand-drawn animation. The atmosphere is playful, snappy, and full of high-speed street-chase energy.
Replace the original video’s yellow taxi with the compact car from @Image 1. Replace its two trucks with the semi-trailer trucks from @Image 2 and @Image 3, respectively.
Rebuild the entire setting as a highway with guardrails, high-rise buildings, grassy slopes, distant mountains, and an open sky. Retain no environmental elements from the original video.
Base the cinematic lighting and atmosphere on @Image 4, with the sun direction strictly aligned with @Video 1.
The sequence is one continuous long take with no cuts. While traveling at high speed, the hero car tips onto two wheels, with only the front and rear wheels of the same side touching the road. It squeezes through the narrow gap between two closely spaced, side-by-side trucks, emerges completely, and lands back on all four wheels.
Follow the camera-movement rhythm of @Video 1 while maintaining a single uninterrupted camera path.
```

The article Recreate box then adds Active References, Seating Layout, Style and Rendering, Twelve Animation Principles, First Frame, Cinematic Lighting, Camera and Continuous Action, Physics, Audio, and Locks. Paste that full box.

Hard constraints from the published lock list:

- One continuous shot. No cuts.
- Trucks approach the camera head-on at the squeeze.
- Occupants stay darkened in the cabin. No face close-ups.
- Action order: anticipation → tilt → squeeze-through → complete clearance → landing → acceleration.
- No music in the generation.

### Scenes 10–11 — The Double Seatbelt (Seedance 2.5, 16:9, 4s)

Inputs: `@Image 1` low-angle target frame; `@Image 2` frontal X-belt end state; `@Image 3` canonical heroine; `@Image 4` rear cabin; `@Image 5` highway.

Continuity fix published on the article: headphones must live in the *target frames*, not only in the character sheet. A conflicting camera still overrides a written costume lock.

Format: Seg 1 = 0.0–1.5s ultra-wide 107° from seat-cushion height. Match cut at 1.5s. Seg 2 = 1.5–4.0s normal 47° dead-level frontal. X-belts land at 2.5s and hold.

Expression lock: she never smiles. Worry only. Mouth level or down.

Paste the article Recreate box for this scene. It includes FIRST FRAME percentages, ACTION TIMING, FACIAL PERFORMANCE, PHYSICS, LIGHTING, AUDIO, POSITIVE LOCKS, and STYLE.

### Scene 18 — The Roof Explosion

Published still: the isolated explosion asset, then hand-textured. The article does not publish a separate Recreate video prompt for Scene 18 in the same Recreate list as Scenes 8 / 10–11 / 3. Do not invent one. Use the hand-textured explosion still plus the roofless taxi sheet and the shared lighting fragment if a later Recreate box appears.

### Scene 3 — Experimental: The Handles Gag (Seedance 2.5, 16:9, ~5s)

Inputs: `@Image 1` girl; `@Image 2` rear cabin with two identical ceiling handles; `@Image 3` highway through glass.

One continuous 5s take. Camera bolted to the cabin, looking rearward. She never pulls the handles on purpose. Inertia tears both mounts. She ends on her back with one torn handle in each fist. Handles keep the exact `@Image 2` design after they rip out.

Paste the article Recreate box. It reprints INPUTS, SCENE CONTEXT, ACTION TIMING, PHYSICS, GOLDEN-HOUR LIGHTING, AUDIO, and POSITIVE LOCKS.

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm a paid Higgsfield account, Blender with the official add-on, SOUL 2.0, Seedream 5.0 Pro, and Seedance 2.5.
2. Send the operator to https://higgsfield.ai/plugins/blender. Do not store binaries here.
3. Generate stills in this order: girl → driver → highway → yellow taxi sheet → roofless taxi from the intact taxi → explosion → cabin interiors and trucks from the article gallery.
4. Hand-correct the girl, driver, and explosion. The article treats those corrected files as the production references.
5. Put headphones, hoodie letter, and other accessories into every camera still, not only the hero sheet.
6. Board the shot. If camera path, vehicle spacing, or squash/stretch matters, block it in Blender as a greybox. Export that blocking as `@Video 1` for the scene that needs it.
7. Open the matching Recreate box on https://higgsfield.ai/@emilywallace/blogs/blender-higgsfield-animation-pipeline-breakdown-animated-short-film.
8. Attach media to the slots that prompt names. Do not carry slot numbers across scenes. Scene 8 is RHD. The two-shot example is LHD. Keep those maps separate.
9. Paste the published prompt unchanged. Generate. Reject takes that drop headphones, swap seats, freeze wheels, invent a convertible roof, add music, or ignore the cut/hold timings.
10. Fix the broken reference, not the whole prompt, when one detail fails.
11. Cut picture in an editor. Add score there. Generated shots are SFX-only.
12. Do not re-host `.blend` files, plugin zips, or image assets.

## Key Learnings & Replication Notes

- Lock designs once. Reuse the hand-corrected sheets.
- Watercolor taxi personality broke in motion. A cleaner 3D pass from the same design survived the chase.
- Previs carries camera, timing, and spacing. Stills carry look. Seedance paints over both.
- Pull the camera back in previs when a gag needs the whole action in frame (Scene 8).
- Written costume locks lose to a camera still that contradicts them. Put the headphones in the target frames.
- Reference numbers are local. Scene 8 RHD vs two-shot LHD is a real trap.
- Animation on twos, twelve principles, and hard locks (seat, camera rig, brake physics, launch) are how this team specifies slapstick.
- Light is world-fixed. Faces move through the key. Do not parent the key to the character.
- Subtle acting is the weak spot the video calls out. Push one facial feature per beat. Keep the face asymmetrical.
- No music in Seedance. Score in the edit.
- Scene 3 is labeled experimental. Treat handle identity as a hard lock or the props morph.
- Police, motorcycle, and some composition keys for the two-shot example are not in the published asset set. Do not fake them.

## Raw Links

- Video: https://www.youtube.com/watch?v=reFzEtCG_m8
- Prompts short link: https://higgsfield.ai/s/higgsfield-animation-episode-1-higgsfieldanimation-cyOPRU
- Companion article: https://higgsfield.ai/@emilywallace/blogs/blender-higgsfield-animation-pipeline-breakdown-animated-short-film
- Plugin page: https://higgsfield.ai/plugins/blender
- Plugin guide: https://higgsfield.ai/blog/higgsfield-blender-plugin
- Higgsfield Animation channel mentioned in the description: https://www.youtube.com/@HiggsfieldAnimation
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
