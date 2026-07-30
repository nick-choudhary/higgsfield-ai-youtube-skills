# PLAYBOOK: This is How I Made an Ultra Realistic AI Short Film Using Seedance 2.0 in 4K (Full Workflow)

**Source Video:** https://www.youtube.com/watch?v=0HIRIT7px9Y  
**Skill Page:** https://higgsfield.ai/s/santiago-higgsfieldai-vWYEeU  
**Skill File:** `seedance-clean_v2.skill` (application/zip)

## Final Result
An emotional short film (“Santiago”) about a footballer processing a missed penalty through therapy sessions and childhood flashbacks. Full director-level control: Dutch angles, 180° rule, whip pans, match cuts, emotion beats, and consistent characters across 4K Seedance generations.

## Skill Installation
1. Download `seedance-clean_v2.skill`
2. Claude → Customize → Skills → Upload
3. The skill splits scenes into shots and selects framing (close-ups, wides, etc.) like a DP.

## Complete Prompt Library (Key Examples)

### Global Style Lock (apply to every scene)
```
Style: 8K IMAX. Photorealistic — Documentary style. Cinematography: Emmanuel Lubezki × Roger Deakins. Color: 60:30:10 — dominant / secondary / accent. Camera: Physical cine lens. 180° shutter motion blur. Skin: Pore-level realism. Acting: Hollywood — micro-pauses, precise eye-line, living eyes with catch-lights. Physics: Gravity and inertia respected. Composition: Rule of thirds + golden ratio. Continuity: No identity drift. Technical: 24fps. Audio: environmental SFX + dialogue only. No music. No subtitles.
```

### Character & Location Sheets
Create grey-background reference sheets for:
- @santiago (25yo Spanish athlete)
- @psychologist
- @office (mid-century modern therapy room)
- @santiago-kit / @goalkeeper / @kid-santiago
- @stadium / @street-pitch / props (ball, kit, trophy)

### Example Scene Structure
Every scene prompt must include:
- References with 100% match locks
- Exact shot timings and hard cuts
- Camera FOV / angle / movement
- Positive locks for identity, wardrobe, blocking, and 180° line
- Diegetic audio only

(Full long-form scene prompts for therapy sessions, penalty miss, childhood flashback, and fan recognition are on the source page.)

## Step-by-Step Recreation Playbook (for an AI Agent)
1. Write the screenplay first (setup → rising action → climax → resolution) with shots ≤15 s.
2. Generate all character, location, and prop sheets on grey backgrounds.
3. Load the skill and feed each scene description.
4. Generate every shot in Seedance 2.0 4K using the style lock + positive locks.
5. Enforce the 180° rule and continuity across cuts.
6. Assemble with hard cuts and emotion beats intact.

## Key Learnings & Replication Notes
- Treat the AI like a camera department, not a magic prompt box.
- Emotion is written beat-by-beat, never via negative prompts.
- Dutch angles and canted frames are powerful for psychological tension.
- Reference sheets + positive locks are what make multi-scene films possible.

## Raw Links
- Skill + Prompts: https://higgsfield.ai/s/santiago-higgsfieldai-vWYEeU
