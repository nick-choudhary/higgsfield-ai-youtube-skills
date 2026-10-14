# PLAYBOOK: How I Make Motion Graphics Inside Claude Motion (Opus 5.5)

**Source Video:** https://www.youtube.com/watch?v=5HYYXYYCrL4  
**Published:** 2026-10-13  
**Prompt pack / skill page:** https://higgsfield.ai/s/claudemotion-higgsfieldai-skVQgf  
**MCP connect page:** https://higgsfield.ai/s/claudemotion-higgsfieldai-HrEFvp  

## Final Result

Claude Opus 5.5 plus Higgsfield MCP builds editable motion graphics. Three levels: recreate a launch video with new footage, build a 3D product ad, and produce a full animated short. Projects export as code for After Effects or Blender edits. Voices and live-action clips come from Higgsfield.

## Skill Installation

Two skills:

- higgsfield-motion-claude (core motion skill, file higgsfield-motion-claude.skill)
- higgsfield-motion-saas (SaaS and app launch videos, file higgsfield-motion-saas.skill)

Steps:

1. Upload both .skill files under Claude Customize → Skills.
2. Connect Higgsfield under Connectors so Claude can generate footage, characters, locations, and voices.
3. Open a new chat. Select Opus 5.5. Go to Artifacts and choose Motion.
4. Attach reference videos or screenshots. Paste one of the briefs below. Send.

For Claude Code MCP:

```
npm i -g @higgsfield/cli
```

Run the CLI login command and complete browser sign-in.

```
npx skills add higgsfield-ai/skills
```

Then paste this to Claude Code:

"Set up Higgsfield for me so I can generate images and videos from here."

Do not download or re-host the .skill binaries. Use the official page.

## Complete Prompt Library

### Case 1 — Recreate a Launch Video with New Footage

Use higgsfield-motion-claude and higgsfield-motion-saas to recreate this ad shot by shot:

https://www.instagram.com/p/Dd66aLqCbO6/

Use the attached video as the frame-accurate reference.

Match its duration, aspect ratio, framing, cut points, typing, cursor movement, camera moves, and transitions. Rebuild the chat, Finder, editor, export window, and pink desktop in code. Keep the UI, text, cursor, transitions, and timeline editable.

Create the live-action footage through Higgsfield. Before generating the clips, generate consistent reference sheets for the character and car in Seedream on a neutral grey background. Generate empty location sheets in Soul Cinema at a three-quarter angle. Create an attractive, realistic adult woman; she does not need to look identical to the reference. Reuse the character, car, and location sheets across the relevant shots.

Use the sheets as reference inputs without forcing each video to begin on a reference-sheet frame. Match each shot's action, composition, camera movement, and edit points. Keep the laptop open where the action requires it, place the mug in the correct hand, avoid extra people, and make the cleanup shot one continuous take. Check that props and actions remain consistent across cuts.

Use the supplied Higgsfield logo as a clean graphic in the export scene, with correct proportions and legible lettering. Keep generated footage separate from the editable motion so either can be replaced independently. Build a clean, synchronised sound mix without clipping, distortion, or abrupt audio cuts.

Compare the assembled result with the reference at the same absolute timecodes. Fix continuity errors, mistimed transitions, unreadable text, and distorted branding before delivery.

Plan the shots, then continue through production and quality checks to the finished result. Do not stop at a storyboard or first preview. Deliver the final MP4, the editable code project, and organised visual and audio assets.

### Case 2 — Combine Three References into an Original Launch

Use higgsfield-motion-claude and higgsfield-motion-saas to create an original launch film for Claude Motion × Higgsfield.ai.

Study these three references:

https://www.instagram.com/p/DeHzMbDidhx/

https://www.instagram.com/p/Dd4VIgTq8e7/

https://www.instagram.com/p/Ddw64rKK6tN/

Combine their strongest ideas into one coherent film with an original sequence. Format: 1920×1080, 16:9, exactly 20 seconds. Make it dynamic and very smooth, with clear visual progression and a readable final brand lockup.

Build the motion graphics in code. Use kinetic typography, a particle sphere, a moving dot grid, and a 3D fan where they support the sequence. Connect scenes through visible actions, matching shapes, and continuous camera movement. Use Higgsfield for any generated visual content placed inside the design, maintaining a consistent look across those assets.

Keep the project organised into editable scenes and layers. Expose text, fonts, palette, individual colours, layer visibility, scale, position, and scene duration as controls. Text containers must resize correctly when copy changes. Use the supplied brand assets where available; otherwise use clean text wordmarks.

Drive the scenes and sound from a shared timeline. Changing a scene's duration must shift subsequent scenes and update the related music and sound cues. Check that transitions still connect and text remains readable after timing changes.

