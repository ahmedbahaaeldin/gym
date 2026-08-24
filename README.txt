CUT & BUILD — install on your iPhone (one-time, ~5 minutes)

This is a small web app. Host these files anywhere with HTTPS,
then add it to your iPhone home screen. Easiest path: GitHub Pages.

1) Go to github.com -> New repository (e.g. "gym") -> create it.
2) "Add file" -> "Upload files" -> upload ALL files in this folder
   (index.html, sw.js, manifest.webmanifest, the 3 icon PNGs).
3) Repo Settings -> Pages -> Source: "Deploy from a branch"
   -> Branch: main, folder: / (root) -> Save.
4) After ~1 minute your app is live at:
   https://<your-username>.github.io/gym/
5) Open that link in SAFARI on your iPhone
   -> tap the Share button -> "Add to Home Screen".

Done. It opens full-screen like a native app, works offline after
the first load, and ALL your data (sets, weights, body weight,
history) is stored on the phone itself — nothing is uploaded.

Notes
- Deleting the home-screen icon deletes the saved data.
  Use "Export backup" in the Stats tab occasionally (it copies
  your data as text — paste it into Notes).
- To change the program later, just edit index.html and re-upload.
