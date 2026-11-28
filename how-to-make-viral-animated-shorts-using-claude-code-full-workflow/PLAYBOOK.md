# How To Make VIRAL Animated Shorts Using Claude Code (Full Workflow)

Source: https://www.youtube.com/watch?v=GrFez9F0TF4  
Published: 2026-11-27  
Skill page: https://higgsfield.ai/s/faceless-shorts-higgsfieldai-IYvYnx

## Final Result

Three finished vertical Shorts, each under 90 seconds, in different styles:

- 2D stickmen inside a 3D world about John Harrison’s marine chronometer solving the longitude problem.
- 8-bit pixel animation explaining why airplane windows are rounded.
- Full 3D thought experiment: what if you were the last person on Earth.

Each uses a British narrator (Arthur via ElevenLabs), captions, licensed sound, and a clear hook-to-payoff structure. Total cost is low because generation is limited to voice and a few assets; the rest is code-rendered.

## Skill Installation

1. Connect Higgsfield MCP in Claude (or Claude Code). Use the MCP link from higgsfield.ai.
2. Download the skill file: Higgsfield_Viral_Shorts.md (linked from the blog page or the cloudfront URL in the prompts).
3. Attach the .md file to the chat or place it where the agent can read it. The skill is instructions, not a binary installer.
4. Optional: the page also offers faceless-shorts-scriptwriter.skill for idea generation. Attach it the same way.
5. Tell the agent to read the skill before starting any production request.

The skill routes voice to ElevenLabs/Arthur, costumes/props to GPT Image 2, optional 3D objects to Meshy, and animation to Blender or WebGL.

## Complete Prompt Library

### Idea generator

```
Use Higgsfield Viral Shorts to help me choose an original story.

Give me five original ideas for a short educational video. Choose from history, how everyday things work, and science or psychology. For each idea, give me a clear question, an opening line and a short outline with a satisfying ending. Suggest whether it would work best with 2D stickmen in a 3D world, 8-bit animation or full 3D, and explain the choice in one sentence.

Use credible sources to check the facts. What-if stories are fine, but make the hypothetical premise clear. Recommend one idea and write a natural English script of about a minute for it. Keep the explanation easy to follow and let the ending answer the hook. Don't generate media yet.

Read the Higgsfield Viral Shorts skill before starting: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/71c01284-d883-484d-a21f-592f5740c740.md
```

### 2D characters in a 3D world (longitude clock)

```
I'd like to make an original animated Short about how a clock helped sailors find their longitude. Use Higgsfield Viral Shorts for the workflow.

Make a new version of "The Clock a Carpenter Built to Find the Sea." Aim for about 70 seconds, vertical 1080 × 1920. Use flat 2D stickmen inside a 3D world.

Write the story around a practical problem: you can cross the ocean and still struggle to work out how far east or west you are. Introduce John Harrison, a carpenter and self-taught clockmaker, and explain why a clock had to keep accurate time on a moving ship. Show the simple comparison between local solar time and the time at a known reference point: every four minutes of difference equals one degree of longitude.

Check the history with Royal Museums Greenwich: https://www.rmg.co.uk/stories/time/harrisons-clocks-longitude-problem and https://www.rmg.co.uk/stories/time/what-longitude . Keep the tests of Harrison's different timekeepers separate. End with the long dispute over tests and rewards, without claiming that he was never paid. Use a generic illustrated craftsman and sailors; don't invent quotations or recreate a historical likeness. Open on the navigation problem, without staging a real shipwreck as a gag.

Start with the voiceover through Higgsfield. Find Arthur in the available ElevenLabs voices and use a natural British delivery, with changes in emotion that fit the story. If Arthur or ElevenLabs isn't available, show me the available alternative before recording. Measure the audio and build the timeline from it.

Use GPT Image 2 through Higgsfield for original costumes, wigs, hats and papers on transparent backgrounds. Draw the heads, hands and facial expressions with code. For a detailed ship or clock, generate a clean original reference and use an available Meshy image-to-3D model through Higgsfield. Inspect the props before placing them in the scene.

Build and animate the sets in Blender or an equivalent available code renderer. Keep the characters flat and facing the camera, with the scene's light, shadows and blur. Make the ship rock, and keep the characters and clock anchored to the deck. Move from the deck to the workshop and back to sea with clear, motivated transitions. Use two clocks and a simple globe diagram to make the time comparison visible.

Add licensed music, subtle ambience and sound effects where they support the action. Keep the voice clear and captions small but readable on a phone. Render and check the actual finished MP4, including the ending. Return the video and keep the editable scene files, script, audio and captions so I can change a shot later. If a required tool is missing, tell me what needs setting up instead of claiming the render is complete.

Read the Higgsfield Viral Shorts skill before starting: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/71c01284-d883-484d-a21f-592f5740c740.md
```

### 8-bit (airplane windows)

