# Get the Bite — Interview Lab

A standalone interview activity for grades 9–12 broadcast production, based on the supplied KHS Cougar News Interviews handbook.

## Run
Open index.html in a browser, or serve this folder with any static web server. No installation, build, external fonts, accounts, or server database is required.

## Student flow
Four rounds contain 12 scenario decisions with teaching notes and explanatory feedback. Incorrect answers allow retries. All 12 decisions must be answered correctly before the certificate download unlocks. This records practice completion, not a proctored assessment or verification of real-world interviewing skills.

Students enter a name and download a personalized 1800 × 1200 PNG certificate. A preview and a second save link provide a fallback if the first download does not begin. The name is fitted to the available space. The completion date is set when all decisions are first mastered.

Progress and the entered name are saved in this browser using local storage when available. Nothing is sent to a teacher or database. On shared devices, use Reset my progress before the next student. If embedded storage is restricted, the activity still works during the current page session.

The scenario uses fictional dialogue and supplied clip lengths and timecodes. It does not contain recorded interview audio.

## Publish in fitzkhspress-hub/2627
Keep the existing repository homepage. Add this folder as interview-lab, containing index.html, styles.css, and app.js. Do not replace the repository’s root index.html.

If GitHub Pages already publishes main / (root), the activity will be available after deployment at:
https://fitzkhspress-hub.github.io/2627/interview-lab/

Otherwise, in repository Settings → Pages, choose Deploy from a branch, main, and / (root), then Save. If the repository uses a custom deployment workflow, ensure interview-lab is included in the published output instead.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Embed after deployment

```html
<iframe
  src="https://fitzkhspress-hub.github.io/2627/interview-lab/"
  title="Get the Bite: broadcast interview challenge"
  width="100%"
  height="950"
  style="border:0"
  loading="lazy"
></iframe>
```

The receiving website must permit iframe embeds. If it adds an iframe sandbox, the activity requires scripts; image downloads also require download permission. Provide a direct link as a fallback when an embedding platform blocks downloads or storage.

## Files
- index.html: activity structure
- styles.css: responsive presentation
- app.js: content, progress, feedback, and certificate generation

The original handbook PDF is not included in the web package.
