# Scott-1

Scott 1 4 ever

This workspace contains a static prototype page `index.html` for the "Scott 1 National Team" demo.

Quick preview

```bash
cd /workspaces/Scott-1
python3 -m http.server 8000
# open http://localhost:8000
```

Notes

- User accounts and the admin code (`UncJohn`) are stored client-side in `localStorage` for demo purposes only — this is insecure.
- To reset stored users in your browser devtools run:

```js
localStorage.removeItem('scott1Users_v1');
localStorage.removeItem('scott1CurrentUser_v1');
```

Files

- `index.html` — main page

Next steps

- Commit files, run a local server, or deploy to GitHub Pages. Let me know which you prefer.
