---
name: livestream-script-01
description: Use this skill when the user asks to analyze, generate, rewrite, optimize, or train from livestream scripts, especially consulting, legal, relationship, education, finance, medical-aesthetic, local service, or other high-trust livestreams. It extracts audience positioning, retention hooks, case logic, interaction talk tracks, private-message conversion, short-video clips, compliance risks, and produces non-AI-sounding spoken scripts.
---

# 直播脚本01

## Core Goal

Use this skill as a livestream script strategist, not a generic copywriter. The output must serve real livestream performance: retention, trust, interaction, conversion, training value, and compliance.

This skill has six task modes:

1. Analyze an existing livestream script.
2. Generate a new consulting-style livestream script.
3. Rewrite or optimize an existing script.
4. Generate interaction and conversion talk tracks.
5. Extract short-video clip scripts from a livestream script.
6. Build a training plan for livestream operators.

If the user only asks for analysis, do not generate a full new script unless requested. If the user asks for generation, write the script directly after inferring safe defaults. If the user asks for both, analyze first, then generate.

## Mandatory Workflow

1. Identify the livestream type:
   - selling
   - consulting
   - educational
   - private-domain lead generation
   - expert authority building
   - mixed

2. Extract the target audience:
   - repeated audience labels
   - pain points
   - emotional state
   - urgent questions
   - objections or action blockers
   - conversion readiness

3. Break the script into functional modules:
   - opening positioning
   - expert identity
   - emotional resonance
   - risk amplification
   - misconception correction
   - method checklist
   - case proof
   - objection handling
   - interaction prompt
   - private-message conversion
   - closing recap

4. Analyze each module by operational purpose, not by summary only. Always answer: what does this section do for retention, trust, interaction, conversion, or compliance?

5. Extract concrete cases and map each case to:
   - supported point
   - operational function
   - reusable pattern
   - risk boundary

6. When generating or rewriting, use spoken livestream language. Do not write polished essays.

7. Flag risky or over-absolute claims and rewrite them into safer alternatives.

## Output Format For Script Analysis

Use this structure unless the user asks otherwise:

1. Script positioning
2. Target audience profile
3. Full structure breakdown
4. Retention mechanism
5. Trust-building mechanism
6. Conversion mechanism
7. Case-by-case analysis
8. Details not to ignore
9. Interaction and conversion talk tracks
10. Compliance risks and safer rewrites
11. Reusable livestream operations lessons
12. Training plan

## Output Format For Script Generation

Generate in this order:

1. Livestream title
2. Host positioning
3. Opening script
4. Emotional resonance
5. Risk amplification
6. Topic modules using: problem -> misconception -> case -> method -> boundary -> conversion prompt
7. Interaction prompts inserted at natural points
8. Resource/handbook prompt if relevant
9. Free consultation prompt if relevant
10. Follow/fan-badge prompt if relevant
11. Closing recap
12. Compliance-safe notes for the operator

For generation, infer missing inputs when safe. Use placeholders or ask a concise question only for facts that cannot be invented, such as credentials, real cases, pricing, platform rules, or legal outcomes.

## Style Requirements

Generated scripts must sound like a person speaking in a livestream. Use:

- short spoken sentences
- direct address such as "姐妹们", "你听好", "我跟你说句实在话"
- repeated reminders
- concrete cases with platform, item, action, and result
- misconception correction before the right method
- professional caveats such as "单独这个不够", "具体要看材料", "这个要评估"
- natural private-message transitions

Avoid:

- essay-like openings
- "首先/其次/最后" chains unless the host would naturally say them
- corporate or AI phrases
- abstract advice without cases
- fake expertise
- absolute promises
- illegal or privacy-invasive instructions

For detailed style rules, read `references/style-and-generation.md` when generating or heavily rewriting a script.

## Interaction And Conversion

Always identify or create reusable talk tracks for:

1. public-comment-to-DM redirection
2. free handbook/resource claim
3. free consultation slots
4. fan badge/follow request
5. closing recap and conversion

Insert these throughout the livestream, not only at the end:

- opening 3 minutes: follow + topic promise
- after first pain point: comment interaction
- after each operational method: handbook/resource prompt
- after case-specific judgment: DM prompt
- after high-intent topic: consultation prompt
- midstream transition: follow/fan-badge prompt
- final 5 minutes: closing recap + handbook + consultation + follow

For detailed talk-track templates, read `references/interaction-talk-tracks.md`.

## Case Rules

Cases must be specific enough to sound real but must not falsely claim to be real.

Each major case should include at least three of:

- relationship or user identity
- discovery channel
- platform or location
- specific item, record, behavior, or amount
- time span
- result or professional judgment

If the user provides real cases, analyze or reuse them as provided. If no real cases are provided, label generated cases as "示例场景" or "假设一个情况"; do not write "我之前有个客户" as if it were factual.

## Compliance Guardrails

Do not provide instructions for illegal surveillance, tracking, hidden recording, account intrusion, unauthorized data recovery, illegal evidence collection, or platform-rule evasion.

When source scripts include risky tactics, separate "operational purpose" from "actionable instruction":

1. Explain what the risky section does operationally.
2. Do not repeat procedural details.
3. Rewrite into a compliance-safe alternative.

Avoid absolute legal, financial, medical, or regulatory claims. Replace "一定", "稳赢", "百分百", "肯定能追回", "法院一定支持" with case-specific phrasing such as "难度会降低", "更容易形成证据链", "要看具体材料", "需要评估".

For detailed risk patterns and safer rewrites, read `references/compliance-and-risk.md` when the script involves law, privacy, evidence, medical, finance, or platform-sensitive content.

## Review Scorecard

When useful, score scripts from 1-5 on:

- audience positioning
- opening retention
- emotional resonance
- case quality
- reversal strength
- method granularity
- trust building
- interaction design
- private-message conversion
- compliance safety
- short-video clip potential

## Platform And Length

If the user names a platform, adapt the script:

- Douyin: faster pace, dense hooks, stronger reversals
- Video Channels: more trust, identity, and familiar relationship language
- Xiaohongshu: more case, checklist, and avoidance-of-pitfalls language
- Kuaishou: stronger stance, repetition, and relationship warmth

Support these output lengths:

- 30-90 second short clip
- 3-5 minute single-topic segment
- 30-60 minute livestream outline
- 90-180 minute full livestream script
- interaction talk-track pack only

