# PLAYBOOK: How to Build a Faceless Channel YouTube Won't Demonetize (Claude Fable 5.2)

**Source Video:** https://www.youtube.com/watch?v=YP8D2_j3_Hc  
**Published:** 2026-11-11  
**Skills & Prompts Page:** https://higgsfield.ai/s/faceless-channel-fable-5-2-higgsfieldai-oVZiqR  
**MCP Page:** https://higgsfield.ai/s/faceless-channel-fable-5-2-higgsfieldai-zffqvC  
**Companion Blog:** https://higgsfield.ai/@adilinthewildtempo/blogs/how-to-create-a-faceless-youtube-channel-with-ai

## Final Result

A complete faceless English science documentary channel system:

- Original researched 5-minute "What if..." script with storyboard
- Full 1080p video generated and edited via Higgsfield MCP + Seedance 2.5
- Consistent photorealistic style, natural documentary voice, motion graphics, and sound
- Three thumbnail/title pairs, description, and tags
- Additional videos and Shorts from the same pipeline
- Monetization-safe original content (not mass-produced templates)

Example outcome shown: a finished ~4:33 "What If Apophis Hit Earth?" documentary.

## Skill Installation

Download these four Markdown skills from the blog/page (hosted by Higgsfield; do not re-host binaries):

- higgsfield-faceless-script.md — researches topics and writes scripts with storyboards
- higgsfield-seedance-prompts.md — writes generation prompts (camera, lighting, action)
- higgsfield-faceless-production.md — generates video, voiceover, music, SFX, graphics, and edits via Higgsfield
- higgsfield-youtube-packaging.md — creates thumbnails, titles, description, and tags

Also attach the Thumbnail Guide PDF when packaging.

**MCP setup:**
1. In Claude: Settings → Connectors → Add
2. Paste `https://mcp.higgsfield.ai/mcp`
3. Sign in to your Higgsfield account

Attach the relevant skill files to the chat before sending prompts. Files stay attached in the same conversation.

## Complete Prompt Library

### Topic Research
```
Use higgsfield-faceless-script. Research three topics for an original five-minute English “What if…” science documentary. Check recurring interest across YouTube over the past five years, recent successful videos, and relevant examples in Higgsfield Content Factory. Read accessible audience comments for unanswered questions. For each topic, give me a clear viewer question, one visual hook, the scientific payoff and direct evidence links with dates and visible metrics. Separate verified evidence from guesses. Recommend one. Do not generate media yet.
```

### Script Writing
```
Use higgsfield-faceless-script. Write a roughly five-minute English “What if…” documentary about a hypothetical Apophis impact. Verify the science and make the hypothetical premise unmistakable. Research relevant questions and accessible audience comments before writing.

Use hook, intro, body, recap and outro. Open with the impact, then rewind to explain the asteroid, the sequence of consequences, what changes at different distances, and how early detection could change the outcome. Give each section a question and a payoff. Include a storyboard with narration, visual action, graphics and sound cues. Use faster visual changes in the opening minute, then let clear explanations breathe. Flag any uncertain numbers for review.
```

### Full Video Production (main recreation prompt)
```
Use the attached Higgsfield Faceless Script, Higgsfield Faceless Production, and Higgsfield Seedance Prompts skills to recreate the documentary below as one finished video through the connected Higgsfield MCP.

Generate and edit the actual media in Higgsfield. Use Seedance 2.5 for the video shots at 1080p, 16:9. Use the connected Higgsfield image and audio tools for references, narration, music and sound effects. Deliver a downloadable 1920 × 1080 MP4 with the full edit and mixed audio; do not stop at a script, an HTML animation, a storyboard or a set of separate clips. If a required Higgsfield tool or model is unavailable, say which one is missing before substituting anything.

VISUAL DIRECTION
Photorealistic science documentary: believable scale, physically coherent action, natural lighting, restrained color and detailed environments. Start with an asteroid approaching Earth and reach the impact within the opening ten seconds. Keep one consistent asteroid shape, one consistent city and the same people across related shots. Generate and reuse reference images before the video shots. Show a compact moodboard and storyboard first, then produce the shots and assemble the complete film. Use varied shot lengths, with faster changes in the opening minute and longer takes when an explanation needs room. Use the fixed truck/garage escape scene, with clear screen direction and coherent movement.

NARRATION AND SOUND
Use one natural adult documentary voice: calm, curious and clear. The reference project used Max through ElevenLabs; use that voice if it is available through the connected tools, otherwise ask me to select an available replacement. Give numbers room to land and align the explanation with the shot. Build tension into the hypothetical impact, pull the music back for the rewind and explanation, then resolve the score during the safe flyby. Add localized impact, debris, glass, traffic and room sounds where the scene calls for them; keep the narration intelligible. Do not put an effect on every cut.

EDIT AND GRAPHICS
Build motion graphics and readable contextual labels for size, speed, energy, distance, elapsed time and orbital deflection. Time each label to the sentence that explains it. Keep graphic text out of the generated footage and composite it in the edit. Use a visible HYPOTHETICAL SCENARIO label for the imagined impact and REAL 2029 FLYBY for the safe encounter. Keep those two timelines unmistakably separate. All footage and illustrations should be original or properly licensed.

Check the science before generating. The real Apophis encounter is a safe flyby. Treat the impact speed, energy, crater size and damage zones below as scenario assumptions and estimates, not as an actual forecast; if a number is unsupported, flag it and use a supported explanation. Preserve the hook, rewind, personal consequences, planetary-defense payoff and intact-city ending.

Use this complete script and visual plan:

# What If Apophis Hit Earth?

Target runtime: approximately 4 minutes 33 seconds. Use varied shot lengths that fit the narration.

## 01 · HOOK & INTRO · 0:00–0:55.25

What if Apophis hit Earth on April 13th, 2029? A hundred kilometers away, the light arrives first. Everything else is still on its way.

**Scene dialogue:** “…get in the car! Leave it!”

Okay, let's rewind.

To be clear, the real Apophis will miss us. NASA has ruled out any impact for at least the next hundred years. But in this scenario, it doesn't miss.

**Visual direction:** Open on Apophis, accelerate into the impact, then stay with people in its path. Reverse the disaster at 0:36.50. Reveal the real safe flyby at 0:39.83, then return to the hypothetical question.

[Continue with the full body sections as provided in the source page for size/speed/energy, impact & city, etc., through the ending.]
```

