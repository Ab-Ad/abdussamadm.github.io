# abdussamadm.github.io

Personal site for Abdussamad Mangalasseri, styled after the CODEX-b poster (deep space background, gold accents, Raleway + Playfair Display).

## Adding your photos

Drop image files into `assets/img/` using these exact names — the page finds them automatically, no code changes needed:

| File | Used for |
|---|---|
| `assets/img/profile.jpg` | Hero portrait (top of page) |
| `assets/img/research1.jpg` | Photo grid |
| `assets/img/research2.jpg` | Photo grid |
| `assets/img/research3.jpg` | Photo grid |
| `assets/img/cern1.jpg` | Photo grid |
| `assets/img/cern2.jpg` | Photo grid |
| `assets/img/misc1.jpg` | Photo grid |

Until you add a file, that spot shows a dashed placeholder with its filename — so the site never looks broken.

To add more photo slots than these six, copy one `<div class="photo-frame">…</div>` block inside the `#photos` section in `index.html` and give it a new filename.

## Adding hobbies / "Beyond the Lab"

Open `index.html`, find the section starting with `<section id="life">`, and replace the placeholder card with your own text, list, or photos — same pattern as the other sections.

## Publishing to GitHub Pages

Since your repo is named `abdussamadm.github.io`, GitHub will publish whatever is on the `main` branch automatically — no extra setup needed.

```bash
# from inside your local clone of abdussamadm.github.io
cp -r /path/to/this/site/* .
git add .
git commit -m "Add personal website"
git push origin main
```

Then visit `https://abdussamadm.github.io` after a minute or two.

## Notes

- I couldn't push this for you directly — I don't have write access to your GitHub account from here. Copy the files in and push whenever you're ready.
- I left the CV's two academic references (with their personal CERN/university emails) off the public site, since that contact info was given as private references for job applications rather than for public posting. Happy to add a references section back in if you'd like.
- The GitHub link in the Contact section assumes your username is `abdussamadm` — update it in `index.html` if that's wrong.
