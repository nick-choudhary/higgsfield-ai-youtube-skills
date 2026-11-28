---
name: higgsfield-viral-shorts
description: Create original narrated Shorts with code-rendered 2D characters in a 3D world, 8-bit animation, or full 3D. Use Higgsfield for available voice and asset generation, then build, time, render, and check the film in a code-capable environment. Use for making or revising a Short, not copying an existing creator or automatically publishing it.
---

# Higgsfield Viral Shorts

Turn one original story into a finished animated Short. Choose a visual style, build the scenes with code, and use Higgsfield for the voice and assets the film needs.

Attach this file to a code-capable assistant, such as a supported Higgsfield Supercomputer session or Claude Code, connect Higgsfield where needed, and give it your story or selected script. This file contains the workflow instructions. It does not install software, connect accounts, include a rendering engine, or supply copyrighted media. The assistant must create the project files it needs and use tools actually available in its environment.

## Start with the brief

Read the user's request and attached materials first. Preserve an approved script, style, voice, and duration. Ask only for a missing decision that materially changes the film. Otherwise choose a reasonable default, state it briefly, and proceed within the authorized scope.

Establish:

- **Story:** the script or the question the film will answer.
- **Style:** 2D characters in a 3D world, 8-bit, or full 3D.
- **Length:** the requested duration or maximum. Do not treat 61 seconds as a platform requirement.
- **Voice:** a supplied recording or a voice available through the connected Higgsfield tools.
- **Output:** default to a vertical 1080 × 1920 MP4 at 30 fps, unless the user specifies otherwise.
- **Constraints:** locked wording, permitted references, budget, and any assets that must remain unchanged.

For a separate style version, agree from the request what must carry over. If the user asks for the same narration and timing, preserve the original audio and timeline. If the user asks for a separate version, do not claim that its voice or length matches the original unless verified.

Do not require the user to configure a render engine if you can select an appropriate available one. Do not silently change the story to fit a convenient template.

## 1. Check the story and write for the screen

Use historical events, everyday mechanisms, real experiments, or clearly identified thought experiments. Research facts using credible sources, preferably primary or institutional sources. Keep a small internal source record for dates, numbers, and causal claims. A source is evidence, not permission to reuse its wording or media.

Write original narration in natural spoken English unless the user requests another language. Keep the explanation clear enough to follow without pausing. A useful structure is:

1. **Hook:** a concrete question, surprising result, or apparent contradiction.
2. **Build:** two or three connected details that make the question more interesting.
3. **Explanation:** show the mechanism or decision that changes the story.
4. **Payoff:** answer the opening question with a consequence or final detail that follows from the evidence.

This is a flexible structure, not a fixed phrase sequence. Do not force “You see,” invent a twist, or copy another narrator's cadence. Avoid empty introductions and suspense that never pays off.

For history, distinguish documented facts from disputed accounts. For science, distinguish an observed experiment from a hypothetical scenario. A “last person on Earth” story is a thought experiment, not a real experiment. Do not invent participant numbers, research findings, quotations, earnings, or view counts.

Write to the requested duration, then test with the actual voice. If the first take is too long, tighten the script before speeding up speech. Four words per second is not a requirement. Preserve intelligibility and meaningful pauses.

Do not promise virality, a specific income, monetization approval, or a guaranteed audience response. “Viral Shorts” is the name of this workflow, not a performance guarantee.

## 2. Check the tools, then choose the voice

Inspect the connected Higgsfield tool catalogue before generating anything. Use its current model names, inputs, costs, and output formats. Do not fabricate tool calls, model IDs, voice IDs, or successful results.

Use these routes when they are available and appropriate:

| Need | Model or tool to look for | Role in this workflow |
| --- | --- | --- |
| Narration | Higgsfield speech tools; ElevenLabs V4 when available | Generate the selected narrator, then measure the resulting audio. |
| Transparent costumes and props | GPT Image 2 | Create original flat assets for the hybrid style. |
| Optional hero object | Meshy image-to-3D, including Meshy V7 when available | Turn an original or authorized reference image into an inspectable 3D asset. |
| Rendering the animation | An available code renderer such as Blender or a browser with WebGL | Build and animate the scenes. This is separate from generating still assets. |

These are routing preferences, not evidence that a particular tool is installed. If a named model is unavailable, explain the relevant alternative and follow the user's constraints. Do not substitute a different model while displaying the requested model's name.

