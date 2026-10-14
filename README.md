# Your portfolio website

All of your text lives in one plain-text file, `content.txt`. Pictures go in the `images` folder. No coding needed.

## What is in the folder
- `index.html`: the site itself. You never need to open it.
- `content.txt`: ALL your text (intro, projects, skills, experience, About page). Edit this one.
- `Gabriel_Mareze_Resume.pdf`: the file the Download Resume buttons open.
- `images/`: every picture on the site.
- `.nojekyll`: an empty helper file for GitHub. Leave it.

## Replace your old site with this one
1. Unzip this folder on your computer.
2. Open your repository on GitHub and click **Add file**, then **Upload files**.
3. Drag in `index.html`, `content.txt`, `Gabriel_Mareze_Resume.pdf`, `README.md`, `.nojekyll`, and the **images folder**. Open the folder first if GitHub shows it as a single item, so the pictures land inside `images`.
4. Scroll down and click **Commit changes**. Files with the same names are replaced.
5. Wait about a minute, then hard refresh your site with Ctrl+Shift+R.

GitHub Pages should still be set to branch **main**, folder **/ (root)**. If the site ever shows a 404, check Settings, then Pages.

Everything in a public repo is public, including the pictures and the resume PDF (it has your phone number). Only upload what you are happy to share.

## Edit your text later
1. On GitHub open `content.txt` and click the pencil icon.
2. Change the text and click **Commit changes**.
3. Wait about a minute and refresh the site.

## Add pictures
1. Open the `images` folder on GitHub, click **Add file**, then **Upload files**.
2. In `content.txt`, add the file name to the project's `images:` line, for example `images: desk-pet-1.jpg, desk-pet-2.jpg`.
3. Keep pictures under about 1 MB each. Names are exact, including lowercase and `.jpg`.

## Add or remove a project
- Add: copy one whole `[project]` block, paste it where you want it, and change the text. Add `main: yes` to show it on the first page.
- Remove: delete its whole block.

## Update your resume
Upload a new PDF named exactly `Gabriel_Mareze_Resume.pdf`. GitHub replaces the old one.

## If something looks wrong
- Every `key: value` line needs the colon right after the key, with no space before it.
- Block headings like `[project]` must be on their own line, at the left edge.
- If the page says it could not load content.txt, you opened index.html straight from your computer. Use your GitHub link instead.
