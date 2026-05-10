# Qardash AI

Vercel-ready version.

## Deploy
1. Push this folder to GitHub.
2. Import repo in Vercel.
3. In Vercel → Project → Settings → Environment Variables add:

```txt
GROQ_API_KEY=your_groq_key
```

4. Redeploy.

API key is stored server-side in `/api/chat.js`, not in the browser.
