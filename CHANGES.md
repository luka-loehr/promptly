# Changes Made to Fork

This project is a fork of the original Gemini CLI by Google LLC, renamed to "Promptly" by @lukaloehr.

## Modifications Made

In accordance with the Apache License 2.0 Section 4(b), the following files have been modified:

### Package Names and Structure
- Main package renamed from `@google/gemini-cli` to `@lukaloehr/promptly`
- Core package renamed from `@google/gemini-cli-core` to `@lukaloehr/promptly-core`
- CLI package renamed from `@google/gemini-cli` to `@lukaloehr/promptly-cli`
- VSCode extension renamed from `gemini-cli-vscode-ide-companion` to `promptly-vscode-ide-companion`

### User-Facing Changes
- Binary renamed from `gemini` to `promptly`
- Bundle output renamed from `bundle/gemini.js` to `bundle/promptly.js`
- GEMINI.md renamed to PROMPTLY.md
- All user-facing strings updated to reference "Promptly" instead of "Gemini CLI"
- Documentation updated to use new package names

### Modified Files with Prominent Notices
The following files contain modification notices as required by Apache License 2.0:
- `/package.json`
- `/packages/cli/package.json`
- `/packages/core/package.json`
- `/packages/vscode-ide-companion/package.json`
- `/README.md`
- `/esbuild.config.js`
- `/scripts/create_alias.sh`
- Various UI component files in `/packages/cli/src/ui/`

### Import Updates
All imports have been updated from `@google/gemini-cli-core` to `@lukaloehr/promptly-core`

### Environment Variables
The following environment variables remain unchanged as they refer to the Google Gemini AI service:
- `GEMINI_API_KEY` - Still required for authentication with Google's Gemini API
- `GEMINI_MODEL` - Still used to specify which Gemini model to use
- Other Google/Gemini service-related variables remain unchanged

## Original Copyright

Original work Copyright 2025 Google LLC
Licensed under the Apache License, Version 2.0

## Attribution

This project is based on the excellent work by the Google Gemini team. All original functionality and architecture remain intact, with only naming changes applied for the fork.