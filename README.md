# Yumeng Liu — Academic Homepage

This repository contains Yumeng Liu's academic homepage, built with Jekyll and the Academic Pages template.

## Before publishing

Two placeholders must be replaced in `_config.yml`:

1. Replace every `YOUR_USERNAME` with your GitHub username.
2. Add the same username to `author.github` if you want the GitHub icon to appear.

The current public contact email is `2056168338@qq.com`. Change it in `_config.yml` if another academic email should be used.

The profile photo is `images/profile.jpg`. Replace this file with a higher-resolution formal photo when available; keep the same filename.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `YOUR_USERNAME.github.io`.
2. In this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Create academic homepage"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```

3. Open the repository on GitHub and go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. After the build finishes, visit `https://YOUR_USERNAME.github.io`.

## Update content

- English home page: `_pages/about.md`
- Research page: `_pages/research.md`
- English CV: `_pages/cv.md`
- Chinese introduction and CV: `_pages/zh.md`
- Navigation: `_data/navigation.yml`
- Sidebar and website settings: `_config.yml`

Do not publicly add an anonymous manuscript's title, abstract, or distinctive figures before its review process ends.

## Preview locally

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Acknowledgment

Based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), released under the MIT License.
