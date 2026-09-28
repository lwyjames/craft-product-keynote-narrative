---
name: craft-product-keynote-narrative
description: Turn a product feature, approved UX flow, or group of features into a Chinese product-launch keynote narrative, pain-point setup, slide headlines and concise copy, demo beats, and spoken speaker notes. Use for keynote story structure, value pillars, one-slide launches, tagline exploration, talk-track rewrites, and speech-duration calibration. Hand off approved copy to presentation production when requested; this skill does not render slides or videos by itself.
---

# Product keynote narrative and speaker notes

Shape a story an audience can follow once, while the presenter speaks and the product demo runs. Preserve what the product actually does. Use the user's currently approved product brief, UX flow, and project decisions; never silently resurrect an abandoned feature or a superseded asset.

## Establish the assignment

1. Identify audience, announcement purpose, allocated slides/time, stage of work, approved source materials, prohibited claims, and the immediate deliverable. Treat launch requirements as user-provided inputs, including requirements already supplied in the conversation or project. Organize them without inventing requirements on the user's behalf. Label any suggested defaults as proposals or assumptions, not confirmed requirements; ask only when a missing choice would materially change the claim or demo. Search project context when an earlier decision is relevant, then prioritize the latest approved material.
2. Distinguish a verified product capability from a proposed idea, a launch promise, and an inference. Keep the distinction visible in the working notes. Do not invent integration, availability, performance, privacy, or compatibility claims.
3. Respect the requested stage. If the user says to discuss direction without images/slides, deliver text only. If the user asks for a single page, build one focused page; do not expand it into an unsolicited deck. If the user asks for multiple pages, set one audience takeaway and one main visual/demo action per page.
4. Honor the latest source restrictions, approved wording, exclusions, audience, product naming, and asset version. Project-specific details are not global defaults.

## Deliver and maintain the launch narrative

When the user enters the product-launch workflow (requests preparation or revision of the launch narrative), actually create or update and deliver **`发布叙事.md`**. Do not stop at a chat-only outline, promise to create it later, or label it approved merely because it is ready for review. For standalone tagline exploration, direction discussion, or an isolated talk-track rewrite outside that workflow, retain the requested lightweight text output.

- Use the user's launch requirements and latest approved product/UX material as inputs. Record the source of requirements; distinguish user-confirmed inputs, proposed choices, assumptions, and missing information. Never list an AI-generated “发布需求” as a required upstream deliverable from the user or replace the user's brief with invented requirements.
- Include the launch goal and audience, scope and page/time budget, source materials and constraints, central message and value hierarchy, ordered pages/beats with headlines and screen copy, demo/visual actions, complete speaker notes, transitions, and timing assumptions or calibration as applicable to the requested scope. Mark unknowns as pending instead of fabricating product facts.
- Keep the exact filename **`发布叙事.md`** throughout draft, revision, and approval. Update the same project artifact; do not create suffix variants such as `发布叙事_草稿.md`, `发布叙事_v2.md`, or `发布叙事_批准版.md`. Track revision and approval inside the document; use separate project folders for unrelated projects.
- Put a short status block at the top: `状态：草稿 / 修订待确认 / 批准版`, `修订：…`, `用户批准记录：未批准 / 用户的明确批准表述及对应修订`. Start with 草稿; use 修订待确认 after content revisions. Mark **批准版 only after the user explicitly approves that specific current narrative**. Approval of a UX design, a general direction, permission to continue, silence, or the agent's own quality check does not approve the narrative. Preserve already-given explicit approval when it unambiguously covers the current revision; do not ask again.
- If narrative content changes after approval, return the current status to 修订待确认 and retain the previous approval as historical, scoped to its earlier revision. Do not carry approval forward to changed claims or copy. When approved, update the status in the same file and deliver that file again.
- Save the actual Markdown artifact through the available persistent file workflow and provide its file link. If an artifact already exists, read and revise its current contents rather than reconstructing it from memory. If saving fails, state that delivery is incomplete; do not claim the file was delivered. An explicit user instruction to provide chat text only overrides file delivery for that request.
- Hand the current `发布叙事.md` to downstream presentation production when requested, with its status and unresolved items visible. Present only an explicitly approved revision as approved copy. Keep optional storyboard governance separate.

