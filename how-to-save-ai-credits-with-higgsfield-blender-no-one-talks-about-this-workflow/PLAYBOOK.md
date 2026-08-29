# How To Save AI Credits With Higgsfield + Blender (No One Talks About This Workflow)

**Video:** https://www.youtube.com/watch?v=OiULPvTJ-0E  
**Published:** 2026-08-28  
**Duration:** 19:48  
**Prompts article:** https://higgsfield.ai/s/blender-plugin-higgsfieldai-lpdrbq  
**Article (resolved):** https://higgsfield.ai/@adilinthewild/blogs/this-blender-higgsfield-ai-workflow-changes-how-you-make-ai-video  
**Plugin install:** https://higgsfield.ai/s/blender-plugin-higgsfieldai-CFXDqV  
**Plugin page:** https://higgsfield.ai/plugins/blender  
**Official plugin guide:** https://higgsfield.ai/blog/higgsfield-blender-plugin

## Final Result

Five Seedance 2.5 videos, each driven by a Blender blockout instead of a text-only roll of the dice:

1. A 30-second one-take fight through a torii tunnel. Six attackers, six timed falls, camera never cuts.
2. A 30-second diner dialogue. Six people around one table, four cuts, nobody swaps seats.
3. A 30-second continuous camera-move reel. Three orbits, three vertical floor rises, one robo-arm rooftop lock.
4. A 30-second hypermotion soda ad. 13 scenes. Can is a cylinder, ice is cubes, fruit is spheres. Two black gaps left for liquid sim.
5. A 19-shot / 30-second car commercial. One blocked edit, then four style passes: photoreal night chase, painted 2.5D getaway, two-color manga, toybox western.

The point of the video: lock camera, cuts, and timing in 3D first. Spend credits only after the move is already right. Greybox carries motion. Reference sheets carry look. Same blocking file can be re-skinned.

## Skill Installation

There is no `.skill` zip in this episode. The "skill" is the official Higgsfield Blender add-on plus the Higgsfield Bridge MCP connector that lets Claude build inside the open `.blend`.

### A. Blender add-on

Requirements: Blender 4.2–5.1 on Windows or macOS. Internet. A signed-in Higgsfield account. Generation runs in the cloud; a strong GPU is only needed for local Cycles/EEVEE.

1. Open https://higgsfield.ai/plugins/blender and download the signed `.zip`. Leave it zipped.
2. Drag the zip onto any open Blender window. It installs and enables itself. Fallback: Edit → Preferences → Add-ons → Install.
3. Sign in on the floating Higgsfield bar over the 3D viewport.
4. Tabs on the bar: Scene Builder, 3D Model, Character Animation, Image, Video, Camera, Asset.

Models available from the bar (per official FAQ): Nano Banana 2, GPT Image, Seedream 5.0 Pro, Z Image for stills; Seedance 2.5 for video; Meshy 5 for 3D; plus the catalogue dropdown and upscalers.

### B. Higgsfield Bridge (Claude talks to the open scene)

This is not the generic Higgsfield MCP (`https://mcp.higgsfield.ai/mcp`). The Bridge talks to the add-on in the file you already have open.

1. Copy `https://bridge.higgsfield.ai/mcp`
2. In Claude: Settings → Connectors → Add custom connector.
3. Name it **Higgsfield Bridge**. Paste the URL.
4. Sign in when prompted.
5. Test with the official first prompt:

```
Build me a calibration bay blockout in Blender
```

Video setup notes from the episode (00:49): use Claude Cowork, set Fable 5 to high, then work through the Bridge. After login the Higgsfield toolbar sits in the viewport. You can drop assets, build meshes, or generate a full scene from that bar.

Do not download or re-host the plugin binary. Get it from Higgsfield.

## Complete Prompt Library

Full Seedance generation prompts for all five use cases live in copy boxes on the prompts article. Those widgets did not expose their bodies as plain HTML, so they are not invented here. Open the article and copy each box before you generate.

What *is* published in the article, the video description, and the spoken brief:

### Loop used on every case

1. Claude + Bridge builds or edits the greybox in the open Blender file.
2. Render the blockout (video used 1920×1080, 24 fps, duration matched to the shot — usually 30s).
3. Attach the blockout clip + character/location stills.
4. Ask Claude for a second-by-second Seedance 2.5 prompt that follows the clip.
5. Generate video-to-video in Seedance 2.5. Greybox = camera and timing. References = wardrobe, faces, set dress.

