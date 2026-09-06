# PLAYBOOK: GPT-6 Astra + Higgsfield MCP Made This ENTIRE Video in One Chat

**Source Video:** https://www.youtube.com/watch?v=NuvA32_dmtg  
**Published:** 2026-09-06  
**Duration:** 11:07  
**Official link in the description:** Higgsfield MCP connection guide — https://higgsfield.ai/s/astra-6-higgsfieldai-SkClBI (resolves to the ChatGPT / MCP hub: https://higgsfield.ai/mcp)

This video is a talking-head YouTube tutorial built in one GPT-6 Astra chat with Higgsfield MCP. The host uses their own face and voice as references. Higgsfield generates the presenter clips. Motion graphics come from existing After Effects templates. The cut happens in DaVinci Resolve.

No separate `.skill` file or prompt pack was published for this video. Do not invent one. The only official resource in the description is the MCP connection guide.

## Final Result

A finished YouTube tutorial with:

1. Script and take plan written in the same GPT-6 Astra chat
2. AI talking-head footage generated through Higgsfield MCP from the host's own face and voice
3. Screen recordings / visual demos for the tool walkthrough
4. Motion graphics animated from existing After Effects templates, synced to narration
5. Assembly in DaVinci Resolve with music, sound design, levels, and a YouTube export
6. Comedy inserts that are also AI-generated from the same face/voice references

Chapters from the video (use these as the production order):

- 00:00 This entire video was made in one chat
- 00:58 Connect GPT-6 Astra and Higgsfield MCP
- 02:03 Write the production brief
- 03:21 Build the script and plan your takes
- 04:24 Generate an AI talking head from your own video
- 05:29 Check facial consistency, voice, and lip sync
- 06:32 Add visual demonstrations and screen recordings
- 07:32 Animate motion graphics in After Effects
- 08:11 Assemble the video in DaVinci Resolve
- 08:52 Audio levels, music, and sound design
- 09:36 Final quality checks and export
- 10:18 The complete AI video workflow

## Skill Installation

The description points at the MCP connection guide, not a downloadable skill. Install the connector once.

### ChatGPT plugin (what the linked page shows)

1. Open the ChatGPT Plugins Directory, or go to https://higgsfield.ai/mcp and click **Add Higgsfield plugin**.
2. Click **Add**.
3. Sign in to Higgsfield and authorize.
4. Start a new chat. Enable the Higgsfield tool or mention it.

Official limits from Higgsfield connect docs:

- Generations through the plugin always spend credits. Unlimited on higgsfield.ai does not carry over.
- Audio generation and the Website Building skill are not available in ChatGPT. Use higgsfield.ai or Claude for those.

ChatGPT plugin deep link published on the MCP page:  
https://chatgpt.com/plugins/plugin_asdk_app_6a3293e129088191abf0875820e839da?q=higgsfield

### Claude (official connect docs)

1. claude.ai or Claude Desktop → Settings → Connectors → Add custom connector.
2. Name it `Higgsfield`.
3. Paste `https://mcp.higgsfield.ai/mcp`
4. Connect, sign in, authorize.
5. Confirm Higgsfield appears in active connectors.

Same credit rule: every MCP generation deducts credits.

### Claude Code / Codex / CLI

Send this setup message to the coding agent (wording from Higgsfield connect docs):

```
Set up Higgsfield for me so I can generate images and videos from here. 1. Install the CLI: run npm i -g @higgsfield/cli . 2. Authenticate: run higgsfield auth login and complete the sign-in in the browser it opens. 3. Install the companion skills: run npx skills add higgsfield-ai/skills . Once that's done, let me know when it's ready.
```

Docs: https://higgsfield.ai/cli  
GitHub: https://github.com/higgsfield-ai/cli

## Complete Prompt Library

This video did not publish a long prompt pack. Below are the only copyable requests that are actually public for this workflow: reconstruction of the production brief from the description/chapter list, plus example requests printed on the linked MCP page. Anything else would be invented.

### 1. Production brief (from the video description + chapter list)

Use this as the first message in a GPT-6 Astra chat that already has Higgsfield MCP connected. Swap the topic, length, and references for the operator's project.

```
Make this entire YouTube video in one chat using Higgsfield MCP.

Deliverable: an 11-minute YouTube tutorial, 16:9.

Use my own face and my own voice as references for the presenter and any comedy inserts. Generate the talking-head footage in Higgsfield. I will animate existing After Effects templates for motion graphics and assemble the cut in DaVinci Resolve.

Work in this order:
1. Confirm Higgsfield MCP is connected.
2. Write a production brief.
3. Write the script and plan the takes.
4. Generate the AI talking head from my reference video.
5. Check facial consistency, voice, and lip sync before spending more credits.
6. List the visual demonstrations and screen recordings I still need to capture.
7. Note which motion-graphics beats should be synced to narration in After Effects.
8. Give me an assembly order for DaVinci Resolve, plus audio-level, music, and sound-design notes.
9. Give me a final QC checklist and export settings for YouTube.

Do not skip the review step after the talking-head generates. The presenter clips and comedy clips must stay on my face and voice.
```

