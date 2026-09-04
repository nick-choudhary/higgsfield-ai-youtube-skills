# PLAYBOOK: Claude Fable 5.1 + Higgsfield AI = Insane Motion Graphics!

**Source Video:** https://www.youtube.com/watch?v=2OwMjg5As2g  
**Published:** 2026-09-02  
**Prompt pack / skill page:** https://higgsfield.ai/s/marketing-studio-motion-design-higgsfieldai-QzAGtQ  
**MCP install page:** https://higgsfield.ai/s/marketing-studio-motion-design-higgsfieldai-KeDAEy  
**Skill name (as published):** motion prompt skill — motion and text design for Marketing Studio

The companion blog is titled *I Built a $5K/Month Business With Claude Fable 5.1 + Higgsfield AI* (Adil, Sep 2, 2026). Full generated Marketing Studio prompts live in the embedded skill on that page. They are not pasted as raw downloadable `.skill` bytes. Do not invent them.

## Final Result

Six paid motion-design styles, all generated from Claude + Higgsfield MCP + Marketing Studio. No After Effects. Video claims people sell this work at $300/day. Author’s credit math for every style in the video, failed takes included: about $70 total (~1,800 credits, one evening), ~$5 per finished video.

| Style | Stated market rate | Who buys it |
|---|---|---|
| SaaS / launch videos | $500–$3,000 per 15s | Tech and SaaS |
| Motion graphics on real footage | $200–$500 per 60s | Creators, small businesses |
| Hypermotion product ads | Premium product work (the “look expensive” style) | Restaurants, cosmetics, physical brands |
| 3D real estate flythroughs | $2,000–$15,000 per minute (beginners list $500–$1,000 per property) | Developers selling units before the building exists |
| 2D explainers | $300–$800 to start (agencies quote $3,500–$12,000 / 4–8 weeks) | Apps, universities, online schools |
| Editorial explainers | $1,500–$4,000 per minute | YouTubers, podcasters, media, startups with data |

## Skill Installation

1. Open Claude (desktop or claude.ai) → Customize → Connectors → Add custom connector.
2. Name it `Higgsfield`.
3. Paste: `https://mcp.higgsfield.ai/mcp`
4. Sign in to your Higgsfield account when prompted.
5. Open the prompt pack: https://higgsfield.ai/s/marketing-studio-motion-design-higgsfieldai-QzAGtQ
6. Upload the **motion prompt skill** from that page into Claude Skills (Customize → Skills). The page describes it as the file that handles motion and text design so output matches professional software.
7. Optional check in Higgsfield itself: Marketing Studio → Video. The same presets (SaaS, Hypermotion, Motion Design, etc.) sit there. The workflow in the video drives them from Claude, not from the web UI.

CLI note from the MCP page: Claude Code / Codex users should use the Higgsfield CLI instead of the connector URL. Docs: https://higgsfield.ai/cli — GitHub: https://github.com/higgsfield-ai/cli

## Complete Prompt Library

These are the copyable user messages published in the video description, timestamps, companion blog, and transcript. Longer Marketing Studio generation prompts are produced by the skill after you send one of these. They were not published as standalone text on the public page.

### Setup / studio check

```
Open Higgsfield Marketing Studio and use the Video presets. Drive them from Claude with the motion prompt skill loaded.
```

### Type 1 — Launch video from a website URL

```
Write a launch video prompt and generate it from this client website URL: [PASTE URL]
Analyze the product, core benefits, and target audience. Use the SaaS / launch preset in Marketing Studio.
```

Blog behavior: drop the URL in chat. Marketing agents handle positioning. Marketing Studio picks the SaaS preset.

### Type 1 — Recreate a reference 1:1

```
Recreate this finished video 1:1. Reverse-engineer a Marketing Studio prompt that matches the motion, heavy text overlays, and reveal effects.
```

Attach the reference video.

Credit-saving step from the blog, before you spend video credits:

```
Generate a 9-frame storyboard first so I can approve layout and visuals. If something is off, fix it at the image stage, then use that frame as the video reference.
```

### Type 2 — Motion graphics on real footage

```
Upload this talking-head footage. Add dynamic motion graphics and camera moves. Use this script: [PASTE SCRIPT OR ASK CLAUDE TO WRITE ONE].
Build a design sheet first. Output the design sheet as HTML so fonts survive. I will pick a font, then generate.
```

Blog note: graphics should sync to spoken words. Camera moves can be invented by the model.

### Type 3 — Hypermotion from one message

```
I need a hyper-motion ad for this product. Attach the product photo. Pick the Hypermotion preset. Style: [expensive / minimal / bright].
```

