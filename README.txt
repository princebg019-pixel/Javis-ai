JARVIS AI — Android phone web app

Included:
- index.html: assistant interface, chat, voice input/output, notes, settings
- manifest.webmanifest: installable PWA metadata
- sw.js: basic offline app-shell cache

IMPORTANT LIMITATIONS
- This is an installable web app (PWA), not a native APK.
- Full AI replies require a Gemini API key. Create/manage one at https://aistudio.google.com/app/apikey
- The API key is stored in browser local storage on this phone. Do not share the device/browser profile.
- Female voice selection is a preference only; the actual available voice depends on Android text-to-speech voices.
- Speech recognition requires browser support and internet; it may not work offline.
- It cannot run a permanent background wake word, read private messages, or control every Android setting.
- Keep Android/Chrome updated.

PUBLISH WITH GITHUB PAGES (one-time setup)
1. Sign in to https://github.com on your phone.
2. Create a new PUBLIC repository named jarvis-ai.
3. Upload index.html, manifest.webmanifest, and sw.js to the repository root.
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for GitHub Pages to publish. The address will be https://YOUR-GITHUB-USERNAME.github.io/jarvis-ai/
7. Open that address in Chrome on Android. Tap ⋮ > Install app (or Add to Home screen).

Use only HTTPS hosting for microphone and install support.
