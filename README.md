# Your portfolio website

This folder is the whole website. You edit one plain-text file (`content.txt`) and drop pictures in the `images` folder. No coding needed.

## What is in the folder
- `index.html`: the site itself. You never need to open this.
- `content.txt`: ALL your text (name, projects, experience, skills). This is the file you edit.
- `images/`: your project pictures.
- `.nojekyll`: an empty helper file for GitHub. Leave it.

## Put it online with GitHub (free)
1. Make a free account at github.com.
2. Click the + at the top right, then **New repository**. Name it `portfolio` (or `yourusername.github.io` for a shorter web address). Set it to **Public**, then **Create repository**.
3. On the new repo page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `content.txt`, `.nojekyll`, and the whole `images` folder. Click **Commit changes**.
4. Go to **Settings**, then **Pages**. Under "Branch", pick **main** and **/ (root)**, then **Save**.
5. Wait about a minute and refresh the Pages screen. It shows your link, which looks like `https://yourusername.github.io/portfolio/`.

Everything in a public repo is public, including the pictures and descriptions. Only upload what you are cleared to share.

## Edit your site later
1. On GitHub, open `content.txt` and click the pencil icon.
2. Change the text, then click **Commit changes**.
3. Wait about a minute and refresh your site.

## Add pictures
1. Open the `images` folder on GitHub, click **Add file**, then **Upload files**, and drop your pictures in.
2. In `content.txt`, find the project and add the file names, for example `images: desk-pet-1.jpg, desk-pet-2.jpg`.
3. Tip: keep pictures under about 1 MB each so the site loads fast.

## Add a project
1. In `content.txt`, copy one whole `[project]` block (from `[project]` down to the blank line).
2. Paste it where you want it. Projects show in the order they appear in the file.
3. Change the text. Add `main: yes` to show it on the first page (the first page works best with 6).
4. A project gets its own page when it has an `overview:` or bullet lines starting with `- `. Without those it shows only as a card on the All projects page.

## Remove something
Delete its whole block from `content.txt`.

## If something looks wrong
- Every `key: value` line needs the colon right after the key, with no space before it.
- Block headings like `[project]` must be on their own line, starting at the left edge.
- If the page says it could not load content.txt, you opened index.html directly from your computer. View the GitHub link instead.