No product photo? The blog says Claude can generate the product too.

Endcard lock (blog):

```
Lock the final frame to the attached END IMAGE reference.
```

Watch / exploded-product variant described on the page (no longer raw prompt published):

- Decompose a mechanical watch into an exploded diagram
- FPV fly between the layers
- Motion-tracked spec callouts
- Slam it back together

Same pattern works for cookware, wardrobe, any physical product.

### Type 4 — 3D real estate

```
Turn this static architectural render into a blueprint-to-reality launch film. One unbroken camera move. The drawing's own linework extrudes into photoreal archviz. Overlay price and square footage.
```

Attach the developer’s still render.

Transcript phrasing also used:

```
Generate a 3D real estate motion video with camera fly-throughs, interior reveals, and text overlays showing pricing and square footage.
```

### Type 5 — 2D explainer

```
Make a 2D explainer. Product/course: [NAME]. Audience: [WHO]. What must appear on screen: [LIST]. Write the Marketing Studio prompt and generate.
```

One published example direction: fuse Octane-grade 3D objects with flat vector characters. Separate example name on the page: **HiggsFit — Pure 2D Vector**.

### Type 6 — Editorial explainer

```
Create an editorial explainer. Topic: [TOPIC]. Use these numbers and facts: [PASTE DATA]. Nonstop text, numbers, and charts. Do not invent figures. Verify every number before rendering.
```

Or the research version from the transcript:

```
Research this topic, verify the facts, then generate the editorial explainer. Do not put an unverified number on screen.
```

### Market-research helper from the transcript

```
Analyze which tech and SaaS niches drop the biggest budgets on motion design based on recent spending data and 5-year projections. Examples to consider: fitness apps, AI automation platforms.
```

## Step-by-Step Recreation Playbook (for an AI Agent)

1. Confirm Higgsfield MCP is connected (`https://mcp.higgsfield.ai/mcp`) and the motion prompt skill from the QzAGtQ page is loaded in Claude.
2. Do not download or re-host the binary skill. Point the operator at the official page.
3. Build a three-video portfolio in one session. Pick three of the six styles. Suggested set: one launch video from a real URL, one hypermotion product ad, one 2D or editorial explainer.
4. For launch videos: paste a live website URL. Let the skill write the Marketing Studio prompt. Approve a 9-frame storyboard before video.
5. For reference recreations: attach the source video. Ask for 1:1 motion + text overlay match.
6. For footage overlays: attach a talking-head clip. Demand an HTML design sheet and font approval before render. Sync graphics to speech.
7. For hypermotion: attach product photo + optional endcard image. Set style (expensive / minimal / bright). Lock last frame to the endcard.
8. For real estate: attach one architectural still. One continuous camera move. Price and sqft as overlays.
9. For explainers: give product, audience, on-screen list. For editorial, supply or verify every number yourself.
10. Keep failed takes. Author’s published cost for the whole video set was ~1,800 credits / ~$70.
11. Client hunt as published:
    - Search freelance platforms for “motion graphics ad”
    - Find companies with public launch dates, make the video unsolicited, send it
    - Post the work; each clip is portfolio and outbound ad
12. Do not quote rates as guarantees. They are the numbers stated in the video and blog.

## Key Learnings & Replication Notes

- Claude writes. Marketing Studio renders. MCP is the pipe.
- The skill exists so you do not hand-write Marketing Studio prompts.
- Approve stills / 9-frame boards before video. That is the credit save.
- HTML design sheets keep fonts intact for brand work.
- Hypermotion last-frame lock needs an END IMAGE attachment.
- Editorial work dies on one bad number. Verify first.
- Real estate is the high-ticket niche in this video because developers have stills and no building to film.
- Description also links https://higgsfield.ai/s/general-higgsfieldai-IrjQir — that page is an older AI short-film prompt library (Adil cop film), not this motion-graphics pack. Use QzAGtQ for this workflow.

## Raw Links

- Video: https://www.youtube.com/watch?v=2OwMjg5As2g
- All prompts / companion blog / motion skill embed: https://higgsfield.ai/s/marketing-studio-motion-design-higgsfieldai-QzAGtQ
- Blog permalink: https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day
- Install Higgsfield MCP: https://higgsfield.ai/s/marketing-studio-motion-design-higgsfieldai-KeDAEy
- MCP connector URL: https://mcp.higgsfield.ai/mcp
- Description “full prompts + skill” link (different film library): https://higgsfield.ai/s/general-higgsfieldai-IrjQir
- Discord: https://discord.gg/higgsfield
- X: https://x.com/higgsfield_ai
- Instagram: https://www.instagram.com/higgsfield.ai