Create a finished soundtrack with music and synchronised sound effects. Check the full export for abrupt movement, particle flicker, text overflow, clipped elements, and audio sync problems.

Plan the film and continue through the complete build, sound mix, and quality checks without stopping at a storyboard or preview. Deliver the finished 20-second MP4, editable project, controls, and separate assets.

### Case 3 — A 3D Laptop Launch with a Bicycle Transformation

Use higgsfield-motion-claude to create a polished 3D launch film for Higgsfield MCP × Claude Motion from the attached reference.mp4. Use higgsfield-motion-saas for the laptop's UI animation and connected transitions.

Format: 1920×1080, 16:9, exactly 30 seconds. Preserve the reference's story, key copy, and edit rhythm, while rebuilding the shots in code as a 3D scene with crisp 2D interface plates. Use one desk and one laptop as the continuous setting; the story plays out through the laptop and the objects it presents.

Use the attached fonts and the actual Higgsfield and Claude logos. Keep text and logos sharp, correctly proportioned, and editable. The supplied reference and brand assets take priority over default skill styling.

Give the scene rich, realistic material detail, studio softbox lighting, and smooth, motivated camera movement. Add restrained light streaks, lens flares, glints, and very faint dust during compositing. Use hand-drawn transition accents where appropriate without covering the product or text.

Extend the sequence naturally to 30 seconds with a couple of new shots that develop the existing story. Keep the flip transition continuous and smooth, with no pause in the middle or sudden change of direction.

For the product assembly and transformation sequence, use the bicycle in the attached image instead of the truck. Build the action around recognisable bicycle components: frame, fork, wheels, handlebars, pedals, and saddle. Keep their proportions and assembly order believable. Adapt the camera framing to the bicycle's silhouette and preserve the surrounding film's lighting, materials, and motion style.

Keep the bicycle parts, scene objects, camera animation, UI, copy, branding, and timing editable in the code project. Add music and sound effects that follow the assembly, transitions, and final reveal.

Plan, build, render, and inspect the complete film. Fix intersections, assembly errors, abrupt camera moves, unreadable branding, and sound-sync problems. Continue to the finished result without stopping at a storyboard or preview. Deliver the final 30-second MP4, editable code project, and all supporting assets.

### Case 4 — An ASCII Journey Inside an App

Use higgsfield-motion-claude and higgsfield-motion-saas to create an original ASCII-style launch film using the attached launch and particle-animation references.

Format: 1920×1080, 16:9, 24 seconds. Build the design, particles, ASCII forms, interface, typography, camera moves, and transitions in editable code.

Start inside a clear, believable app interface. A visible cursor click launches the camera into the app. Interface cards become tunnels, graphs become tracks, and files assemble into a video timeline. Return to the interface and reveal the finished video as the payoff.

Keep one continuous visual language across the sequence: a consistent glyph set, particle scale, palette, type system, and motion style derived from the references. Make each transformation grow out of the previous action. Preserve the camera's direction across transitions and leave enough time to read the important UI states.

Generate visual content through Higgsfield for the previews, cards, and final video displayed inside the design. Integrate it into the ASCII world while keeping the interface and typography crisp. Keep these generated assets separate from the editable code layers.

Add music and sound effects synchronised to the click, transformations, timeline assembly, and reveal. Check for glyph flicker, visual noise, unreadable text, stalled camera motion, and abrupt cuts.

Continue from planning through production and quality checks to a complete result. Do not stop at a concept, storyboard, or preview. Deliver the finished 24-second MP4, editable project, and separate assets.

### Case 5 — Invent a Product and Build Its 3D Launch

Use higgsfield-motion-claude and the six attached visual references to create an original 3D product launch film. Invent the product, its name, and the central concept. Give it a recognisable silhouette and a clear purpose that the film communicates visually.

Create a 20-second, 1920×1080, 16:9 film. Use the references to guide realistic materials, bold lighting, fisheye close-ups, and smooth, continuous camera movement. Build everything in editable code.

### Case 6 — SaaS Motion Graphics

(Truncated in source extraction; use the skill page for any remaining SaaS-specific brief.)

### Case 7 — Why Does a Cat Need a Passport?

Use higgsfield-motion-claude to produce an original educational animated film titled “Why Does a Cat Need a Passport?” for a faceless YouTube channel.

FORMAT

1920×1080, 16:9, 24 fps, exactly 30 seconds. All dialogue, narration, and on-screen text must be in English. No on-camera presenter.

REFERENCE AND STYLE

Use Passport Rush for cinematic staging, expressive reactions, pacing, and visual comedy:

https://youtu.be/ZncA70OAgPw

Create original characters and a self-contained story. Use hand-drawn 2D animation throughout: confident outlines, flat colours, hand-drawn shadows, warm airport lighting, and lightly textured backgrounds. Animate characters and props. Avoid 3D, photorealism, and static-image slideshows. This art direction takes priority over the skill's launch-film defaults.

