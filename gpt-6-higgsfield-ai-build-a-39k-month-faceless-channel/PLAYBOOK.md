# PLAYBOOK: GPT-6 + Higgsfield AI: Build a $39K/Month Faceless Channel

**Source Video:** https://www.youtube.com/watch?v=7SZ76s-nqpQ  
**Published:** 2026-09-04  
**Duration:** 7:28  
**Prompt pack / companion blog:** https://higgsfield.ai/s/faceless-channel-using-gpt-6-higgsfieldai-sPQEqd  
**MCP / ChatGPT plugin page:** https://higgsfield.ai/s/faceless-channel-using-gpt-6-higgsfieldai-PUrlDd  
**Companion blog title:** How to Build a $39K/Month Faceless Channel With GPT 6 Astra + Higgsfield AI (@adilinthewildtempo, Sep 4, 2026)

This is the GPT-6 Astra rebuild of the older Claude Fable 5 faceless-channel video (`wU_bmWb6bhg`). Do not mix the two prompt packs.

Skill files published on the blog (hosted by Higgsfield, not re-hosted here):

- `faceless-script-writer-SKILL.md` — educational explainers, documentary storytelling, true crime  
  https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/4be16712-6afe-43e6-9646-dc1807f84b84.md
- `faceless-video-prompts-SKILL.md` — Seedance 2.5 shot-prompt system  
  https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/36303f8b-2ce6-47f2-88c8-1be1d39c930e.md
- Thumbnail / CTR PDF (`Higgs-guide-main.pdf`)  
  https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/c3120d41-5e62-4c99-b68c-0085d6db9679.pdf

## Final Result

A packaged faceless YouTube video with no camera and no editing app:

1. Original researched script (not a template)
2. Higgsfield MCP generates the shots, voiceover, music, and cuts
3. Thumbnails for A/B tests, titles, description, tags
4. Two extra videos for the same channel
5. The whole loop saved as one skill / one command

Reference numbers from the video and blog (AdSense claims about a researched third-party channel, not a guarantee):

- Example channel: $39,500/month AdSense
- Stated RPM on that example: $31 per 1,000 views
- Author’s scaled math: 3 videos/week totaling 100,000 views/month at $31 RPM ≈ $3,100; at ~$10 RPM ≈ $1,000
- YPP bar named on screen: 1,000 subscribers and 4,000 watch hours
- Niches called out as highest-paying: finance, tech, education. The walkthrough uses edutainment because it stays watchable years later.

On-screen sample VO from the generated pyramid video:

> You have never really seen the Great Pyramid. Its smooth white shell was stripped long ago. What we stare at is the raw stone beneath. 4,000 years of records keep their wages and their daily bread. And yet, not one drawing of the building itself survives. Now, cosmic ray scans expose a void hidden in the core. The first new chamber found inside since medieval time.

## Skill Installation

### ChatGPT (what the video shows)

Official plugin path from Higgsfield docs:

1. Open the ChatGPT Plugins Directory, or go to https://higgsfield.ai/mcp?tab=chatgpt and click **Add Higgsfield plugin**.
2. Select **Add**.
3. Sign in to Higgsfield and authorize.
4. Start a new chat. Enable the Higgsfield tool or mention it in the request.

Video wording: open Higgsfield MCP & CLI, copy the install command, get redirected to ChatGPT, click install plugin, allow access. Setup is once, about two minutes.

Official limit: audio generation and the Website Building skill are **not** available in ChatGPT. Use higgsfield.ai or Claude for those. Generations through the plugin always spend credits. Unlimited on the Higgsfield web app does not carry over.

### Claude

1. Customize → Connectors → Add custom connector.
2. Name it `Higgsfield`.
3. Paste `https://mcp.higgsfield.ai/mcp`
4. Sign in.
5. Upload `faceless-script-writer-SKILL.md` and `faceless-video-prompts-SKILL.md` from the blog links above (Customize → Skills). Do not re-host the files.

### Claude Code / Codex / CLI

```
npm i -g @higgsfield/cli
npx skills add higgsfield-ai/skills
```

