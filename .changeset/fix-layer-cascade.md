---
"@drop-in/graffiti": patch
---

Fix CSS cascade layers - wrap base styles in @layer base so utilities can properly override element defaults (fixes .circle not working on buttons)