### Batch Two More Videos
```
Use the attached Higgsfield Faceless Script, Higgsfield Faceless Production and Higgsfield Seedance Prompts skills to make two more complete five-minute science documentaries through Higgsfield MCP:

1. What if Earth’s oceans vanished? Open on an enormous cargo ship stranded on the exposed seabed. Establish the emptied harbor, the scale of the missing water and the effect on marine life. Build the explanation around the consequences for life, weather and the water cycle.

2. What if the Moon broke apart? Open with the Moon above Earth, then a visible fracture and fragments lifting away. Explain how the outcome depends on the size, speed and orbits of the fragments, then explore debris and tides. Do not present a stable ring or inevitable impacts as the only possible outcome.

Research each topic separately, check the science and clearly label each premise as a thought experiment. Use the same realistic visual direction and the same narrator voice as our first documentary, but write a new hook, story and ending for each topic. Structure each as hook, intro, body, recap and outro. Make the first minute visually active, then let the shot length follow the explanation.

Create a moodboard and storyboard for each. Use Seedance 2.5 at 1080p, 16:9 for the video shots; generate the references, voiceover, music and sound effects through connected Higgsfield tools. Add contextual motion graphics, then edit and export two separate finished 1920 × 1080 MP4s. Return the actual videos, not just the scripts, image boards or a browser animation. If the required Higgsfield tools are unavailable, tell me before choosing another route.
```

### Packaging (Thumbnails + Titles)
```
Use higgsfield-youtube-packaging and the attached Higgsfield Thumbnail Frameworks guide (Guide Claude.pdf). Package our finished “What If Apophis Hit Earth?” documentary for YouTube. The film explores a hypothetical impact, then explains the real safe flyby.

Create three distinct thumbnail/title pairs using frameworks from the guide: the moment before impact, the contrast between near and far, and the question of stopping the asteroid. Keep the hypothetical framing clear. Each thumbnail needs one strong focal point, a moment frozen in action and no more than four or five words. The title should add to the image, not repeat its text.

Generate all three actual thumbnail images through connected Higgsfield image tools in 16:9. Do not substitute an HTML mockup or stop at image prompts. Check spelling and readability at phone size. Return each generated image with its paired title, an accurate video description and a relevant tag list within 500 characters. If a required Higgsfield tool is unavailable, tell me before substituting another route.
```

(Additional recreation prompts for ocean and moon documentaries follow the same pattern of inspecting a reference video, extracting structure, then regenerating originally.)

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm the user has a Higgsfield account and Claude with MCP connected to `https://mcp.higgsfield.ai/mcp`.
2. Direct them to download the four skill Markdown files and Thumbnail Guide from the official page. Do not download or store the files here.
3. Attach `higgsfield-faceless-script.md` and run the Topic Research prompt. Select the recommended topic.
4. Continue in the same chat (or re-attach the skill) and run the Script Writing prompt.
5. Attach the Script, Seedance Prompts, and Production skills. Run the Full Video Production prompt (or the equivalent recreation prompt). Wait for the finished MP4.
6. Attach the Packaging skill and Thumbnail Guide. Run the Packaging prompt. Collect three thumbnail/title pairs, description, and tags.
7. Optionally run the batch prompt for two more videos, or the Shorts extraction prompt.
8. Upload the video to YouTube, select AI disclosure, and apply the winning thumbnail after testing.

## Key Learnings & Replication Notes

- Original scripts with real research and clear hypothetical framing avoid YouTube's inauthentic-content rules. Mass-produced templates do not.
- Science/education niches have strong evergreen interest and solid RPM.
- Consistent visual style, narrator voice, and motion graphics that match the narration keep retention high.
- Faster cuts in the first minute, then longer explanatory takes.
- Generate references first, then video shots. Inspect finished reference videos when recreating similar ones.
- One chat + attached skills turns the pipeline into a repeatable system.
- Disclose realistic AI content honestly; disclosure itself does not demonetize.

## Raw Links

- Video: https://www.youtube.com/watch?v=YP8D2_j3_Hc
- All skills & prompts: https://higgsfield.ai/s/faceless-channel-fable-5-2-higgsfieldai-oVZiqR
- Higgsfield MCP: https://higgsfield.ai/s/faceless-channel-fable-5-2-higgsfieldai-zffqvC
- Instant extension: https://higgsfield.ai/s/faceless-channel-fable-5-2-higgsfieldai-geRJqI
- Companion blog: https://higgsfield.ai/@adilinthewildtempo/blogs/how-to-create-a-faceless-youtube-channel-with-ai
- MCP connector: https://mcp.higgsfield.ai/mcp
- Discord: https://discord.gg/higgsfield
