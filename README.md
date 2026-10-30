# David Okai Sarpong — Portfolio

Static, GitHub Pages-ready portfolio files. The recovered public repository contained only compiled assets (and its latest commits had removed those app bundles), so this version restores a maintainable source structure without a build step.

## Update personal knowledge

- Edit `src/data/davidKnowledge.js` to update the chatbot facts and public portfolio content.
- Replace `David_Sarpong_CV.pdf` in the site root when you update your CV; the homepage and contact section link to it.
- Edit `src/data/hockeyData.js` to add hockey-photo metadata. Set `year`, `institution`, `stage` and `achievement` only when verified.
- The chatbot uses a local rules-based fallback. It requires no API key and does not send visitor messages to a model service. Its system-prompt brief is in `Ask-David-System-Prompt.md` at the project deliverables root.

## Add hockey media

- Put hockey photos in `assets/hockey/moments/` or the relevant `provincial/`, `queens-college/` or `rhodes/` folder, then add a matching record to `hockeyData.js` and `davidKnowledge.js`.
- Replace `assets/hockey/video/hockey-journey.mp4` when updating the personal clip. Keep `preload="metadata"` so the full video is not downloaded until playback.
- The two supplied stills currently have neutral captions and no assigned dates or teams.

## Publish

The site is plain HTML, CSS and JavaScript modules. Serve the project directory as the site root for local preview, or publish the repository root with GitHub Pages. The root-relative asset links are set up for the existing `itsdavidketcham.github.io` domain.
