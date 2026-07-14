# Architecture

## Design principles

1. **Local-first:** Core functionality runs without a server.
2. **Progressive enhancement:** Optional AI features must not replace the offline workflow.
3. **Provider-neutral records:** Project data should remain useful when a music service changes.
4. **Transparent decisions:** Generated drafts remain editable and must not be presented as final creative authority.
5. **Privacy by default:** No project content is transmitted without an explicit user action.

## Current implementation

The initial release is a single static `index.html` containing HTML, CSS, and JavaScript. Browser local storage preserves the current project. JSON import/export provides portability.

## Data model

A project includes song metadata, creative direction, reference observations, prompt preferences, and an array of generation records. Each generation record contains model information, selected settings, three listening scores, a link or filename, notes, and a timestamp.

## Future API boundary

Any future API integration should be optional, isolated behind a clear user action, rate-limited, and documented. The application should send only the minimum fields required for the requested transformation.
