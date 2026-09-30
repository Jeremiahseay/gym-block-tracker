BLOCK TRACKER — CLOUD UPDATE

This update adds the cloud foundation for:
- account sign-in
- cloud workout history
- weekly review records
- automatic weekly review generation via a Supabase Edge Function

IMPORTANT:
1. Keep your Supabase secret/service-role key and OpenAI API key private.
2. Only the Supabase Project URL and client-side publishable key belong in config.js.
3. Keep your existing program.json, manifest.webmanifest, and sw.js from the working GitHub app.
4. Upload/replace only the files in this update package unless instructed otherwise.

The app still keeps a local copy for resilience; cloud sync is the long-term source of truth once configured.
