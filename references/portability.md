# Portable use and repository packaging

Chosen repository: https://github.com/sananxrom/1cw-thumbnail-skill

The user approved publishing this reference pack to the public repository on 2026-09-24. Keep the asset pack with the skill so a fresh chat does not depend on the originating machine. Repository visibility can change; check actual access before offering remote retrieval as an available route.

## Folder layout and installation

Keep `SKILL.md`, `agents/`, `references/` and `assets/` together. All working links are relative; the old computer's absolute paths are not required. Git can version Markdown/prompts alongside this small curated image pack. Keep large PSD archives separate unless specifically needed. Do not add a software licence that purports to license guest photographs or other third-party assets without the owner's direction.

For Codex, place the entire `1cw-thumbnails` folder under the configured skills directory (commonly `~/.codex/skills/1cw-thumbnails`), then start a new chat/session and check skill discovery. Installation and discovery are environment-dependent. Invoke `$1cw-thumbnails` and provide the episode brief and guest portrait. If the environment has no skill discovery, explicitly point it at `SKILL.md`.

For ChatGPT, the Markdown is an instruction pack, not automatically an installed Codex skill. Provide `SKILL.md` and supporting reference documents in a project/chat, and make the actual identity/style images available as attachments. If ZIP extraction is supported, upload the full pack; otherwise upload the Markdown and core images separately. Ask it to follow the pack and use the available image-generation capability. Do not assume Markdown links make images accessible to its generator.

An ordinary new chat does not inherit the original conversation or automatically load this repository. Explicitly supply the pack or installed skill. A public repository link can help retrieve files when browsing is available; a private repository needs authenticated access or an attached/local copy. A link alone is not a guarantee of readable image access.

## Suggested fresh-chat request

> Use the attached/installed 1cw-thumbnails skill. Read SKILL.md and the linked design and asset references, and inspect Eddie's original portrait plus the XR and robot-arm thumbnails. My new episode is [title]. Here is the guest photograph and episode description: [context]. Propose concise thumbnail text and Eddie/guest/background direction first. Wait for my selection before rendering. Preserve the original faces and save the final PNG and exact prompt.

## Missing assets

First search inside the supplied pack or clone using the documented relative paths. If a repository is available, retrieve the actual image files through the environment's supported authenticated/public access method. Inspect them and ensure the generator can receive them. Do not pass an inaccessible GitHub HTML page or a Git LFS pointer as a portrait. If essential identity images cannot be accessed, ask the user to attach them; prepare concepts while waiting but do not substitute a new face.

## Maintaining the pack

Add approved examples deliberately rather than loading every output into each prompt. Keep source identity references stable. Save exact prompts with reference order and observed model/tool metadata. Record feedback as a general rule only when the user makes it general; preserve per-episode exceptions separately. Explicitly mark older conflicting prompts as historical. Version updates in Git, and avoid embedding tokens, local credentials or session-only file dependencies.

## Reproducibility limits

This is a documented creative process with visual references, not a fine-tuned model or deterministic rendering setup. Backend model changes can alter output. Exact seeds/model versions were not exposed by the original tool. Calibrate on a new example after changing generators. For exact fonts, final export dimensions or layered deliverables, use a separately agreed production step.