```
Let's make an original 8-bit Short called "Why Airplane Windows Are Round." Use Higgsfield Viral Shorts for the workflow.

Aim for 61 seconds, vertical 1080 × 1920. Draw and animate every visual with code. No image generation or borrowed game assets.

Start with a close view of a rounded airplane window and ask why it has that shape. Pull back to show the cabin, then explain the pressure difference between the inside and outside during flight. Show how repeated pressurization loads the fuselage. Compare a sharp-cornered opening with a rounded one: stress concentrates around sharp corners, while rounded corners spread it more smoothly.

Use a simple metal panel and colored stress lines to explain the principle. Label the diagram as illustrative, not a measured simulation. Show how a tiny crack can grow over repeated loading, then return to the original window for the payoff: the shape is part of how the structure handles stress.

Check the explanation against the FAA's Comet investigation summary: https://www.faa.gov/lessons_learned/transport_airplane/accidents/G-ALYV . Don't claim that passenger-window shape alone caused the 1954 accidents. Keep this version focused on the engineering explanation, without recreating a real crash or its victims.

Write a natural English script with a clear hook, explanation and ending. Start production with the voiceover through Higgsfield. Select Arthur from the available ElevenLabs voices, with a curious British delivery. If that voice or engine is unavailable, show me an available alternative. Use the finished audio to time the scenes.

Build a crisp pixel world with original geometry, a consistent palette and nearest-neighbor scaling. Use JavaScript/WebGL or another available code renderer. Move between the window, airplane, pressure diagram and metal panel so the viewer always knows what the narration is explaining. Use a generic unbranded aircraft. Keep labels short and aligned with the spoken explanation.

Add restrained sound effects and readable captions. Keep any licensed music below the voice. Render the finished MP4 and check the physics explanation, captions, timing and audio. Return the actual video plus the editable project. The goal is a finished animated explanation, not just an image sequence or a code sample.

Read the Higgsfield Viral Shorts skill before starting: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/71c01284-d883-484d-a21f-592f5740c740.md
```

### Full 3D (last person on Earth)

```
I'd like to make an original full-3D Short: "What If You Were the Last Person on Earth?" Use Higgsfield Viral Shorts for the workflow.

Aim for about 88 seconds, vertical 1080 × 1920. Make the character, objects and locations in 3D. Clearly frame the whole story as a thought experiment, with a small readable label at the start.

Open with one ordinary adult realizing the city is empty. At first it feels like freedom: an empty shop, a car they can take, no queues and no one telling them what to do. Then turn the question around. Owning everything doesn't mean you can keep it working.

Show the systems people normally maintain: electricity, water, communications and transport. Explain that reliability would change without operators and repairs, while the exact sequence depends on the system and location. Don't give invented countdowns or imply every power plant would explode.

Move from the practical problem to the human one. There is nobody to help when something breaks, nobody to share a meal with and nobody to call. End with the character setting a second place at a table or talking to an ordinary object. The payoff is that access to things doesn't replace other people.

Write original, natural English narration. Check claims about infrastructure and isolation before recording. Use the WHO overview for the limits of what we know about social connection: https://www.who.int/news-room/questions-and-answers/item/social-connection . Don't assign a fixed day when someone would hallucinate or become ill. Keep uncertainty in the wording and avoid medical advice.

Generate the voice first through Higgsfield. Find Arthur in the available ElevenLabs voices and use an expressive British delivery: curious at first, then more reflective. If the voice or engine is unavailable, show me an available alternative. Measure the audio and build the timeline from it.

Build original 3D geometry. Inspect any generated models from multiple angles. Use coherent lighting, materials and camera distance so objects stay readable on a phone. Favor clear mechanical demonstration over decorative detail.

Add licensed music and restrained sound. Keep captions readable. Render and check the finished MP4, including the ending. Return the video and the editable project.

Read the Higgsfield Viral Shorts skill before starting: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/71c01284-d883-484d-a21f-592f5740c740.md
```

## Step-by-Step Recreation Playbook (for an AI agent)

1. Read the attached Higgsfield_Viral_Shorts.md skill completely.
2. Confirm Higgsfield MCP is connected and list available voices and image models.
3. If the user supplied a script, lock it. Otherwise run the idea-generator prompt and wait for approval.
4. Record the narration first (Arthur or approved alternative). Measure its duration and word timings.
5. Build a shot list mapped to the audio timeline.
6. Generate only the assets the style needs (transparent costumes for 2D/3D hybrid, optional Meshy models). Draw expressions and simple limbs in code.
7. Implement the scene in the available renderer (Blender for 3D sets, WebGL for 8-bit). Keep characters grounded and faces readable.
8. Composite sound, captions, and music. Render a test still and a short moving clip before the full film.
9. Render the final vertical MP4. Inspect every shot for black frames, floating characters, unreadable text, and ending payoff.
10. Deliver the MP4 plus the editable project files, script, and captions. Do not publish unless explicitly asked.

## Key Learnings & Replication Notes

- Voice first locks the timeline and prevents wasted regeneration.
- Code renders the animation; image models only supply flat assets or references.
- Characters stay facing camera and use local coordinates on moving platforms so they do not slide.
- Fact-check primary sources and label hypotheticals. Do not invent quotes or claim measured simulations for illustrative diagrams.
- The skill is pure instructions. The agent must write its own project files and use only tools that exist in the environment.
- 50 ready scripts exist on the page but were marked private for some users; the skill can generate new ones.

## Raw Links

- Video: https://www.youtube.com/watch?v=GrFez9F0TF4
- Skill + prompts blog: https://higgsfield.ai/@adilinthewildtempo/blogs/how-to-make-viral-faceless-shorts-using-claude-code
- Skill MD: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/71c01284-d883-484d-a21f-592f5740c740.md
- Pricing / offer: https://higgsfield.ai/s/faceless-shorts-higgsfieldai-tBbqBO
- MCP: https://higgsfield.ai/s/faceless-shorts-higgsfieldai-DwyYVA
