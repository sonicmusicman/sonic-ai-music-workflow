# Sonic AI Music Workflow

A local-first, open-source workflow tool for independent musicians who use AI-assisted music services.

## What it does

- Turns loose song ideas into a structured production brief.
- Records reference-track observations without copying a specific artist's identity.
- Produces editable prompt drafts for Suno, Lyria, or general-purpose language models.
- Tracks generation settings, links, scores, listening problems, and next actions.
- Compares generated versions by melody, arrangement, and lyrics scores, then records problems and next actions.
- Preserves project data with browser local storage.
- Supports JSON import and export for project backups and Markdown export for song briefs.
- Works as a single HTML file with no account, installation, build step, server, or API required for its core features.

## Why this project exists

Independent musicians often lose time rebuilding the same brief, prompt, and listening notes for every generation. This project makes that process reproducible and reviewable while keeping the creator in control.

## Quick start

1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Fill in a song brief and reference analysis.
4. Generate an editable project blueprint or prompt draft.
5. Record each generated version and export the project as JSON.

## Privacy

The core application runs locally in the browser. Project data is stored in browser local storage unless the user explicitly exports it. It does not automatically upload the user's creative data. No analytics, remote database, or API calls are included in the core version.

## Scope

This repository does not generate audio itself. It organizes creative decisions and records outputs from external music-generation services. Optional AI-assisted features may be proposed later, but the offline workflow will remain usable without an OpenAI account.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md). Bug reports and feature requests are welcome through the issue templates.

## Security

Please report security concerns according to [SECURITY.md](SECURITY.md).

## License

MIT License. See [LICENSE](LICENSE).