Master files are promised as free downloads on the article. Grab them from the page; do not re-host binaries.

### Claude blocking briefs (spoken / written)

**One-take fight — scene build**

```
Connect to Blender through Higgsfield Bridge and build a 30-second previz in a single shot: a corridor with textured walls, a box-person walks down it. Bring the camera alive — different framings, and animate the lens: it moves continuously on its own route, with accelerations and accents on the pauses. Everything smooth, no cuts, the hero always in frame. Save a backup copy of the file after every stage.
```

Spoken follow-ups from the video:

```
Now, make it more interesting, add texture to the walls, use different framings, and animate the lens.
```

**One-take fight — prompt request after the blockout render exists**

```
Write a 30-second Seedance prompt based on this video blocking. Read the input video and write out the prompt second by second to match the camera moves in the clip.
```

Article label for the finished generation prompt: **Torii Tunnel One-Take**. What it does (article): video-to-video over the blocking render. Previz drives the camera path 1:1. References dress the world — six attackers, six timed falls, one continuous take.

**Dialogue scene — first blockout**

```
One round table, six people around it, no faces or bodies yet.
```

```
Add a slow camera movement.
```

```
Some more natural handheld movement. I want to keep it subtle.
```

Article: four cuts with exact timings, seat-locked characters, Claude-written dialogue that lands on whoever is in frame, per-character acting tasks. Article label: **The Diner Dialogue**. 30 seconds, one block.

Shot-list method from the video: brief Claude like a camera operator. Rails, targets, and the four cuts. Do not let people leave their chairs.

**Viral camera moves — blocking brief**

```
Three scenes, one continuous orbit, wraps around the crew by the car, loops around the basketball play mid shot, and lands on the hero while the car drifts around him.
```

```
The camera rockets up through a building, revealing a brand new world on every floor.
```

```
Mimics those crazy commercial rigs that whip to a frame and instantly lock into place.
```

Article label: **Seven Locations, One Take**. Three orbit passes, three vertical floor rises, robo-arm rooftop finale. Seven moves, one unbroken 30s flow. Attach blocking render + character + location refs. Video-to-video. Greybox drives every camera move 1:1.

**Soda ad — blocking rules**

```
The can is just a cylinder, the ice is just cubes, and the lemons are just spheres. No faces, no hands to mess up.
```

```
Edit line by line what the camera does, how the can moves, and where the fruit flies. Notice that scene seven is completely blank. I don't bother blocking liquid. Keep it black in the blockout and let the AI fill it in later.
```

```
Soda ads need fast, snappy motion. The camera slams in, pauses for a beat, and accelerates into the next cut.
```

Article: 13 scenes with per-scene cameras, commercial speed-ramp motion, black gaps left for liquid-sim generations. Article label: **The Higgs Commercial**. Attach blocked preview + can design sheets + three environment refs. Two black gaps are intentional.

**Car commercial**

Assets named in the video: two characters, the car, the blocking video. 19 shots in 30 seconds. Structural lock (cuts, camera, timing) stays. Style layer changes.

Four published style passes (copy the full prompt from the article for each):

| Style | Article title | What the article says it does |
|---|---|---|
| 1 Realism | The Night Chase | Live-action photoreal. Post-rain waterfront night, teal-and-amber grade, drift physics, police pursuit finale. 1:1 re-dress of the blocking. |
| 2 2.5D | The Painted Getaway | Hand-painted 2.5D. Grandpa getaway driver, knitting grandma, 1960s saloon, golden hour. Driven by a style-master image + the same blocking video. |
| 3 2D | The Ink Chase | Moving black-and-white manga page. Exactly two colored objects — her red dress and the pink car. Frames locked 1:1 to the blocking. |
| 4 3D | The Toybox Western | Toy stop-motion western. Brick-built canyon, wind-up tin robot driver, amigurumi cat partner. Lip-synced dialogue. No extra shots. |

Spoken generation instruction used on the commercial:

```
Define what the gray boxes are and the characters acting.
```

### Official first Bridge prompt (plugin page)

```
Build me a calibration bay blockout in Blender
```

### Image-bar example on the plugin page

```
Night rooftop with neon signs and rain
```

## Step-by-Step Recreation Playbook

