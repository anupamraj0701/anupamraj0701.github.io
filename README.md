# Publishing your site with GitHub Pages

This folder is a complete, ready-to-publish website: `index.html`, `style.css`, and an `assets/` folder with your photo and CV.

## 1. Create a GitHub account
If you don't have one: [github.com/join](https://github.com/join)

## 2. Create a new repository
1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `anupam-raj.github.io` (replace `anupam-raj` with your GitHub username, all lowercase) — this exact naming pattern is what makes GitHub host it as your personal site
3. Set it to **Public**
4. Do **not** check "Add a README" (you already have one)
5. Click **Create repository**

## 3. Upload your site files
On the new repo's page, click **"uploading an existing file"** and drag in:
- `index.html`
- `style.css`
- the whole `assets` folder (with `photo1.jpg` and `Anupam_Raj_CV.pdf` inside)

Commit the changes (the green "Commit changes" button).

*(If you're comfortable with git/terminal instead, you can `git init`, `git add .`, `git commit -m "initial site"`, and `git push` to the repo instead of using the web upload.)*

## 4. Turn on GitHub Pages
1. In your repo, go to **Settings** → **Pages** (left sidebar)
2. Under "Build and deployment" → "Source", select **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)` → **Save**

## 5. Visit your site
After a minute or two, your site will be live at:

```
https://anupam-raj.github.io
```

(with your actual GitHub username in place of `anupam-raj`)

## Making future edits
Any time you want to update content: edit `index.html` in the GitHub web editor (click the pencil icon on the file) or re-upload the changed file, commit, and the live site updates automatically within a minute.
