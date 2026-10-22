# YTLite

Theos tweak for YouTube (Objective-C / Logos). Sources: `YTLite.x`, `Settings.x`, `Sideloading.x`, `YTNativeShare.x`, `Utils/`. Build with `make` (Theos).

## Working rules (token-saving)
- Read only the files you need; prefer Grep over reading whole `.x` files.
- Batch independent tool calls in one turn; avoid repeating the same edit.
- For multi-file changes, plan first, then implement.
- Do not connect/disconnect MCP servers or switch models mid-session; set them at the start.
- Run the build (`make`) to self-check before reporting back.
- Run `/compact` before taking a break, not after; use `/clear` between unrelated tasks.