Written for an agent. Do not skip the copy step on the article.

1. Confirm Blender 4.2–5.1 is installed. Confirm the user has a Higgsfield login with credits.
2. Install the add-on from https://higgsfield.ai/plugins/blender. Keep the zip zipped. Drag onto the Blender window. Sign in on the floating bar.
3. Add the Higgsfield Bridge connector in Claude: `https://bridge.higgsfield.ai/mcp`, name **Higgsfield Bridge**, sign in.
4. Open a new `.blend`. Save immediately. Save a backup after every blocking stage (the article says this for the fight; do it on every case).
5. Pick one use case. Paste the matching Claude blocking brief above. Let the Bridge place real geometry (Scene Builder), not a picture.
6. Keep proxies cheap: boxes for bodies, cylinder for the can, cubes for ice, spheres for fruit. No faces in the greybox unless the shot needs a head turn you will lock later.
7. Animate the camera in Blender. For dialogue, give Claude an explicit shot list with cut count. For ads, write the speed-ramp (slam / pause / accelerate) into the brief.
8. Leave liquid, sparks, and other sims as black gaps in the blockout. Do not waste blockout time on them.
9. Render the previz: 1920×1080, 24 fps, duration = final clip (30s in every featured case).
10. Open https://higgsfield.ai/@adilinthewild/blogs/this-blender-higgsfield-ai-workflow-changes-how-you-make-ai-video and copy the generation prompt box for that use case. If you must regenerate a prompt instead of copying, attach the blockout clip and use:

```
Write a 30-second Seedance prompt based on this video blocking. Read the input video and write out the prompt second by second to match the camera moves in the clip.
```

11. In Higgsfield (Video tab in Blender, or Cinema Studio on the web) run Seedance 2.5 video-to-video. Attach the blockout as the motion source. Attach character sheets and location stills as look refs. Set duration to match the blocking (30s).
12. Compare against an unblocked text-to-video take of the same prompt if you need the credit-saving proof the video shows. Keep the blocked take.
13. For the car commercial only: lock the 19-shot edit once. Re-run the same blocking video through each of the four style prompts. Do not rebuild cameras.
14. Edit. Do not add shots the blockout did not contain unless the user asks.

## Key Learnings & Replication Notes

- Credits die on bad camera guesses. A greybox render is cheaper than a failed Seedance take.
- You do not need to model in Blender. Claude + Bridge builds the blockout from a plain-language brief.
- Greybox = timing and path. References = identity and set. Mixing those jobs in one text prompt is how seats swap and hands melt.
- Seat lock is a blocking problem, not a prompt-adjective problem. Six people stay in six chairs because the previz already put them there.
- Shot count belongs in the brief ("exactly four cuts") the same way it does in other Higgsfield playbooks.
- Liquid and other sims: leave black. Let Seedance invent them in the gaps.
- Product proxies should have no faces and no hands. Cylinder / cube / sphere is enough for a soda ad.
- One blocking file, many worlds. The 19-shot commercial is the proof: realism, paint, manga, toys, same cameras.
- Save incremental `.blend` copies. Bridge edits are live in the open scene.
- Plugin needs the network. Already-generated files stay in the `.blend` and on disk offline.
- Same Higgsfield credits as the website. Cost shows on the Generate button before you press it.
- Anti-Slop mode is listed on the official plugin guide for Seedance 2.5 inside Blender. Use it when hands or physics go soft.
- ASR on the YouTube captions says "Kixlab" / "C dance" / "Cloud". Those are Higgsfield, Seedance, and Claude.

## Raw Links

- Video: https://www.youtube.com/watch?v=OiULPvTJ-0E
- Prompts share link: https://higgsfield.ai/s/blender-plugin-higgsfieldai-lpdrbq
- Prompts article: https://higgsfield.ai/@adilinthewild/blogs/this-blender-higgsfield-ai-workflow-changes-how-you-make-ai-video
- Plugin share link: https://higgsfield.ai/s/blender-plugin-higgsfieldai-CFXDqV
- Plugin page: https://higgsfield.ai/plugins/blender
- Plugin guide: https://higgsfield.ai/blog/higgsfield-blender-plugin
- Bridge MCP: https://bridge.higgsfield.ai/mcp
- Generic Higgsfield MCP (not the Bridge): https://mcp.higgsfield.ai/mcp
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
