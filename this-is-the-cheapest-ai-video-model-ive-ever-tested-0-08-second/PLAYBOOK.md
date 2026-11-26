# This Is The Cheapest AI Video Model I've Ever Tested ($0.08/Second)

## Final Result
Clips generated with MAGI-2 on Higgsfield: up to 30 seconds of 1080p video with native sound at roughly $0.08 per second. Examples include anime fights from character references, painterly cartoon animation, 3D characters, motion design that mixes 2D and 3D, product ads, consistent characters across video references, multi-character fight scenes, Blender previs turned into final shots, one-take continuous camera moves, realistic UGC ads, text-only generations, and microdramas from a single image.

## Skill Installation
No downloadable .skill file. MAGI-2 is a video model available in the Higgsfield web app and via the Higgsfield API.

In the web app:
1. Go to Video → Create Video.
2. Select model MAGI-2.
3. Choose References mode (up to 10 images, 5 videos, 5 audio) or Frames mode (start frame + optional end frame).
4. Write the prompt. Refer to uploads as Image 1, Video 1, or Audio 1.
5. Set duration (4–30 s), aspect ratio, and Sound on or off.
6. Generate.

API model ID: sand/magi-2/text-to-video (also image-to-video and reference-to-video variants). Price is $0.08 per second. One concurrent generation per account on standard plans.

## Complete Prompt Library

### Structured Skate Film Example (from official how-to)
SCENE CONTEXT
Early morning on an empty city street at dawn. A young woman drops her skateboard, rides down the long empty road toward the skyline, pops an ollie against the rising sun and rolls on toward the waking city. Energetic, playful skate-film editing, no other people.

ACTIVE REFERENCES
@Image 1: young woman, about 20, slim, soft features, light freckles. Choppy layered copper-orange bob with darker roots, two light-blue hair clips on her left side, pink translucent rectangular glasses, silver chain necklace with small charms. Oversized royal-blue T-shirt with a white checkerboard band across the chest, worn over a white long-sleeve top, black leather belt, leopard-print cargo shorts, pink socks with flowers, black loafers. Her face and outfit 100% match @Image 1 in every shot.
Skateboard: plain light natural-wood deck with no graphics, light wheels.
@Image 2: location reference. @Image 2 controls the geography: the long empty road with worn cracked asphalt and a dashed white line, the ornate pale stone balustrade with vintage lamp posts on the left, the trolley poles, overhead wires and the low tiled-roof building on the right, and the skyline of high-rise towers at the end of the road. No cars, no people. No readable text or logos anywhere.

FORMAT MODE
Controlled multi-shot sequence, six shots, HARD CUTs at 2.0s, 3.5s, 6.5s, 9.5s and 12.0s. Real-time motion, energetic rhythm. Outfit, hair, glasses, board and golden light stay identical in every shot.

LIGHT LOGIC
A low sun rises between the towers at the end of the road. When the camera faces her front, her face is lit by warm golden sun. When the camera faces the city, she is backlit with a glowing rim and the sun flares between the towers.

SHOT 1 — 0.0s to 2.0s — FACE
LENS LOCK = 29° short telephoto portrait, camera 2 meters in front of her, at eye level. Close-up of her face, front view. Warm low sun lights her face; behind her the road and lamp posts melt into soft golden bokeh. She pushes her pink glasses up her nose with one finger, looks past the camera toward the city, and a small confident half-smile appears. The blue hair clips catch the light; loose strands move in the breeze.

SHOT 2 — 2.0s to 3.5s — BOARD DROP
LENS LOCK = 84° wide, camera on the asphalt, 30 cm from the board. Ground-level close shot: the skateboard slaps flat onto the cracked asphalt, a black loafer with a pink flower sock steps onto it, the other foot gives one hard push, and the board shoots out of frame toward the city.

SHOT 3 — 3.5s to 6.5s — RIDE
LENS LOCK = 84° wide, camera low on a moving vehicle, 3 meters behind her, facing the city. She rides away from camera toward the skyline, pushing twice, then carving smooth S-turns along the dashed white line. The sun glows between the towers ahead; her backlit hair and T-shirt flutter in the wind. The camera chases her with speed and slight bumps from the road.

SHOT 4 — 6.5s to 9.5s — FACE IN MOTION
LENS LOCK = 47° standard, camera on a moving vehicle riding alongside on her left, 1.5 meters away, slightly ahead and angled back at her. Medium close-up of her in three-quarter front view while she rides: hair whipping back, T-shirt billowing, glasses catching a sun glint. She glances at the camera and breaks into a real, easy laugh, then looks ahead again. The stone balustrade and lamp posts streak past behind her in motion blur.

SHOT 5 — 9.5s to 12.0s — OLLIE
LENS LOCK = 84° wide, camera very low behind her left shoulder, moving with her, facing the city. She crouches, then pops an ollie over a crack in the asphalt: the tail snaps sharply on the road, the board rises to her feet, and at the top of the jump she hangs for a split second in the air, a crisp silhouette against the sun between the towers, with a lens flare.

SHOT 6 — 12.0s to 15.0s — PASS AND GO
LENS LOCK = 47° standard, camera standing low on the road ahead of her, facing her.
12.0s to 13.0s: she lands with a solid thud, knees absorbing the impact, and rolls straight toward the camera, grinning, golden sun on her face.
13.0s to 13.8s: she rolls past the camera very close, her laughing face and the wind of her passing filling the frame for a moment.
13.8s to 15.0s: the camera stays in place and swings around to follow her; she rolls away down the empty road toward the skyline and the rising sun, growing smaller.

