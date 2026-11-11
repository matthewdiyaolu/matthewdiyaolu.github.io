# Matthew A. Diyaolu — academic website

Plain HTML and CSS. No build step, no theme to install, works on GitHub Pages as-is.

## Publish it (about 5 minutes)

1. Sign in to GitHub and create a **new public repository** named exactly
   `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. In the new repo, click **Add file → Upload files** and drag in *everything in this
   folder*, keeping the folders (`assets`, `images`, `files`) intact. Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

## Two things to add before sharing the link

| What | Where | Notes |
|---|---|---|
| Your photo | `images/profile.jpg` | Square crop works best. Until it exists, the sidebar shows your initials. |
| Your CV | `files/Diyaolu_CV.pdf` | The sidebar and the CV page link here. Use an academic CV **without your home address**. |

## Editing later

Every page is a single file: `index.html` (About), `research.html`, `teaching.html`,
`cv.html`. Open one on GitHub, click the pencil icon, edit the text, commit.
Changes go live within a minute or two.

- **Add a paper draft:** put the PDF in `files/`, then in `research.html` find that
  paper and replace the comment line under it with
  `<p class="paper-meta"><a href="files/YOUR-FILE.pdf">Draft (PDF)</a></p>`
- **Mark a job market paper:** in `research.html`, change that paper's badge text from
  `Chapter` to `Job Market Paper`, and move the paper to the top of the list.
- **Change the sidebar** (email, links): the sidebar block appears near the top of each
  of the four pages, so edit it in all four.
- **Colours and fonts:** `assets/css/main.css`. The site follows the visitor's light or
  dark mode automatically.

`.nojekyll` tells GitHub to serve the files exactly as they are. Leave it in place.