For the accompanying tutorial, the selected narrator is **Arthur**. List or search the actual available voices, select the matching Arthur entry, and use the identifier returned by the tool. Preview it when supported. If Arthur is unavailable or the choice is ambiguous, resolve that before recording the full narration. Do not invent a voice card or silently choose a substitute. A user's explicit voice choice overrides this tutorial default.

Keep the same voice and compatible settings throughout one film. A continuous take often gives more consistent delivery; separate takes can help with line-level revisions. Use whichever preserves continuity and accurate timing. Do not clone a real person's voice without the necessary permission.

Measure each recorded line or the continuous track. Create word or phrase timings from the actual audio. Store the final narration before animation timing is locked. If the audio changes later, update the affected scene, caption, and sound timings together.

Use paid generation within the user's authorized scope and budget. Check cost where the tools expose it. Do not introduce repeated approval gates for already authorized work; ask before adding material unapproved spend or renting infrastructure.

## 3. Build the visual plan

Map the narration to a short shot list. Each beat should have a clear visual subject and a reason to exist.

Record the beat's start and end time, narration, subject, action, camera, transition, and sound event. Keep these timings in one editable timeline used by rendering, captions, and audio.

Show cause and effect. If a clock solves a navigation problem, show the information it provides and how it is used. If a shape changes stress, make the difference visible. If a person disappears from a city, show the specific systems that stop working. Attractive scenes alone do not explain the idea.

Use original, user-owned, licensed, or verified public-domain inputs. Do not import another channel's script, frame sequence, character design, soundtrack, or screenshots as a production template. Broad styles such as pixel art, flat characters, and 3D animation are suitable starting points; develop a distinct setting and composition for this story.

### A. 2D characters inside a 3D world

Use Blender or another available renderer capable of 3D lighting, geometry, shadows, and camera animation. Blender may run in the background; the user does not need to operate its interface manually.

- Build real 3D sets with consistent scale, surfaces, light, and physical depth.
- Draw simple flat heads, facial expressions, hands, and line limbs in code. Generate only the illustrated assets the scene needs, such as costumes, hair, hats, maps, and letters.
- For GPT Image 2, request original flat painted assets with transparent backgrounds and consistent proportions. A costume asset can be headless because the character's head is drawn separately; the final character must be complete.
- Place the 2D parts on transparent planes in the 3D scene. Keep the face readable as the camera moves. Ground the feet, align held props with the hands, and allow believable shadows and occlusion.
- A moving platform needs local coordinates. A character on a ship must turn toward the camera in the ship's coordinate space, rather than sliding or rotating incorrectly as the ship moves.
- Use expressions, gaze, arm poses, and simple body motion to communicate action. Do not claim that the image model generated the expressions when they were drawn by code.
- Keep characters legible on a phone. Avoid sets or props hiding the face or swallowing the action.

Use camera movement to reveal information. If a continuous moving sequence is requested, hide transitions behind actual foreground objects or a motivated whip. Match direction, brightness, and color across the join. Check the outgoing and incoming frames; a mid-shot preview cannot reveal a bad cut.

### B. 8-bit / pixel-3D

Use an original browser/WebGL scene or another available code renderer. Choose a low internal resolution and upscale with nearest-neighbor filtering. For example, 270 × 480 can become 1080 × 1920 while keeping the pixel grid crisp.

- Build original low-detail geometry, sprites, textures, and a coherent limited palette.
- Do not use recognizable game characters, ripped sprite sheets, branded interfaces, or a game's distinctive assets.
- Make the mechanism readable through movement, color, or a simple cutaway. Use labels only when they improve understanding.
- Keep text and silhouettes readable at the chosen internal resolution. Avoid mixing crisp pixels with accidental blurry interpolation.
- Move the camera when the story needs a reveal or change of scale. Hold long enough for the viewer to understand a new idea.

### C. Full 3D

Choose the renderer for the requested look. Blender with physically based materials is suitable for a realistic result. A browser renderer such as three.js is suitable for a stylized result when the environment supports it. Do not present a flat illustration or an unrendered model as the finished 3D video.

- Build or generate original geometry. Inspect any generated model from several angles before staging it.
- Check scale, orientation, topology problems, unwanted text, and materials. Remove accidental logos and unrequested markings.
- Use bevels, material roughness, coherent lighting, and appropriate camera distance to make objects readable.
- Favor a clear mechanical demonstration over decorative detail. An explanatory cutaway or simplified object is acceptable when its simplification does not change the claim.
- Avoid recognizable brands or exact protected product designs unless the user's rights and intended use have been established.

For an engineering story, distinguish a visual analogy from a validated simulation. Do not label an illustrative stress or pressure animation as measured scientific output.