Then authenticate with the CLI. Docs: https://higgsfield.ai/cli — GitHub: https://github.com/higgsfield-ai/cli

Platform Faceless Content skill (also on https://higgsfield.ai/mcp / https://higgsfield.ai/skills):

```
Create a faceless video about a surprising historical fact with a strong hook, stylized visuals, voiceover, and subtitles.
```

Faceless Studio on the web (Aug 20, 2026 changelog): Education, History, Kids, Storytelling. Script → style (8 presets including Stickman Cartoon and Studio 3D) → voice. Separate product from this GPT-6 chat workflow.

## Complete Prompt Library

These are the user messages published in the Sep 4, 2026 video description, transcript, and companion blog. The two SKILL.md files contain the long internal rules. Load those files in the agent; do not invent replacements.

### 1. Niche research + original script

```
Analyze the top-performing faceless educational channels — their hooks, video structures, what patterns repeat across their most viral videos. Then write me a script for that niche: original research with real insights, a structure that isn't a template, nothing recycled. Pick a topic with strong search demand.
```

Blog note: attach / load the faceless prompt skill first so it fills in the details that stop generic scripts.

Swap the niche word for finance or tech if that is the channel. Script-writer skill niches: `explainer`, `documentary`, `crime`.

### 2. Generate the video from the script

```
Make a 3-minute video from this script using Higgsfield MCP. Original visuals in one consistent style, voiceover, music, edited cuts every few seconds. 1080p, faceless YouTube channel.
```

Blog behavior: MCP splits the script into clips, generates every shot in one style, matches VO and music, cuts automatically.

If ChatGPT refuses audio, generate picture on the plugin, then run voice and music on higgsfield.ai or Claude.

### 3. Package + two more videos

```
Put together the complete YouTube package: thumbnails, title options, description, tags. Then make 2 more videos — pick topics that would perform well for the same channel.
```

Blog thumbnail rule: high-CTR stills that force a click. One focal point readable on a phone. Title asks a question the thumbnail does not answer.

### 4. Published thumbnail prompt (pyramid / DECODED example)

```
Standalone YouTube-style video cover thumbnail, 16:9, generated from text only (no reference image). SCENE: three pyramid-like structures standing on a dark glossy reflective surface against a dark charcoal textured background with subtle film grain. OBJECT 1 — far left, tiny: a small pyramid built from colorful toy building blocks, bright primary colors, yellow/green/orange/blue/red/pink tiers, smooth matte plastic, soft reflections on the floor. OBJECT 2 — center: a medium pyramid made of small tan sandstone blocks, stepped design with horizontal tiers, rough weathered stone texture. OBJECT 3 — right, dominant: a large smooth-sided stone pyramid with a sharp apex, fine tan masonry grid pattern, lit by warm golden light on its left side and cool blue light on its right, a clean warm-cold split running down its edge, the dark floor reflecting both lights. COMPOSITION: dramatic low-angle hero shot — camera near the ground looking up, strong vertical perspective, the large smooth pyramid towering and dominant in the right half of the frame, the medium stepped pyramid behind it on the left, the tiny block pyramid far left in the background, clear scale progression from small to huge. TITLE: the bold white sans-serif word "DECODED" in the upper left corner, large and ultra-legible. ARROW: a glowing curved red arrow rising from the title and pointing up to the apex of the large pyramid. Absolutely no timestamps, no timecodes, no corner badges, no numbers anywhere. No watermark, no other text.
```

### 5. Save the loop as a skill (blog)

The blog’s last move: dump niche logic, script rules, generation settings, and packaging into one skill file. Next video is one command. Use the two published SKILL.md files plus your package prompt as that file. Do not invent a third skill body.

### 6. Faceless video-prompt system (from `faceless-video-prompts-SKILL.md`)

Trigger line published in the skill description:

```
make the prompts
```

or hand the script over and ask for a faceless / documentary / explainer shot or a 10-second block.

Standing audio line the skill puts in every Seedance prompt:

```
NO MUSIC. SFX ONLY — diegetic sound throughout; no score, no narration, no voices.
```

That line is for the raw clip. Music and VO are added in the edit / MCP package step.

FOV table from the same skill: 180° full sky · 107° overhead-wide · 84° wide · 63° environment · 47° normal · 29° short tele · 18° portrait compression · 12° long tele · 8° extreme detail.

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm the operator has a paid Higgsfield account and either ChatGPT with the Higgsfield plugin or Claude with `https://mcp.higgsfield.ai/mcp`.
2. Point them at the official SKILL.md URLs. Do not download binaries into this repo.
3. Load `faceless-script-writer` and `faceless-video-prompts` into the agent.
4. Ask them to pick one niche: finance, tech, or education (edutainment). Have them check RPM on VidIQ or equivalent for a live top channel in that niche. Do not invent RPM numbers.
5. Run Prompt 1. Demand a FACT CHECK list for every date, figure, and named claim. If a fact cannot be sourced, cut it.
6. Approve the script before spending video credits.
7. Run Prompt 2. Target 1080p. Expect MCP to split the script, generate shots, and assemble. If the ChatGPT plugin cannot do voice, move VO to the Higgsfield web app.
8. While that renders, run Prompt 3 and/or Prompt 4 for thumbnails. Generate at least two thumbnail variants.
9. Collect title options, description, tags, the master video, and the two extra videos into one folder.
10. Save the working chat as a reusable skill in Claude / Supercomputer so the next episode is one command.
11. Do not claim $39,500/month as the operator’s result. That figure is the researched example channel’s AdSense, not this workflow’s guaranteed output.

## Key Learnings & Replication Notes

- The upgrade vs the June 2026 Claude version is GPT-6 Astra plus the ChatGPT plugin, plus two named skills and a thumbnail PDF.
- YouTube’s stated kill list in the video: mass-produced, generic, repetitive, or manipulative content. The script prompt exists to stay off that list.
- Views on a new video are not gated by subscriber count. YPP still needs 1,000 subs and 4,000 watch hours.
- MCP through ChatGPT spends credits even if the web plan has Unlimited.
- `faceless-video-prompts` wants a new picture about every 2 seconds, FOV in degrees, WB in Kelvin, positive locks instead of “no people”, and no diagram shots from the video model (render charts in code and cut them in).
- `faceless-script-writer` writes the hook last, present-tense VO, a number every 30–60 seconds, and the title’s promised moment at ~70% runtime.
- True crime: public documented cases only. No invented quotes. Victims named only when already public.
- Faceless Studio on the Higgsfield site is a parallel product. This playbook is the GPT-6 + MCP chat path.

## Raw Links

- Video: https://www.youtube.com/watch?v=7SZ76s-nqpQ
- Skills + prompts + thumbnail guide: https://higgsfield.ai/s/faceless-channel-using-gpt-6-higgsfieldai-sPQEqd
- Install Higgsfield MCP in ChatGPT: https://higgsfield.ai/s/faceless-channel-using-gpt-6-higgsfieldai-PUrlDd
- Companion blog: https://higgsfield.ai/@adilinthewildtempo/blogs/how-to-build-a-39k-month-faceless-channel-with-gpt-6-astra-higgsfield-ai
- MCP hub: https://higgsfield.ai/mcp
- ChatGPT plugin tab: https://higgsfield.ai/mcp?tab=chatgpt
- Connect docs: https://higgsfield.ai/creator-hub/help-center/integrations/how-do-i-connect-higgsfield-to-ai-agent
- ChatGPT video-from-plugin blog: https://higgsfield.ai/blog/generate-ai-videos-from-chatgpt
- Script skill: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/4be16712-6afe-43e6-9646-dc1807f84b84.md
- Video-prompt skill: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/36303f8b-2ce6-47f2-88c8-1be1d39c930e.md
- Thumbnail PDF: https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/c3120d41-5e62-4c99-b68c-0085d6db9679.pdf
- Older Claude faceless video (already in this repo): https://www.youtube.com/watch?v=wU_bmWb6bhg
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai
