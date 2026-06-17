# LEAD WELL Interactive Training

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` — the full interactive training page.
- `.nojekyll` — tells GitHub Pages to serve the site as-is.
- `rippling-embed.html` — iframe snippet you can paste into Rippling if the course editor supports embeds.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `leadwell-training-test`.
2. Upload the files in this folder to the root of the repository.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save.
6. GitHub will publish the page at a URL like:

   `https://YOUR-USERNAME.github.io/leadwell-training-test/`

## Test checklist

After the site is live, confirm:

- The page loads on desktop and mobile.
- Section navigation works.
- Continue and Back buttons work.
- The “Why gratitude belongs here” reveal button works.
- The reflection textbox enables the Submit and Copy buttons.
- Submit Reflection displays feedback.
- Refreshing the page preserves the reflection in the same browser through `localStorage`.
- The Copy Response button works, or shows the fallback message if the browser blocks clipboard access.

## Rippling iframe embed

After GitHub Pages is live, replace `YOUR-GITHUB-PAGES-URL` in `rippling-embed.html` with your live URL.

