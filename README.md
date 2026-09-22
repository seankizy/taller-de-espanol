# Taller de Español

A personal Mexican-Spanish learning app for KAP work: Memrise-style spaced-repetition
vocabulary, verb conjugation drills, seven grammar lessons, a Pimsleur-style audio
practice mode, and daily goals with streaks and milestones.

One file, no build step, no server. Open `index.html` (or the GitHub Pages link)
and it just runs.

## Data & privacy

Everything you add — words, verb progress, streaks — is saved in this browser's
`localStorage`, on this device only. There's no account and nothing syncs between
devices. Clearing your browser data or using a different browser/phone starts fresh.

## Optional: AI-assisted add

The "Complete with Claude" buttons (auto-filling a new word's meaning/example, or
generating a verb's full conjugation table, or generating extra grammar exercises)
need an Anthropic API key. Get one at [console.anthropic.com](https://console.anthropic.com),
paste it into the **Agregar** tab, and it's saved locally in this browser only.
It is sent only to `api.anthropic.com`. Without a key, everything else in the app —
90 starter words, 21 fully conjugated verbs, and all 7 grammar lessons — still works.

**Security note:** because this key is typed into a static page with no server behind
it, it is visible to anyone who inspects this browser's network requests or storage.
That's fine for a personal tool only you use. Never commit an API key into this repo.