CHARACTERS

A slightly flustered young adult female traveller and her calm striped cat, who is better prepared than she is. Establish consistent reference sheets first, with expressive faces and readable silhouettes, and reuse them throughout.

HIGGSFIELD PRODUCTION

Generate the character animation, narration, and dialogue through Higgsfield. Use a warm, clear narrator with playful documentary delivery and distinct, consistent traveller and agent voices. Generate separate scene takes, measure their actual durations, and establish the audio timeline before animating. Preserve natural pacing and joke pauses; regenerate takes that do not fit their windows.

Use Higgsfield for character sheets, expressions, backgrounds, documents, and props where useful, maintaining the same 2D style. Build the passport pages, map routes, labels, and document text in editable code so the English remains accurate and readable. Keep generated character clips separate from these editable graphics.

STORYBOARD — USE THIS EXACT DIALOGUE

0–4s — Hook

The traveller approaches the check-in counter with one grounded final step and a clear stop. No floating, frozen jump, or sliding feet. She puts her passport down; the camera pulls back on that action. The agent points at the carrier. Cut to the cat slowly raising an eyebrow.

Agent: “Your passport… and the cat’s?”

Traveller: “The cat’s?!”

4–8s — Reveal

The cat slides out a tiny folder. A pet passport unfolds to fill the screen and becomes the explanation's setting.

Narrator: “Yes. For travel within the EU, there’s a pet passport.”

8–14s — Identification

Passport pages transform into a diagram showing the cat's silhouette, identifying details, and microchip. A scanner reads a number; its match lights up in the document. The cat proudly poses for an imaginary photograph.

Narrator: “It records the animal’s details and microchip number, linking this cat to these records.”

14–20s — Vaccination

A page turns. A vaccination symbol, date, and veterinarian's entry animate neatly into place.

Narrator: “It also records the rabies vaccination, so officials can check that it’s valid.”

20–24s — Important detail

The page unfolds into a map: two routes lead to different document sets. The cat checks his route against a checklist on a clipboard. The paper faces the cat, and the pencil tip touches the paper, not the clip. Keep paws and props correctly aligned throughout the action.

Narrator: “Other routes may require different documents. Check before you travel.”

24–30s — Payoff

Back at check-in, the traveller fumbles with crumpled papers. The cat opens a perfectly organised folder with coloured tabs and adjusts tiny glasses.

Traveller: “You’re more prepared than I am.”

The cat gives a confident meow. After the traveller's line, keep her mouth closed during the silent reaction while preserving her expression. Hold the reaction, then finish with a musical accent.

ANIMATION AND SOUND

Alternate medium shots, paw and document close-ups, and reactions. Transition through folders and page turns; grow educational graphics naturally from the passport. Use anticipation, follow-through, subtle squash-and-stretch, and pauses before jokes. Keep the main action readable and lip movements aligned with the actual speech.

Mix light adventurous music beneath clear dialogue, with paper rustles, a folder click, scanner beep, and final meow.

ACCURACY AND DELIVERY

The example concerns travel between EU countries. Do not imply that a pet passport guarantees boarding or replaces every document worldwide.

Continue through planning, asset generation, animation, compositing, sound, and quality checks to one finished film. Check character continuity, spelling, readability, grounded movement, clipboard geometry, mouth animation, and audio synchronisation. Include the corrected opening, clipboard, and ending in the main export, not only in separate previews.

Deliver one final MP4 of exactly 30 seconds, using the generated voices, plus editable project files and organised separate audio and visual assets. Do not stop at a storyboard or first preview.

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm the two skills (higgsfield-motion-claude and higgsfield-motion-saas) are uploaded in Claude Skills.
2. Confirm Higgsfield is connected under Connectors.
3. Select Opus 5.5 and enable Motion in Artifacts.
4. Attach the exact reference links or files named in the chosen case.
5. Paste the full brief for that case. Do not shorten it.
6. Let Claude run the full production sequence. Do not interrupt at storyboard.
7. Review the delivered MP4 and editable project. Request specific fixes for timing, text, or continuity using the same skills.
8. Export code for After Effects or Blender if further manual edits are needed.

## Key Learnings & Replication Notes

References beat adjectives. Attach the source video or screenshots. Specify exact durations, aspect ratios, and editable elements. Generated footage stays separate from the code motion so either can be swapped. Skills handle brand matching and UI animation. Full briefs include the revision notes so one message produces the finished version.

## Raw Links

- Video: https://www.youtube.com/watch?v=5HYYXYYCrL4
- Skills and prompts: https://higgsfield.ai/s/claudemotion-higgsfieldai-skVQgf
- MCP connect: https://higgsfield.ai/s/claudemotion-higgsfieldai-HrEFvp
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