PHYSICS
Real skateboard physics: the deck flexes under her weight, wheels vibrate over rough asphalt, carves come from shifting weight, the ollie has a sharp pop, a real arc and a weighted landing. Hair and clothes react to speed and wind with natural delay.

AUDIO
Only live sound, cut to the picture: quiet morning and distant birds, the slap of the board on asphalt, the push, wheels rolling louder and louder over rough asphalt, wind rushing past, a far-off tram bell, a short laugh, the sharp clack of the ollie pop, the thud of the landing, the whoosh as she passes the camera, then the wheels fading into the low hum of the waking city. No music.

STYLE
35mm film, warm golden-hour cinema, fine film grain, soft halation around the sun and the glowing lamps, natural colour, energetic indie skate-film mood.

### Arena Fight Scene Prompt (structured, 30 s continuous)
SCENE CONTEXT
In the fleshy toilet of the living bar, Image 1, just after crying, washes her face alone. A hooded cyclops assassin, Video 1, comes up behind her with one axe. She fights back empty-handed; both end standing, neither beaten, and we first see his face.

ACTIVE REFERENCES
Video 2 — camera path and timing for 0:00–0:23 only, exactly as in this previz; then the same camera continues unbroken as below; its grey shapes, colours and lighting stay out.
Image 2 — the toilet, exactly as in the reference: oval room, dark flesh dome, pale veined honeycomb ceiling, hanging sinew strands; round the wall a waist-high band of thin watery glowing yellow liquid in a translucent elastic membrane, white clumps in it; along the left wall pale shell sinks on dark stems, brass taps, each with a round brass-framed mirror on a stalk; on the right a free-standing row of dark metal-framed booths with pale arched doors; round puckered hole in the far wall; dark wet shining flesh floor.
Image 1 — Nisa: face, hair, body, costume, bow, quiver, blades 100% as in the reference; both blades stay sheathed at her thighs, she never touches their grips; hands empty in every frame.
Video 1 — the assassin: body, hooded cloak, armour and the single axe exactly as in the reference. One axe, right hand throughout; left hand holds no weapon or prop, it can intercept, release, grip, push. Left/right means each character's own body.
Video 1 — his face and head, exactly as in this reference, seen only from 0:29.3: deep red skin with black tiger-like stripes, bald head, two small horn ridges at the temples, one large amber-brown eye in the middle of the face in a polished steel oval ring whose band wraps round the head, below it an enormous lipless grin of big yellowed teeth cheek to cheek. Count of eyes: one.

LOCATION MAP
Booths right, sinks along the left wall; camera enters through the wall by the near end of the booths. Nisa at the nearest left sink, facing its mirror, back to the room; the assassin waits in the far-left booth behind her. The fight stays at the sinks; after turning, Nisa stays between him and the sinks, facing him, never behind him. He stays a short step out from the sinks. Stand-off: Nisa with the sinks behind her, he ~1.5 m away on the open wet floor.

FIRST FRAME
Lens inside the glowing yellow liquid of the wall band: watery yellow, white clumps drifting past, the pale membrane ahead, the blurred room beyond.

FORMAT MODE
One continuous 30-second shot, single take, 100° wide.

(Full second-by-second action timing, camera, acting, physics, lighting, audio, positive locks, colour law, and style blocks are on the official announcing page. Copy the complete version from there for exact recreation.)

## Step-by-Step Recreation Playbook
1. Open Higgsfield and select MAGI-2 under Video → Create Video.
2. Decide mode: References for character/location/motion locking, or Frames for start-to-end animation.
3. Upload only material you own or have rights to. Label them clearly in the prompt as Image 1, Video 1, Audio 1.
4. Write a structured prompt. Start with SCENE CONTEXT. List ACTIVE REFERENCES and what each controls. Add LOCATION MAP, FORMAT MODE (continuous or multi-shot with cut times), SHOT list with lens and timing, PHYSICS, LIGHTING, AUDIO, and STYLE.
5. Keep each clip to one or two actions and one camera move for best consistency.
6. For Frames mode, describe the scene already visible in the start image plus the movement that follows. Do not rewrite the scene.
7. Set duration, aspect ratio, and Sound. Check credit cost, then generate.
8. For longer sequences, generate short clips and cut them together.
9. Use video references for camera path and timing when you have previz.
10. Iterate by changing one block at a time.

## Key Learnings & Replication Notes
MAGI-2 generates picture and sound together. Describe audio explicitly if you want specific effects or dialogue.
Limit actions and camera moves per clip. Competing motions reduce quality.
Reference images lock identity. Describe exactly what to take from each image and what to ignore.
For start-frame work, match the prompt to the image content or the model will change the image.
Continuous takes up to 30 s are possible when the prompt keeps the camera path and action simple.
Structured blocks (SCENE CONTEXT, ACTIVE REFERENCES, SHOT list with times, PHYSICS, AUDIO) outperform short free-form prompts.
Cost is linear with duration at $0.08/s. Draft shorter clips first.

## Raw Links
Video: https://www.youtube.com/watch?v=S5fMIf3RQ2U
Try MAGI-2: https://higgsfield.ai/s/magi-2-higgsfieldai-XLJdOS
Discount: https://higgsfield.ai/s/magi-2-higgsfieldai-QkmUDY
Official how-to: https://higgsfield.ai/blog/higgsfield-magi-2
Announcing page with full prompts: https://higgsfield.ai/announcing-magi-2
API playground: https://open.higgsfield.ai/models/sand/magi-2/text-to-video/playground