## Find the story

1. State the concrete situation the audience recognizes, the friction it causes, the product's distinct intervention, the visible proof, and the benefit after use. Avoid invented statistics, melodramatic scenes, and generic claims such as “more intelligent and convenient.”
2. Choose a message hierarchy: whole-section promise → pillar or feature promise → page takeaway → supporting facts. A feature's name, tagline, pain-point headline, and slide title have different jobs; do not force the same phrase into all four.
3. Choose the grouping principle that best clarifies value: user persona, journey, work mode, or problem family. Avoid making the user wade through an inventory of unrelated capabilities. If an established hierarchy exists, revise within it unless the user asks to restructure.
4. Identify one hero moment that can be shown or clearly described. Compare before/after only where the difference is accurate and meaningful. Make the demo action prove the headline. Explain why the experience belongs at the system level only when that claim is supported.
5. When collaborating with external hardware or apps, explain the user-visible handoff and ownership clearly; do not replace a benefit with architecture jargon.

## Write each page or beat

Use a compact working map: **audience takeaway | slide headline | on-screen words | demo/visual beat | spoken note | duration**. Include only requested columns in the final answer, but maintain alignment between them. A pain-point page should establish the tension without prematurely presenting the full solution. A reveal page should show the change plainly. A proof page should let the UX or demo carry the claim.

- Keep on-screen copy sparse and legible in one glance. Use natural simplified Chinese unless the user requests another language. Treat proposed taglines as options until one is approved.
- Write speaker notes to be spoken aloud: conversational, warm, concrete, and paced for the image or demo. Do not read the screen verbatim or recite an implementation spec. Prefer the user's established names, such as 小艺 for the assistant when applicable. Replace jargon with user outcomes; retain technical terms only when the audience needs them.
- Give a visual or illustration brief only when requested. Specify subject, action, eyeline, device orientation, focal point, unused space for text, and continuity with approved UX. Use actual assets and device rules when visual generation starts; this skill does not replace HarmonyOS UX Defaults.
- Keep an approved design aesthetic and product facts when revising an existing slide. Change the smallest relevant set of elements unless the user asks for a new direction.

## Calibrate talk time

Read [timing-and-delivery.md](references/timing-and-delivery.md) whenever the user supplies a target duration, an actual recording/read time, or a slide-by-slide timing budget. Use the user's measured speaking rate when available; treat an unmeasured estimate as provisional. Count demonstration and intentional pause time separately from spoken time. Tighten ideas rather than merely deleting connective words. Recalculate after each material rewrite.

## Check the result

- For each page, test whether an audience can answer: what problem, what changed, and what did I see as proof? Across pages, remove repeated explanatory paragraphs while allowing purposeful repetition of a short theme or title.
- Check that every spoken claim has support in the source and is consistent with the visible screen. Verify that the promised action can be demonstrated at the allocated time.
- For revisions, create a brief issue-to-fix checklist and verify every requested change against the new copy or artifact. Do not claim a timing target was met through a rough estimate if the user supplied an actual read time.
- When the user approves a product-launch narrative and asks for slides, hand the approved page map, copy, demo beats, and timing to the Presentations skill. Keep the original slide file and visual direction when revising. Do not introduce a storyboard manifest as a routine requirement. If the user explicitly supplies a governed storyboard or requests stable slide IDs and PPT alignment, use `presentation-storyboard-governance` for that separate governance task.

## Typical outputs

- **Launch workflow:** the actual `发布叙事.md` file, maintained under the same filename with an accurate draft, revision, or explicitly approved status.

- **Direction only:** 1–3 story directions with a recommended choice and rationale; no visual production unless requested.
- **One page:** headline, minimal on-screen text, visual/demo brief, complete spoken note, and estimated or calibrated duration.
- **Section:** ordered page map, transition sentences, total time, and any claim or asset that still needs confirmation.
- **Rewrite:** revised text and the requested changes actually applied, preserving unaffected approved content.