## 4. Implement a fresh, reproducible project

This Markdown file has no companion engine or helper scripts. Do not call paths from an unseen ZIP or import project-specific modules that have not been created. Write the necessary project files in the current workspace using the available runtime.

A useful project separates the script, timeline, assets, scene code, audio, captions, renders, and final exports. Add a short run note with the actual commands and dependencies that were used. Use normally installed libraries with their applicable licenses; do not package someone else's source code or remove its notices.

Before building the full film:

1. Check which renderer, browser, audio tools, and encoder are actually available. Reuse installed tools; add a missing dependency only when needed and permitted in the environment.
2. Render a still from the intended scene setup.
3. Render a short moving test with the voice and camera timing.
4. Inspect the test, correct visible problems, then build the remaining shots.

If code execution or a required renderer is unavailable, state the specific limitation and provide the runnable project or the next setup step that is possible. Do not say the film is generated when only the prompt or source code exists.

Make each frame reproducible from its frame number or time. Avoid wall-clock timing, accumulated browser animation state, and unseeded randomness. Seed procedural choices during setup. The same timestamp should produce the same scene when rendered alone or as part of a batch.

Define stable scene anchors for characters, props, and camera targets. Keep action, camera, mouth movement if used, captions, and sound events on the shared timeline. Test at least one frame near the start, middle, and end of each shot.

Render into a new versioned folder. Do not overwrite a delivered version while experimenting. Avoid concurrent heavy local renders when they cause memory pressure or missing frames. Use cloud rendering only when available and authorized; shut down rented resources after the job.

## 5. Finish the sound and captions

Keep narration clear. Use original or licensed music and sound effects only. If provenance is unclear, replace the asset rather than carrying it into a public deliverable.

Tie effects to visible events in the timeline. Ambience can connect locations; music can support a change in mood. Do not put a whoosh on every movement by default. Leave space where a pause helps the explanation or payoff.

Measure loudness and peaks, then listen to the mix when playback is available. Music around 16 LU below the voice can be a starting point, not a universal setting. Adjust for the voice, frequency overlap, and platform delivery. Avoid clipping and abrupt level jumps. Do not claim an audible quality check if you only measured numbers.

If captions are requested, align them to the actual spoken words. Use short, readable chunks and keep them clear of faces, important diagrams, and platform controls. Check the export at phone size. Do not animate every letter if it makes reading harder.

Encode a widely compatible MP4 with the requested dimensions and frame rate. Include the entire intended narration and ending. Keep an effects-only or clean master when requested, rather than removing the approved voice from the primary deliverable.

## 6. Review the actual output

Inspect the rendered film, not just the script or a successful render log.

- Check duration, dimensions, frame rate, audio stream, and successful decoding through the final frame.
- Check every shot and transition for black frames, missing assets, flicker, clipping, floating characters, unreadable faces, and captions covering the explanation.
- Confirm that the ending answers the opening question and that the visuals do not contradict the narration.
- Confirm that generated speech says the approved words and contains no unintended phrases.
- Verify asset provenance and distinguish factual claims from illustrative or hypothetical scenes.
- If a check could not be completed, say exactly which check remains. Do not call an unseen film fully reviewed.

For Higgsfield's official channels, website, paid creator work, or promotional demos, also apply these brand boundaries to the actual text, visuals, and audio:

- No political figures, party messages, election content, or war content. Historical figures require the relevant brand review before use; a generic character can illustrate the mechanism without recreating a person's likeness.
- No sexualized framing, sexual content involving minors, slurs, racial caricatures, or identity-based jokes.
- No realistic gore, violence against recognizable real people, or real tragedy used as a gag, spectacle, or sales hook. A serious historical subject does not automatically make a promotional depiction appropriate.
- No unauthorized third-party IP, recognizable likenesses, voice imitation, or misleading endorsement. If rights are unresolved, use original alternatives or obtain the appropriate rights review before release.
- No invented capabilities, invented results, guaranteed income, or misleading statements about model ownership.

Judge what is actually shown. A neutral setting or a harmless object is not a violation by association. Do not claim that this instruction file certifies all future videos or provides legal clearance.

## Deliver

Provide the finished MP4 with a short note naming the style, actual duration, voice, and any material limitation. Include the editable project, script, captions, or alternate versions when requested. Keep the source and asset record with the project; it does not need to clutter the public video.

For a revision, preserve the approved parts. Patch the affected shots and rebuild dependent audio or captions only when timing changes. Keep previous finals available.

Generating a film does not authorize posting it. Upload or publish only when the user has asked for that action.
