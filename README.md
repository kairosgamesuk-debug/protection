# Protection Fields

A static site that plays a sequence of protection field activations. It has no build step.

## Adding or editing a field
1. Put the audio file in `audio/` (use short names without spaces, e.g. `maharic-shield.mp3`).
2. Open `index.html` and find the `FIELDS` list near the bottom.
3. Set that field's `file` to `"audio/maharic-shield.mp3"` and edit its `desc` text.

## Publishing
1. On GitHub, create a new repository (e.g. `protection-fields`) and upload everything in this folder, including the `audio` folder. Uploading in the browser allows files up to 25 MB; with git or GitHub Desktop the limit is 100 MB.
2. On Netlify, choose Add new site → Import an existing project → GitHub, then pick the repo. Leave the build command blank and set the publish directory to `.`
3. From then on, every change you push to GitHub redeploys the site automatically.