### 2. Talking-head generation request (description wording)

After the script is approved:

```
Generate an AI talking head from my own video reference. Keep my face and voice. Check facial consistency, voice, and lip sync on every take before you generate the next one.
```

### 3. Example requests printed on the linked MCP page

These are platform examples, not lines spoken in the video. Use them only as MCP smoke tests after install.

```
Use @Higgsfield with Nano Banana 2 Pro to create a realistic UGC-style product image with natural lighting and an authentic social media look
```

```
Create an 8-second 9:16 talking-head short about replacing light bulbs with a warmer color temperature to make a room look more expensive. Use a clean blue backdrop, bold animated captions, punchy zooms and reframing, selection-box and cursor graphics, and playful pixel-style icons
```

```
Turn this green handbag ad into three campaign-ready variations. Refresh the talent, wardrobe, and upscale home setting while keeping the bag design, product-focused motion, framing, timing, and audio consistent
```

```
Create an editorial motion graphics faceless video about how the Mona Lisa became the world's most famous painting
```

```
Create a stickman cartoon faceless video showing Odysseus's journey to Troy and back home
```

```
Create a complete UGC flow for this tumbler using the attached creator, from concept and script to a finished 9:16 video
```

```
Create a faceless video about a surprising historical fact with a strong hook, stylized visuals, voiceover, and subtitles
```

### 4. Related published talking-head prompts (different source — do not treat as this video)

Higgsfield's Aug 11, 2026 blog "How To Create a Talking AI Avatar in Claude with Higgsfield MCP" has full start-frame and Seedance prompts for a fictional presenter. That is a different workflow (Soul 2.0 + Soul ID + Seed Audio + Seedance 2.5, no After Effects / Resolve finish). Link only:

https://higgsfield.ai/blog/talking-ai-avatar-inside-claude

Do not paste those prompts into this playbook as if they came from `NuvA32_dmtg`.

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm a paid Higgsfield account and one connected agent: ChatGPT plugin, Claude MCP at `https://mcp.higgsfield.ai/mcp`, or Higgsfield CLI.
2. Open https://higgsfield.ai/s/astra-6-higgsfieldai-SkClBI and finish the install for the agent in use.
3. Collect the operator's reference: a clear talking-head video of their face plus a voice sample. The video states the presenter and comedy clips use the host's own face and voice.
4. Run Prompt 1. Stop after the brief and script. Do not generate video until the operator signs off on the script and take list.
5. Run Prompt 2. Generate one talking-head take first.
6. Review that take for face match, voice match, and lip sync. Discard and regenerate only the failed take.
7. Capture real screen recordings for any UI walkthrough. The video treats those as separate from the generated presenter footage.
8. Build motion graphics in After Effects from existing templates. Sync the graphics to the approved narration, not the other way around.
9. Assemble in DaVinci Resolve in chapter order: talking head, demos, graphics, comedy inserts.
10. Set dialogue first, then music and SFX under it. Export for YouTube.
11. Run a last pass: face drift, lip-sync slips, graphics off the beat, clipped audio, missing end card.
12. Do not claim the whole video was generated inside Higgsfield. The published workflow still uses After Effects and DaVinci Resolve for graphics and the cut.

## Key Learnings & Replication Notes

- "One chat" here means GPT-6 Astra plans and drives Higgsfield MCP from a single thread. It does not mean After Effects and Resolve disappear.
- The only description link is the MCP install page. There is no published SKILL.md for this title.
- Face and voice references are the consistency lock. Without them the talking head is a random presenter.
- Review lip sync and face match before burning credits on the rest of the take list.
- ChatGPT plugin cannot generate audio. If the operator is on ChatGPT, generate picture there and do voice on higgsfield.ai or Claude.
- MCP always spends credits.
- Comedy clips in this video are the same pipeline as the presenter clips: same face, same voice, different performance.
- Do not mix this playbook with the Sept 4 faceless-channel pack (`7SZ76s-nqpQ`). That one is script + faceless B-roll. This one is an on-camera AI presenter plus a traditional edit.

## Raw Links

- Video: https://www.youtube.com/watch?v=NuvA32_dmtg
- MCP connection guide from the description: https://higgsfield.ai/s/astra-6-higgsfieldai-SkClBI
- MCP hub: https://higgsfield.ai/mcp
- ChatGPT plugin: https://chatgpt.com/plugins/plugin_asdk_app_6a3293e129088191abf0875820e839da?q=higgsfield
- Connect docs: https://higgsfield.ai/creator-hub/help-center/integrations/how-do-i-connect-higgsfield-to-ai-agent
- CLI docs: https://higgsfield.ai/cli
- CLI GitHub: https://github.com/higgsfield-ai/cli
- Related talking-avatar blog (not this video): https://higgsfield.ai/blog/talking-ai-avatar-inside-claude
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
