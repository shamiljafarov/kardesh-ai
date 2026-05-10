# Qardash AI

Cleaned version without the leaked OpenRouter API key in `index.html`.

## Setup

1. Revoke/delete the old OpenRouter key immediately.
2. Create a new OpenRouter API key.
3. Open `config.js` and paste the new key:

```js
window.OPENROUTER_API_KEY = 'YOUR_NEW_KEY';
```

4. Test locally by opening `index.html`.

## GitHub push

Because the old key was already committed before, start with clean git history:

```bash
rm -rf .git
git init
git add .
git commit -m "clean first commit"
git branch -M main
git remote add origin https://github.com/shamiljafarov/qardash-ai.git
git push -u origin main --force
```

Do not commit `config.js`.
