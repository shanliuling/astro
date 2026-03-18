---
'astro': patch
---

Fixes an issue where the server islands encryption key wasn't shared across Vite environments, causing props to be encrypted differently. Now Astro shares the same encryption key for all environments. 
