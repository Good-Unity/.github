# Editor architecture guide

This file sets a standard for editor work in Good-Unity repositories.

## Rules
- Use one installation method.
- Keep config out of page components.
- Centralize plugins, toolbar, uploads, and styles.
- Keep migration notes when changing editor packages.

## Preferred layout
- src/editor/ckeditor.ts
- src/editor/config.ts
- src/editor/toolbar.ts
- src/editor/uploadAdapter.ts
- src/editor/styles.css
- src/editor/plugins/
- src/editor/README.md

## Migration sequence
1. Freeze current behavior.
2. Audit old imports and duplicated config.
3. Centralize editor code.
4. Replace old installation patterns.
5. Verify custom features.
6. Add tests and CI checks.

## Current state
No editor-specific implementation has been identified in Good-Unity repositories yet. This guide is the baseline for future work.
