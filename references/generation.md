# Generation method and provenance

## What produced the latest approved examples

Anirban's “1,024 QUBITS / INDIA’S / NEXT LEAP?” and Adrian's “AI + BIOTECH / = GODMODE / SPECIES 2.0” used Codex's built-in `image_gen`, exposed as `image_gen__imagegen` in the originating session. The returned files were copied into the project. Neither used an external API call, fine-tuning, Photoshop compositing, separate typesetting or post-generation skin retouch.

Observed input arguments: `prompt` and `referenced_image_paths`. The call exposed no model selector/version, seed, sampler, quality setting or explicit size control. **The underlying image-model name/version is unknown.** Do not retrospectively label it GPT Image 1, 1.5, 2, DALL-E or another model. The conversational assistant was Codex; exact historical assistant versions across all turns are not documented and are not a reproducibility requirement.

Both latest renders requested 16:9 and returned **1672 × 941 PNG**, very close to but not mathematically exact 16:9. Dimensions were observed, not configured. Future environments may return other sizes. Do not claim exact 1280 × 720 unless verified. Preserve output unless resizing is requested or required for a specified delivery contract.

## Known reference order

- Adrian: original Eddie; original Adrian portrait; original XR thumbnail; original robotic-arm thumbnail.
- Anirban: original Eddie; original Anirban portrait; supplied quantum-room image; original XR thumbnail; original robotic-arm thumbnail.

Exact prompts are archived and latest PNGs bundled. Historic guest portraits/backgrounds are not all bundled; they are not needed for new episodes. An exact historic replay requires its source inputs as well as its prompt.

## Portable execution

1. Read the current tool schema; availability and argument names can change. Prefer built-in generation. No API key was needed in the original workflow.
2. Inspect sources visually. Supply original Eddie, new guest, usually original XR and robot-arm thumbnails, plus a supplied episode background if useful. Label every input's role and order. A recent output may calibrate layout; do not use its generated face as the sole identity reference.
3. Build one consolidated prompt from the approved brief and current design rules. Preserve exact text. Do not pass Markdown files as image inputs.
4. Render once and review. Save PNG, exact prompt and a record of actual reference order, exposed tool/model/settings, output dimensions and approval status. Unknown values stay unknown.
5. Use descriptive sibling versions: `guest-hook-v1.png`, `guest-hook-v1-prompt.txt`, `guest-hook-v1-record.json`. Preserve originals and approved files.

Built-in outputs originally appeared in the configured Codex generated-images directory. Copy from the returned path; never hard-code a historical session directory. If no image generator is available, provide a ready prompt and explain the blocker. Do not silently switch to a paid API or a different model. A changed workflow needs user agreement; an alternate model must be calibrated against the pack.

## Review and revision

Check exact text/symbols, Eddie identity, guest fidelity, head/torso balance, hand anatomy, props, centred headline, spacing/shear, background simplicity and skin. Assess small-view readability as well as full size.

For requested edits, state what changes and what stays. Repeated full-image edits can accumulate texture/identity drift. If faces degrade, return to original portraits and consolidate corrections, rather than sharpening damaged faces. Preserve approved text/layout when rebuilding. Stop when the brief is met; avoid speculative extra renders.

A PSD route is optional if requested. Original PSDs were inspected, but these outputs do not establish a tested automated editable-PSD pipeline.
