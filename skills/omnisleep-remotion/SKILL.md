# OmniSleep Remotion Agent Skill

## Purpose
Produce short premium vertical product reels from approved original OmniSleep renders, preserving product geometry, fabric, mattress shape and construction. Do not redraw product images with generative AI.

## Inputs
- Model name, verified features and CTA
- 4–7 original renders (approved by product owner)
- Format 1080x1920, 30fps, 15 seconds
- Optional logo, music licensed for commercial use

## Workflow
1. Validate model and product facts against the approved catalog.
2. Choose hero shot, interior, close-up and functional detail. Do not invent product capabilities.
3. Copy originals to public/assets, update public/monica-air.json with asset paths and verified texts.
4. Render with Remotion: npm install && npm run render. Confirm MP4 opens and duration, frame dimensions and transitions.
5. Manually review every shot for geometry, textile texture, mattress and lifting mechanism fidelity, cropping and text safe zones.
6. Export MP4 and document the inputs, source files and review status.
7. Hermes integration: accept validated JSON only; do not expose API keys, customer data or credentials.

## Quality gates
- Never depict the lift mechanism as operating through fabricated intermediate frames.
- No claims of durability, orthopedic effects or load rating without evidence.
- Do not replace mattress or bed geometry.
- A static slideshow rendered with ffmpeg is a preview, not proof that Remotion executed.
- Require explicit editorial approval before posting to VK/Instagram.

## Status
Initial pilot assets provided in ChatGPT on 2026-11-16. Production Hermes source code and deployment configuration have not been inspected.